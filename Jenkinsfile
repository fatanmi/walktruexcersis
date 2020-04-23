pipeline {
  agent any 
  stages {
    stage('Build') {
      steps {
        sh 'echo "Hello World"'
        sh '''
                  echo "Multiline shell steps works too"
                  ls -lah
               '''
        sh '''echo "google.com"
            echo "the answer is:" +5+5
            tidy -q -e *.html
        '''
      }
    }
  }
}
