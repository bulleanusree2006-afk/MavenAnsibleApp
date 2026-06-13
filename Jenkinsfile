pipeline {
    agent any

    stages {
        stage('Ansible Deploy') {
            steps {
                sh 'ansible-playbook -i hosts.ini playbook.yml'
            }
        }
    }
}

