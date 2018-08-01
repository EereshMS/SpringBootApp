
node{
  stage('SCM Checkout'){
    git'https://github.com/EereshMS/SpringBootApp'
  }
  stage('Compile-Package'){
     sh 'mvn package'
  }
}
