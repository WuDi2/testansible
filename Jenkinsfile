pipeline {
    agent any

    stages {
        stage('test ansible plugins') {
            steps {
				ansiblePlaybook inventory: '/etc/ansible/inventory', playbook: '/etc/ansible/testplaybooks.yml'           
            }
        }
    }
}