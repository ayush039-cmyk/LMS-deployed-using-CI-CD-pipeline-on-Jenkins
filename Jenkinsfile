pipeline {
     agent any

    stages {

        stage('Setup') {
            steps {
                sh '''
                cd Library-Management-System-Containerized-and-Deployed-on-Kubernetes-Minikube-
                pip install --break-system-packages -r requirements.txt
                '''
            
            }
        }
        stage('Deployment') {
            input {
                message "Do you want to proceed further?"
                ok "Yes"
            }
            steps {
                echo "Running Deployment"
                
            }
        } 
        
            
    }
}
