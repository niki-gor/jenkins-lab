pipeline {
    agent any 
    
    stages {
        stage('Deploy LAMP') {
            steps {
                ansiblePlaybook(
                    playbook: 'playbook.yml',
                    inventory: 'inventory.yml'
                )
            }
        }
    }
}