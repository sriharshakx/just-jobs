pipeleine {
  agent any 
  stages {
    stage("MASTER") {
      build(job: 'multiple-br-sample/master')
    }
    
    stage("b2") {
      build(job: 'multi2/b2')
    }
    
  }
}
