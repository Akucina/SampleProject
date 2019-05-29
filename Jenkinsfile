node
{
    stage('Checkout')
    {
        checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: 'github_credentials', url: 'https://github.com/Akucina/SampleProject.git']]])
    }
    stage('Static Code Analysis')
    {
        echo "Static Code Analysis"
    }
    stage('Build')
    {
        echo "Build the code"
    }
    stage('Unit Test')
    {
        echo "Unit Test"
    } 
    stage('Delivery')
    {
        echo "Delivery"
    }   
}
