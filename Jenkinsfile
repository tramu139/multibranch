node('master') 
{
    stage('continous download') {
    git 'https://github.com/tramu139/maven.git'
}
stage('continous build') {
    sh label: '', script: 'mvn package'
}
}
