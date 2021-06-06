node{
    stage ('Build') 
    {        
        git branch: env.BRANCH_NAME, url: 'https://github.com/kubraokumus1/gradle-test'
        sh 'ls -la'
        sh 'pwd'
        sh 'gradle build'
    }
}
