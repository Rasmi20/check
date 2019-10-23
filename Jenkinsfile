node('Node03'){
  datas = readYaml file: 'release.yml'
  stage('git checkout'){
    sh 'git clone https://github.com/Rasmi20/check.git'
 }
  stage('yaml checking'){
   echo "${datas}"
}
}
