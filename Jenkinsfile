node {
    stage('clone') {
        git 'https://github.com/MassiTZ/jenkins-test.git'
    }
     stage('build') {
        sh 'javac Main.java'
    }
    stage('run') {
        sh 'java Main'
    }
}