pipeline{
  agent any
  stages{
    stage('Clone'){
      steps{
        git branch: 'main',
          url : 'https://github.com/Likitha-046/jenkins_simple_demo2.git'
      }
    }
    stage('Run Script'){
      steps{
        sh 'chmod +x script.sh'
        sh './script.sh'
      }
    }
  }
}
