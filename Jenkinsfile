pipeline {
   agent any
     
   stages {
      
      stage('build master') {
          when { 
                buildingTag()
           }
          
         steps {
            echo 'Hello master '
         }
      }
        }
}
