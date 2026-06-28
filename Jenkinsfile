node {

    stage('Checkout') {
        checkout scm
    }
    stage('Run Python') {
        sh 'python3 run.py'
    }
    stage('Test Python') {
        sh 'python3 test.py'
    }
}
