pipeline {
    agent {
        node {
            label 'built-in'
            customWorkspace '/mnt/grp3'
        }
    }
    stages {
        stage ('new-folder') {
            steps {
                sh 'mkdir mock-99'
            }
        }
    }
}
