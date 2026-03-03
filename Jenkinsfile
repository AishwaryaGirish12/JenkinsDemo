pipleline {
  agent any

  stages {

    stage('Clone') {
      steps {
        git url: 'https://github.com/AishwaryaGirish12/JenkinsDemo.git',
          branch: 'main'
      }
    }
    stage('Run Script'){
      steps {
        sh 'chmod +x script.sh'
        sh 'sh./script.sh'
      }
    }
  }
}
