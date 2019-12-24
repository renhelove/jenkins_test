/* 需要 Docker Pipeline 插件 */
node('docker') {
    checkout scm
    stage('Build') {
        docker.image('php').inside {
            sh 'php --version'
        }
    }
}
