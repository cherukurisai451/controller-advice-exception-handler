node{

   stage('SCM Checkout'){

     git 'https://github.com/cherukurisai451/controller-advice-exception-handler.git'

   }
    stage('validate'){

      sh "mvn validate"
   }
    

   stage('Compile-Package'){

      sh "mvn compile"
     
  
  
   }
   stage('test-Package'){

      sh "mvn test"
   }
  
   
   stage('install-Package'){

      sh "mvn install"
   }
   
   }
   
   
