pipeline {

     agent any

        stages{
           stage('Git Checkout'){
                steps{
                    git 'https://github.com/thusiyanth/SpringFramwork.git'
               }
            }

             stage('UNIT Testing'){
                steps{
                    bat 'sh  \'mvn test\''


                }
            }




        }

}