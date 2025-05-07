pipeline {
  agent {
    node {
    label "built-in"
    currentWorkspace '/mnt/server'
  }
  }
  stages{
    stage ("one") {
      steps{
        echo "this is demo branch"
      }
    }
  }
}
