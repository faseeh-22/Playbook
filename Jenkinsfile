pipeline {
    agent any

    stages {
        stage('Run playbook') {
            steps {
                script {
                    sh '''
                        cd /home/faseeh
                        ansible-playbook -b -i invent.ini nginx.yml
                    '''
                }
            }
        }
    }
}

