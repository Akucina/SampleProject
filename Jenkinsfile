node
{
    stage('Checkout')
    {
        checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: 'caa2c3e3-74cb-4bcd-af49-514a4f0ec36f', url: 'https://github.com/Akucina/SampleProject']]])
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
