node{
    stage ('Build') 
    {
        sh 'git clone https://github.com/kubraokumus1/gradle-test'
        dir ('gradle-test'){
            sh 'ls -la'
            sh 'pwd'
            sh './gradlew build'
        }
    }
}
