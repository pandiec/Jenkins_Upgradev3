pipeline {
      agent any
      stages {
            stage('Init') {
                  steps {
                        echo 'Hi, this is Pandiyan from LevelUp360'
                        echo 'We are Starting the Testing'
                  }
            }
            stage('Build') {
                  steps {
                        echo 'Building Sample Maven Project'
                  }
            }
            stage('Deploy') {
                  steps {
                        echo "Deploying in Staging Area"
                  }
            }
            stage('Pre-Production') {
                  steps {
                        echo "Deploying in Pre-Production Area"
                  }
            stage('Final Production') {
                  steps {
                        echo "Deploying in Production Area"
                  }
            }
      }
}
