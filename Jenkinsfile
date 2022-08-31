pipeline{ 
       agent any
  stages{
    stage(' 1-clone'){ 
      steps{
      checkout([$class: 'GitSCM', branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[credentialsId: 'Git', url: 'https://github.com/candinegits/grp3-repo.git']]])
      }
    }
  }
}
