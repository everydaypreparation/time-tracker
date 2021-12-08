node{
  stage('SCM checkout'){
    git 'https://github.com/everydaypreparation/time-tracker.git'
  }
  stage('Compile-package'){
    sh 'mvn package'
  }
}
