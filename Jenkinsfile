node('master')
{
    stage('ContinuousDownload_master') 
    {
         git 'https://github.com/selenium-saikrishna/maven.git'
    }
    stage('ContinuousBuild_master') 
    {
         sh label: '', script: 'mvn package'
    }
    
    
}

