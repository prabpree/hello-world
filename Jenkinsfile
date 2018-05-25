pipeline {
    agent any
    stages {
        stage('deploy')
    {
        steps {
            checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: 'JenkinsUserKey', url: 'https://github.com/prabpree/hello-world']]])
}
}
}
    archiveArtifacts 'jenkinsfile'
}
