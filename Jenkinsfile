node
{
    
 stage('Checkout')   {
     checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: '92d6e340-851e-48ba-8897-10a92dab6edb', url: 'https://github.com/zonski/hello-javafx-maven-example.git']]])
     
 }
 
 stage('Static code analysis')
 {
     echo "Static Code Analysis"
 }
 
 
 stage('Build')
 {
     echo 'Build the code'
 }
 
 stage('Deploy')
 {
     echo 'Deploy the code'
 }
 
}
