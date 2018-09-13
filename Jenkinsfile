pipeline {
  agent any
  stages {
    stage('Stage1') {
      parallel {
        stage('Stage1') {
          steps {
            bat 'echo "hello\''
          }
        }
        stage('stage2') {
          steps {
            bat 'echo \'you mama is a llama\''
          }
        }
        stage('stage3') {
          steps {
            bat 'echo \'the end\''
          }
        }
        stage('') {
          steps {
            bat 'echo "you suck"'
          }
        }
      }
    }
  }
}