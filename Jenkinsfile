  node
{
    stage('checkout')
    {
        checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: 'https://github.com/Kgasr/Git_Sample']]])
        workspace = pwd()
    }
    stage('Static Code Analysis')
    {
        echo "Static code analysis"
    }
    stage('Build')
    {
        echo "Build the code"
    }
    stage('Unit Testing')
    {
        echo "Unit Testing"
    }
    stage('Delivery')
    {
        echo "Delivery"
    }
}  
