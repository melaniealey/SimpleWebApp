node {
   stage('Preparation') {
      git 'https://github.com/Jetski5822/SimpleWebApp.git'
   }
   stage('Build') {
      sh "./gradlew clean test"
   }
}