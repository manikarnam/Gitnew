node{
 stage('SCM checkout'){
git 'https://github.com/manikarnam/Gitnew'
}
stage('compile-package'){
def mvnHome = tool name: 'MAVEN', type: 'maven'
sh"(mvnHome)/bin/mvn package"
}
 }
