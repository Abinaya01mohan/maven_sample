def workspace
node
{

    stage  ("Checkout"){
        checkout([$class: 'GitSCM', branches: [[name: '*/master']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/Abinaya01mohan/maven_sample.git']]])
        workspace= pwd()
    }
    stage ("Static Code Analysis Tool"){
        echo "SAST"
    }
    stage ("Build") {
        echo "build"
        
    }
    stage ("Deploy") {
        echo "Delpoy and delivery"
    }
}

