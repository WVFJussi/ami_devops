pipeline {
  agent any
  stages {
    stage('TestDemo') {
      steps {
        mail(subject: 'Jenkins testmail', body: 'Testipostia Jenkinsin pipelinen tekovaiheessa.', charset: 'utf-8', from: 'devops_ami@amiedu.fi', replyTo: 'valkanjussi@mail.com', to: 'juhani.ikonen@wippies.fi')
      }
    }
  }
}