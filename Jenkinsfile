// Pipeline declarativo
pipeline {
    //Ejecutar desde cualquier agente (nodo) disponible
    agent any
    
    //Fases
    stages {
        stage('Build'){
            // Pasos de la fase
            steps{
                echo "Building artifact"
            }
        }
    }
    stage('Testing'){
            // Pasos de la fase
            steps{
                echo "Tes Unitarios.."
                echo "Tes Integracios.."
                echo "Tes Aceptacion..."
            }
        }
    stages {
        stage('Deploy'){
            // Pasos de la fase
            steps{
                echo "Deplay artefact"
            }
        }
    }
}
