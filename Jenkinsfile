
node{
  stage('SCM Checkout'){
    git'https://github.com/EereshMS/SpringBootApp'
  }
  stage('Compile-Package'){
    def mavenHome = tool name: 'maven', type:'maven' 
    
    sh "${mavenHome}/bin/ mvn package"
  }
}
