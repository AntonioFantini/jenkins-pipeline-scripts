@Library('contra-prod')
withRhProdPod{
    node(env.podName){
        stage('Stage 1'){
  // YOUR JENKINS FILE CONTENT GOES HERE
  // calling brew(), rhpkg() will utilize the tooling
       //installed in the productization-executor container
          //executeInProdExecutor('ls -latr', null, false)
            echo "Hello World"
        }
    }
}

