node {
  stage('checkout'){
    git url: 'https://github.com/SairajBhoi/helloworld.git'
  }
  
  stage('Build'){
       {
         bat 'javac HelloWorld.java'
      } 
    stage('run'){
      {
         bat 'java HelloWorld'
      } 
  }
  }
}
