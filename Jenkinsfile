pipeline {
  agent {
    label {
    label "built-in"
    customWorkspace '/mnt/server'
  }
  }
  stages{
    stage ("one") {
      steps{
        echo "this is master branch"
      }
    }
  }
}
