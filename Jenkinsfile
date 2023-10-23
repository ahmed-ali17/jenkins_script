node{
    git branch: 'main',url:''
    stage{'build'}{
        try{
            sh 'echo "build stage"'
        }
        catch(Exception e){
            sh 'ecgitho "Exception"'
        }
    }
    stage{'test'}{
        if (env.BRANCH == 'feature'){
            sh 'echo "test stage"'
        }
    }
}
