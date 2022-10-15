pipeline{
    agent any
    stages{
        stage('git clone'){
            steps{
                sh'''
                pwd
                rm -rf *
                git clone https://github.com/haseenashaikh/number-project.git
                '''
            }
        }
        stage('maven1'){
            steps{
                sh'''
                mvn compile
                '''
            }
        }
        stage('maven2'){
            steps{
                sh'''
                mvn test
                '''
            }
        }
        stage('maven3'){
            steps{
                sh'''
                mvn clean
                '''
            }
        }
        stage('maven4'){
            steps{
                sh'''
                mvn install package
                '''
            }
        }
    }
}
