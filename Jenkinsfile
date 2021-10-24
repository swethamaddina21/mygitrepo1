pipeline{
    agent any
    environment {
  batchno = "3"
  JAVA_HOME = "/opt/java"
}
    stages{
        stage('name1'){
            steps{
                script{
                    var1=10
                    test = "hiteam"
                    println "hi welcome to jwnkins pipeline ${var1} ${test}"
                    println "batchno is ${env.batchno}"
                    println "java path is ${env.JAVA_HOME}"
                }
            }
            
        }
    }
}
