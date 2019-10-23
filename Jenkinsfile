pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        script{
          def datas = readYaml file: 'release.yml'
          echo "${datas}"
       }
      }
    }
  }
}
