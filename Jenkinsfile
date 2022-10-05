pipeline {
  agent any 
  stages { 
    stage("run frontend"){
      steps {
        echo 'run frontend stage 1 : step 1'
       /* nodejs('Node-18.10') {
          sh 'yarn insall'
        }//nodejs
        */
      }//steps
    steps {
        echo 'run frontend stage 1 : step 2'
      
    }//stage
    stage("run backend"){
      steps { 
        echo 'run backend stage 1 : step 1'
        /*withGradle(){
          sh './gradlew -v'
        */
        }//withGradle
      }//steps "run backend"
    }//stage "run bacend"
  }//stages
}//pipeline
