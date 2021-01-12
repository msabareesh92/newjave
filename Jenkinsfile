node{
stage('SCM Checkout')
{
git 'https://github.com/msabareesh92/newjave.git'
echo "pulling the code"
}
stage('compile')
{
 def Home=tool name: 'maven-1', type: 'maven'
 sh "${Home}/bin/mvn package"
}
}
