node{
  stage('SCM Checkout'){
    tool name: 'maven', type: 'maven'
    
    git 'https://github.com/Pavithmohan24/SapmpleGit'
  }
  stage('Compile-Package'){
    sh 'mvn package'
  }
  
}
