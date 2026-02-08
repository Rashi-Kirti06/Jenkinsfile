post {
    success {
        echo 'Build Successful'
    }
    failure {
        echo 'Build Failed'
    node {
    stage('Build') {
        echo 'Build stage'
    }

    stage('Test') {
        echo 'Test stage'
    }

    stage('Deploy') {
        echo 'Deploy stage'
    }

    try {
        echo 'Pipeline execution successful'
    } catch (err) {
        echo 'Pipeline failed'
        throw err
    } finally {
        echo 'Post build action executed'
    }
}

}

