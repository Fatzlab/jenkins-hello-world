 pipeline {

          agent any

          environment {

             SYSTEM32 = 'C:\\Windows\\System32'
            
             PYTHON_HOME =  'C:\\Users\\fzfat\\AppData\\Local\\Programs\\Python\\Python310'

             PATH = "${SYSTEM32};${PYTHON_HOME};${env.PATH}"
         }
            
          stages {

              stage('Build') {

                  steps {

                      script {

                          // Choisissez la commande en fonction de votre script

                          bat 'python hello.py' // Pour Python

                       
                      }

                  }

              }

          }

      }
 
