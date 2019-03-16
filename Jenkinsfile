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
stage('Get approval'){
    input "Deploy to qa?"
}
node {
    stage('deploy to qa'){
        echo "deploying"
    }
}
mystage('Get approval'){
    input "Deploy to prod"
}    
node {
    mystage('deploy to prod'){
        echo "deployment to prod"
    }
}    
