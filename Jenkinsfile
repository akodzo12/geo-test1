pipeline{
 agent any
 tools{
    M2_Home
  {
    steps{
     sh 'mvn clean'
    }
 }
 stage('maven install'){
     steps{
        sh 'mvn install'
     }
 }
 stage('maven package'){
    steps {
        sh 'mvn package'
    }
 }
 }

 }

