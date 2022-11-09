pipeline {

     agent any

        stages{
           stage('Git Checkout'){
                steps{
                    git 'https://github.com/thusiyanth/springDevApplication.git'
               }
            }

             stage('UNIT Testing'){
                steps{
                    sh 'mvn test'


                }
            }




        }

}
