pipeline
{
  agent any
  stages
  {
    stage('scm checkout')
    {steps{ git branch: 'main', url: 'https://github.com/prakashk0301/jenkins-test.git' }
    {steps{ git 'https://github.com/diyakashyap/pipeline1.git'}
    }

    stage('message')
    {steps{sh 'echo hello'}}
  }
}
