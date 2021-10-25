pipeline{
    agent any
    stages{
        stage('name1'){
            steps{
                script{
                    def a = (input message: 'please enter values', parameters: [string('a')])
                    def b = (input message: 'please enter values', parameters: [string('b')])
                    def c = (input message: 'please enter values', parameters: [string('c')])      
                    if (a.toInteger()>b.toInteger() && a.toInteger()>c.toInteger()){
                        println " a is greater"
                    }
                    else if (b.toInteger()>a.toInteger() && b.toInteger()>c.toInteger()){
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
