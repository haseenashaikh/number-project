pipeline{
    agent any
    stages{
        stage('git clone'){
            steps{
                sh'''
                pwd
                rm -rf *
                git clone 
                '''
            }
        }
        stage('hello'){
            steps{
                sh'''
                '''
            }
        }
        stage('today date'){
            steps{
                sh'''
                echo "hello today $(date)"
                '''
            }
        }
    }
}
