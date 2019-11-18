/* Hello World in Groovy */
/* Hello World in Groovy */
pipeline {
         agent any 
                stages {
                     stage("1") {
                            steps {
                                 echo "hi, new file for workspace"    
                            }
                     }
                     stage("2") {
                           steps {
                             input ('do you want to proceed?')
                            }
                     }
                     stage("3") {
                          steps {
                               echo "hello"
                               }
                      }
                     stage ("4") {
                              stage ("unit test") {
                                                 steps {
                                                       echo "Running the unit test"
                                                       }
                              stage ("integration test") {
                                                  steps {
                                                      echo "running integration test"
                                                  }
                              }
                         }                     
                    }
                     
                }
}
