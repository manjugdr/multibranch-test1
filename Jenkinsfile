pipeline{
    agent any
    stages{
                stage('Validate1'){
                               steps{
                sh 'sleep 5'
                echo 'Validate'
            }
        }
        stage('Compile1'){
                       steps{
                sh 'sleep 5'
                echo 'compile'
            }
        }
   stage ( 'paralle' ) {
   parallel {
        stage('test'){
                        steps{
                sh 'sleep 5'
                echo 'test'
            }
        }
        stage('package'){
                        steps{
                sh 'sleep 5'
                echo 'package'
            }
}
}
}
         stage('verify'){
                         steps{
                sh 'sleep 5'
                echo 'verify'
            }
}
        stage('install'){
                       steps{
                sh 'sleep 5'
                echo 'install'
            }
        }
        stage('deploy'){
                        steps{
                sh 'sleep 5'
                echo 'deploy'
            }
        }
    }
}
