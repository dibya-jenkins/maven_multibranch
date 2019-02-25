node('master') 
{
   stage('ContnuousDownload_master') 
   {
      git 'https://github.com/selenium-saikrishna/maven.git'
   }
   stage('ContnuousBuild_master') 
   {
      sh label: '', script: 'mvn package'
   }
   
   
   
}
