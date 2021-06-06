node{
    stage ('Build') 
    {
        sh 'env'        
        git branch: 'stable-2.204', url: 'https://github.com/kubraokumus1/gradle-test'
        dir ('gradle-test'){
            sh 'ls -la'
            sh 'pwd'
            sh 'gradle build'
        }
    }
}
