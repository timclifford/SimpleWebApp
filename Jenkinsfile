node {
   stage('Preparation') {
      git 'https://github.com/timclifford/SimpleWebApp.git'
   }
   stage('Build') {
      sh "./gradlew clean test"
   }
}