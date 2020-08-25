pipeline {
   agent any
     
   stages {
      
      stage('build master') {
          when { 
           //     buildingTag()
                  tag "2.0"
           }
          
         steps {
            echo 'Hello master '
         }
      }
        }
}
