pipeline {
  agent any
  stages {
    stage('UserInput') {
      parallel {
        stage('UserInput') {
          steps {
            echo 'Hier komt user input'
          }
        }
        stage('error') {
          steps {
            writeFile(file: 'C:\\data\\17_41_06_646_extbeal09.xml', text: 'Dit Is XML')
          }
        }
      }
    }
  }
}