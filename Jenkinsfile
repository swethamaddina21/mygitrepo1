pipeline{
    agent any
    environment {
  batchno = "3"
  JAVA_HOME = "/opt/java"
}
    parameters {
  choice choices: ['dev ', 'prod', 'preprod'], name: 'env'
}
    stages{
        stage('name1'){
            steps{
                script{
                    a=10
                    if (a>= 10){
                        println "value os a is eaual to ${a}"
                    }
                }
            }
            
        }
    }
}
