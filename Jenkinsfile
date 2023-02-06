node {
  stage('Clone') {
      git branch: 'main', url: 'https://github.com/amani-0911/jenkins-helloWorld'
  
   }
    stage('Build') {
        sh 'javac Main.java'
  
   }
    stage('Run') {
      sh 'java Main'
   }
   
}
