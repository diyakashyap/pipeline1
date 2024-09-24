pipeline
{
  agent any
  stages
  {
    stage('scm checkout')
    {steps{ git branch: 'main', url: 'https://github.com/prakashk0301/jenkins-test.git' }
    }

    stage('message')
    {steps{sh 'echo hello'}}
  }
}
