
pipeline {

  agent any

  options {

    buildDiscarder logRotator(artifactDaysToKeepStr: '', artifactNumToKeepStr: '5', daysToKeepStr: '', numToKeepStr: '5')

  }

  stages {

    stage('HelloMultibranchPipeline..Branch1!!!') {

      steps {

       bat "cmd /c echo hello multibranch !!!!!!!!!!!"

      }

    }

  }

}
