 pipeline {

          agent any

          environment {

             PYTHON_HOME =  'C:\\Users\\fzfat\\AppData\\Local\\Programs\\Python\\Python310'

             PATH = '${env.PATH};${JAVA_HOME}\\bin;${PYTHON_HOME}'
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
 
