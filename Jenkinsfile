pipeline {

agent any

      stages {

        stage("First Stage") {

          steps {

              retry(3) {
                  echo "Before throwing error"
                  error "error"
              }
                  echo "After throwing error"
          }

        }

      }

}

