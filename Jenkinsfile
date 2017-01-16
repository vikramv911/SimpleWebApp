node {
   stage('Preparation') {
      git 'https://github.com/vikramv911/SimpleWebApp.git'
   }
   stage('Build') {
      sh "./gradlew clean test"
   }
}