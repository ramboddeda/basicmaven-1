node{
  stage('SCM Checkout'){
    git 'https://github.com/rangaraju29139/basicmaven'
  }
  stage('Compile-Package'){
  def mvnhome =tool name: 'maven3',type:'maven'
    sh "${mvnhome}/bin/mvn package" 
  }
}
