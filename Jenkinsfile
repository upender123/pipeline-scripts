pipeline {

agent any

      stages {

        stage("Stage1") {

          steps {

              retry(3) {
                  echo "Before throwing error"
                  //error "error"
              }
                  echo "After throwing error"
          }

        }

      }

}

