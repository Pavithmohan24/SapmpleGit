node{
  stage('SCM Checkout'){
    git 'https://github.com/Pavithmohan24/SapmpleGit'
  }
  stage('Compile-Package'){
    //
    def MAVEN_HOME =  tool name: 'maven', type: 'maven'
    sh "${MAVEN_HOME}/bin/mvn package"
  }
  
}
