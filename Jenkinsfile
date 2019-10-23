node('Node03'){
  
  stage('git checkout'){
    sh 'rm -rf /var/lib/jenkins/workspace/yml_ch/check '
    sh 'git clone https://github.com/Rasmi20/check.git'
 }
  stage('yaml checking'){
   def datas = readYaml file: '/var/lib/jenkins/workspace/yml_ch/check/release.yml'
   echo "${datas}"
}
}
