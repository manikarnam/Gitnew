node{
 stage('SCM checkout'){
git 'https://github.com/manikarnam/Gitnew'
}
stage('compile-package'){
def MVN_HOME = tool name: 'MAVEN', type: 'maven'
 echo "(%MVN_HOME%)/bin/mvn package"
echo "mvn package"
}
 }
