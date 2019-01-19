node {
    stage('build'){
        echo "building"
    }
}
node {
    stage('test'){
        echo "testing"
    }
}
node {
    stage('deploy to Dev'){
        echo "deploying to Dev"
    }
stage('Get approval'){
    input "Deploy to qa?"
}
node {
    stage('deploy to qa'){
        echo "deploying"
    }
stage('Get approval'){
    input "Deploy to Prod?"
}
node {
    stage('deploy to Prod'){
        echo "deploying to Prod"
    }
}
