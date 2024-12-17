node {
    stage('clone') {
       git 'https://github.com/hssen-bengamra/jenkins-helloworld.git'
   }
   stage('build') {
       git 'https://github.com/hssen-bengamra/jenkins-helloworld.git'
       sh '''
            javac Main.java
          '''
   }
   stage('run') {
       git 'https://github.com/hssen-bengamra/jenkins-helloworld.git'
       sh '''
            java Main
          '''
   }
}