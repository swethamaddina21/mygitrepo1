pipeline{
    agent any
    stages{
        stage('name1'){
            steps{
                script{
		    for (i=1;i<=10;i++){
	                println "value of i is ${i}"
			while(i==5){
			    continue;
			}
    	            }                               
		    for (i in [10..15]){
		        println "value of i is ${i}"
			while(i==11){
			    break;
			}
		    }		   
                }                    
            }            
        }
    }
}
