pipeline{
    agent{
        label 'linux-worker-dev'
    }
    stages{
        stage("Compilacion"){
            sh 'mvn -DskipTests clean install package'
        }
    }
}