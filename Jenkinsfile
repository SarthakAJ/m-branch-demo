pipeline {
  agent {
    node {
    label "built-in"
    customWorkspace '/mnt/server'
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
