node('master')
{
    stage('ContinuousDownload_Loans') 
    {
         git 'https://github.com/selenium-saikrishna/maven.git'
    }
    stage('ContinuousBuild_Loans') 
    {
         sh label: '', script: 'mvn package'
    }
    
    
}

