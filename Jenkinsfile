node ('node:16-buster-slim') {
    def PORT = 3000

    stage('Build') {
        sh 'npm install'
    }
    stage('test') {
        sh './jenkins/scripts/test.sh'
    }
}