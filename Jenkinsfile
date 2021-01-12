node{
stage('SCM Checkout')
{
git 'https://github.com/msabareesh92/newjave.git'
echo "pulling the code"
}
stage('compile')
{
 sh 'mvn package'
}
}
