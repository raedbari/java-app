
// node{
//     git  branch:'main', url: 'https://github.com/raedbari/java-app.git'
//     stage ('build'){
//         try{
//             sh 'echo "raed in build stage"'

//         }
//         catch  (Exception e){
//             sh 'echo "exception found"'
//             throw e 
//         }
//     }
//     stage ('test'){
//        if (env.BRANCH_NAME=="FA"){
//         sh'echo "raed in fa stage"'
//        }
//        else {
//         sh'echo "raed in main branch"'
//        }
//     }
// }

pipeline{
    agent any 
    stages{
        stage('build'){
          steps{
            script{
                echo "in build stage "
            }
          }
        }
          stage('test'){
           steps{
            script{
                echo "in test stage"
            }
           }
          }
    }
}