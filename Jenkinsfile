pipeline {
     agent { label 'local'}
  
    stages {
        stage('Stage 1') {
    input {
                message "Should we continue?"
                ok "Yes, we should."
                submitter "Yazeed"
                parameters {
                    string(name: 'PERSON', defaultValue: 'Mr Jenkins', description: 'Who should I say hello to?')
                }
    }
   
            steps {
                
                script { 
                    properties([
                        parameters([
          
                            string(
                                
                                name: 'SP', 
                                trim: true,
                                defaultValue: 'du'
                            )
                        ])
                    ])
                }
                sh label: '', script: 'mkdir /tmp/LLLLKuuuooooouL66666'}

            }
        }
    }



