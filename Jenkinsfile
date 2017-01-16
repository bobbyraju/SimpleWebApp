node {
   stage('Preparation') {
      git 'https://github.com/bobbyraju/SimpleWebApp.git'
   }
   stage('Build') {
      sh "./gradlew clean test"
   }
}