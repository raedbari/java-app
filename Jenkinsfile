
node{
    git  branch:'main', url: 'https://github.com/raedbari/java-app.git'
    stage ('build'){
        try{
            sh 'echo "raed in build stage"'

        }
        catch  (Exception e){
            sh 'echo "exception found"'
            throw e 
        }
    }
    stage ('test'){
       if (env.BRANCH_NAME=="FA"){
        sh'echo "raed in fa stage"'
       }
       else {
        sh'echo "echo "raed in main branch"'
       }
    }
}