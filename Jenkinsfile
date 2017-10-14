node {
    stage('Git Checkout') { // for display purposes
     echo 'Checout Code and clone it inside jenkins workspace..'
     git 'https://github.com/DeepLineTech/VirpthyPro.git'
   }
   stage('Build Test & Package') {
      echo 'Build the package'
      sh 'mvn clean compile'
   }
   stage('Results') {
       echo 'Test Results are reported..'
       sh 'mvn test'
   }
   stage('Deploy to Dev'){
       echo 'Deploy to Dev environment'
   }
   stage('Deploy to Test'){
       echo 'Deploy to Test environment'
   }
      stage('Test Automation'){
       echo 'Deploy to Dev environment'
   }
   
}
