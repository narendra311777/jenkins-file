node{
   stage('SCM Checkout'){
     git 'https://github.com/narendra311777/jenkins-file.git'
   }
   stage('Compile-Package'){
      // Get maven home path
      def mvnHome =  tool name: 'M2', type: 'maven'   
      sh "${mvnHome}/bin/mvn package"
         }
   
}
