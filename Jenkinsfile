pileline {
    agent { label 'JDK_8'}
    stages{
        stage('vcs'){
            steps{
                git url: 'https://github.com/ajayreddy123456/game-of-life.git',
                branch: 'arjun'
            }
        }
        stage('package'){
            steps{
                sh 'export PATH="/usr/lib/jvm/java-1.8.0-openjdk-amd64/bin:$PATH" && mvn package'
            }
        }

    }
}