pipeline{
  agent any;
  stages{
    stage("Git"){
      steps{
        sh 'git checkout MoatezBorgi'
        sh 'git pull origin MoatezBorgi'
      }
    }
    stage("Maven Clean and Compile"){
      steps{
        sh 'mvn clean compile'
      }
    }
  }
}
