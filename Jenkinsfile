// Pipeline declarativo
pipeline {
    //Ejecutar desde cualquier agente (nodo) disponible
    agent any
    
    //Fases
    stages {
        stage('Fase 1 - Build'){
            // Pasos de la fase
            steps{
                echo "Fase 1 paso 1..."
            }
        }
		stage('Fase 2 - Testing'){
            // Pasos de la fase
            steps{
                echo "Tes Unitarios.."
                echo "Tes Integracios.."
                echo "Tes Aceptacion..."
            }
        }
		stage('Fase 3 - Deploy'){
            // Pasos de la fase
            steps{
                echo "desplegando artefecto.."
            }
        }
    }
 }
