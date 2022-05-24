pipeline{
    agent any
    stages{
        stage('defvari'){
            steps{
                script{
                    var2=20
                    println "my var value is ${var2}"
                    println "my branch name is ${BRANCH_NAME}"
                }
            }
        }
    }
}
