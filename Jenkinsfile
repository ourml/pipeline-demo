pipeline {
  agent any
  parameters {
    string(name: 'userName', defaultValue: 'Lin Li', description: 'please give a name')
    choice(name: 'version', choices: ['1.1', '1.2', '1.3'], description: 'select the version to test')
    booleanParam(name: 'is_boy', defaultValue: true, description: 'you are boy or not')
  }
  
  stages {
    stage('test') {
      steps{
        script {
          sh "java -version"
        }
      }
    }
  }
}
