pipeline{
        agent any
        stages{
            stage('clean'){
              steps{
              echo 'Build Stage'
              sh 'mvn clean'
             }
            }
            
            stage('test'){
              steps{
              echo 'Test Stage'
              sh 'mvn test'
             }
            }
            stage('install'){
              steps{
              echo 'Install Stage'
              sh 'mvn install'
             }
            }
            stage('deploy'){
              steps{
              echo 'Install Stage'
              sh 'mvn deploy'
             }
            }
        }
}
