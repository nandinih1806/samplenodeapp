pipeline {
   agent any
   stages {
  stage('Building image') {
    steps{
       script{
          docker.build("nandinih1806/samplenodeapp")
       }
    }
  }
   }
}
