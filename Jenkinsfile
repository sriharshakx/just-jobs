pipeleine {
  agent any 
  stages {
    stage("MASTER") {
      steps {
      build(job: 'multiple-br-sample/master')
      }
    }
    
    stage("b2") {
      steps {
      build(job: 'multi2/b2')
      } }
  }
}
