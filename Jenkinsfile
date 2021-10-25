pipeline {
  agent any 
  stages {
    stage('working with if conditions') {
      steps {
        script {
          def myval1 = input message: 'enter myval1 value', parameters: [string(defaultValue: '20', description: '', name: 'myval1', trim: false)]
          if(myval1.toInteger() == 10) {
            println "myval1 value is $mval1"
          }
          else if (myval1.toInteger() == 20)
          {
              println "myval1 value is $myval1"
          }
          else {
              println "$myval1 not satisfies if condition"
          }
        }
      }
    }
  }
}
