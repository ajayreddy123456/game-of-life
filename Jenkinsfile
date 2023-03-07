pileline {
    agent { label 'JDK_8'}
    stages{
        stage('vcs'){
            steps{
                git url: 'https://github.com/ajayreddy123456/game-of-life.git',
                branch: 'arjun'
            }
        }
        stage( 'package' ){
            steps{
                sh 'mvn package'
            }
        }
        
    }
}