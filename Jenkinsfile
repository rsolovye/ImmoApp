pipeline {
  agent any 
  stages { 
    stage("run frontend"){
      steps {
        echo 'executing yarn...'
       /* nodejs('Node-18.10') {
          sh 'yarn insall'
        }//nodejs
        */
      }//steps
    }//stage
    stage("run backend"){
      steps { 
        echo 'executing gradle...'
        withGradle(){
          sh './gradlew -v'
        }//withGradle
      }//steps "run backend"
    }//stage "run bacend"
  }//stages
}//pipeline
