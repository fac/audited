#!groovy

@Library('freeagent') _

freeagentGem( slack: [channel: '#rails-next'] ) {
  stage("Setup Test") {
  bash '''
    sudo apt-get install libpq-dev
    '''
  }
  stage("Test") {
//   bundle.exec "rake"
  }
}
