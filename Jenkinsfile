pipeline {
   agent {
      docker {
         label "docker"
         image "ubuntu:16.04"
      }
   }
   options {
      timestamps()
   }
   stages {
      stage('Publication') {
         steps {
            echo "Publishing to nemerosa.com"
         }
      }
   }
}
