node{
 stage('SCM checkout'){
git 'https://github.com/manikarnam/Gitnew'
}
stage('compile-package'){
def mvnHome = tool name: 'MAVEN', type: 'maven'
Execute Windows batch command"(mvnHome)/bin/mvn package"
}
 }
