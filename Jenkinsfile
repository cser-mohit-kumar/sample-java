node {
    stage('Clone') {
        git branch: 'main',
            url: 'https://github.com/cser-mohit-kumar/sample-java.git'
    }
    stage('Run') {
        sh '''
            echo 'Hello World'
        '''
    }
}
