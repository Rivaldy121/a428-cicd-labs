node {
    def dockerImage = 'node:16-buster-slim'
    def dockerRun = docker.image(dockerImage).withRun('-p 3000:3000')

    stage('Build') {
        sh 'npm install'
    }
    stage('test') {
        sh './jenkins/scripts/test.sh'
    }
}