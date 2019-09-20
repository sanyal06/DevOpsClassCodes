pipeline{
   agent {
      docker {
           image 'node: tomcat:7'
           args '-p 3000:3000 -p 5000:5000'
       }
    }
     
   enviroment {
      CI = 'true'
    }
     
   stages {
      stage('Build'){
         steps {
           sh 'echo "Hello World"'
           }
         }
     }
 }
