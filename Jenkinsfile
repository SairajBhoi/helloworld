node {
  stage('checkout'){
    git url: 'https://github.com/SairajBhoi/helloworld.git'
  }
  
  stage('Build'){
      dir('helloworld/src/main/java/com/coveros/demo/helloworld/') {
         bat 'javac HelloWorld.java'
      } 
    stage('run'){
      dir('helloworld/src/main/java/com/coveros/demo/helloworld/') {
         bat 'java HelloWorld.main'
      } 
  }
