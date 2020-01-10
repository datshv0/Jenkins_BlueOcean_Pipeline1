pipeline {
  agent any
  stages {
    stage('Saludo') {
      steps {
        echo "Hello ${params.PERSON}"
      }
    }

    stage('Despedida') {
      steps {
        echo 'hasta luego'
      }
    }

  }
  parameters {
    string(name: 'PERSON', defaultValue: 'Mr Jenkins', description: 'Who should I say hello to?')
  }
}