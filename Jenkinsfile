pipeline {
   agent any

   stages {
      stage('Hello') {
         steps {
            echo 'Hello World'
         }
      }
    stage('commiting sample repo') {
       steps {
          git 'https://github.com/kmayer10/maven-sample-project.git'
      }
    }
   }
}
