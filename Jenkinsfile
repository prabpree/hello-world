pipeline {
    agent any
    stages {
        stage('deploy')
    {
        steps {
            sh 'sudo yum -y install httpd'
}
}
}
    archiveArtifacts '/var/lib/jenkins/workspace/website/jenkinsfile'
}
