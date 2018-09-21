node ('centos-large') {
  stage('build plugin') {
    withMaven(
       maven: 'maven3'
      sh 'mvn clean install'
    )
  }
}
  
