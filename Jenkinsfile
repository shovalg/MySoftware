properties([pipelineTriggers([pollSCM('30 * * * *')])])
node {
  stage("hook to git repo"){
    git branch: 'main', url: 'https://github.com/shovalg/MySoftware.git/'
  }
  stage("Ex.demo"){
    bat "dir"
  }
}
