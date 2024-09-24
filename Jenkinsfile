pipeline
{
  agent any
  stages
  {
    stage('scm checkout')
    {steps{ git https://github.com/diyakashyap/pipeline1.git}
    }

    stage('message')
    {steps{sh 'echo hello'}}
  }
}
