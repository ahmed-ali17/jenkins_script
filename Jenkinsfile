node{
    git branch: 'main',url:'https://github.com/DinaGamalMahmoud/simple-java-app.git'
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
