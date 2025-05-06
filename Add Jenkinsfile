pipeline {
   angent any
  stages {
    stages("build") {
      steps {
         echo 'building the application...'
         script{
            def test =2+2 < 5?  'goood' :'bad'
            echo test
         }
      }
   } 
     stages("test") {
      steps {
         echo 'testing the application...'
 } 
} 
     stages("deploy") {
      steps {
         echo 'deploying the application...'
      }
     }
  }
}
