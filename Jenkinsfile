
node {
  stage('checkout sources') {
        // You should change this to be the appropriate thing
        git url: 'https://github.com/jemarbush1/ci-lab'
  }

  stage('Build') {
    // you should build this repo with a maven build step here
    withMaven (maven: 'maven3') {
                   sh "mvn package"
                 }
  }
  // you should add a test report here
}
