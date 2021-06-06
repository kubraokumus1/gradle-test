node{
    stage ('Build') 
    {
        sh 'rm -r gradle-test'
        sh 'git clone https://github.com/kubraokumus1/gradle-test'
        dir ('gradle-test'){
            sh 'ls -la'
            sh 'pwd'
            sh './gradlew build'
        }
    }
}
