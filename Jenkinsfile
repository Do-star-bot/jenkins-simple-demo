pipeline{
  agent any

    stages{

      stage('Clone'){
        steps{
          git url:'https://github.com/Do-star-bot/jenkins-simple-demo1.git',
            branch :'main'
        }
      }
      stage('Run Script'){
        steps{
          sh 'chmod +x cript.sh'
          sh './script.sh'
        }
      }
    }
}
      
