pipeline{
    agent any
    stages{
        stage('name1'){
            steps{
                script{
                    a = (input message: 'please enter values', parameters: [string('a')]).toInteger()
                    b = (input message: 'please enter values', parameters: [string('b')]).toInteger()
                    c = (input message: 'please enter values', parameters: [string('c')]).toInteger()      
                    if (a>b && a>c){
                        println " a is greater"
                    }
                    else if (b>a && b>c){
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
