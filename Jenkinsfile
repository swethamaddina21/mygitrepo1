pipeline{
    agent any
    stages{
        stage('name1'){
            steps{
                script{
                    def a.toInteger() = input message: 'please enter values', parameters: [string('a')]
                    def b.toInteger() = input message: 'please enter values', parameters: [string('b')]
                    def c.toInteger() = input message: 'please enter values', parameters: [string('c')]      
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
