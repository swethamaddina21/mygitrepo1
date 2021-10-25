pipeline{
    agent any
    stages{
        stage('name1'){
            steps{
                script{
                    a.toInteger = input message: 'please enter values', parameters: [string('a')]
                    b.toInteger = input message: 'please enter values', parameters: [string('b')]
                    c.toInteger = input message: 'please enter values', parameters: [string('c')]      
                    if (a>b && a>c){
                        println " a is greater"
                    }
                    if (b>a && b>c){
                        println "b is greater"
                    }
                    else{
                        println "c is greater"
                    }                   
                }                    
            }            
        }
    }
}
