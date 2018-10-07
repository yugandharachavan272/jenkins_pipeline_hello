node {
    stage('build'){
        echo "building"
    }
}
stage('Deploy approval'){
    input "Deploy to qa?"
}
node {
    stage('deploy to qa'){
        echo "deploying"
    }
}
