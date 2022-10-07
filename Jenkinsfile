pipeline {
  agent any 
  stages { 
    stage("run frontend"){
      steps {
        echo 'run frontend stage 1 : step 1'
        nodejs('Node-18.10') {
          sh 'yarn install'
        }//nodejs
      }//steps
    }//stage
    stage("run backend"){
      steps { 
        echo 'run backend stage 1 : step 1'
        withGradle(){
          sh './gradle -v'
        }//withGradle
        
      }//steps "run backend"
    }//stage "run bacend"
  }//stages
}//pipeline
