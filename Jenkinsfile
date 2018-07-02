node {
   stage('Preparation') {
      git 'https://github.com/melaniealey/SimpleWebApp.git'
   }
   stage('Build') {
      sh "./gradlew clean test"
   }
}