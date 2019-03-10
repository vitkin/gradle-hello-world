pipeline {    
    agent {
        node 'slave1'
    }    
    stages {        
        stage('Check-out') {            
            steps {                
                scm checkout            
            }        
        }        
        stage('Build') 
        {            
            steps {                
                sh 'gradle build'  
            }        
        }    
    }
}
