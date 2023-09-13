node {
    stage('Build') {
        sh 'npm install'
    }
    stage('test') {
        sh './jenkins/scripts/test.sh'
    }
}