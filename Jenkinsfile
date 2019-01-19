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
}
node{
stage('Get approval'){
    input "Deploy to qa?"
}

    stage('deploy to qa'){
        echo "deploying"
    }
}

node{
stage('Get approval'){
    input "Deploy to Prod?"
}
    stage('deploy to Prod'){
        echo "deploying to Prod"
    }
}
