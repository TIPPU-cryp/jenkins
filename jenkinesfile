node{
    stage('SCM Checkout'){
        git 'https://github.com/TIPPU-cryp/jenkins.git'
    }
    stage('Compile-Pakage'){
        //Get maveen home path
        def mvnHome = tool name : 'maven-3',type: 'maven'
            sh "${mvnHome}//bin/mvn package"
    }
stage('Email Notification'){
    
}
}
