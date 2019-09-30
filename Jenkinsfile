pipeline {
     agent any
     stages {
          stage("Compile") {
               steps {
                    sh "./gradlew compile"
               }
          }
         
{		  
stage("Package") {
     steps {
          sh "./gradlew build"
     }
}
}

}
}
