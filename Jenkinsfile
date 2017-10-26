pipeline{
    agent any
    tools{
        maven 'apache-maven-3.3.9'
        jdk 'jdk1.8.0_121'
    }
    stages{
        stage ('Initialize') {
            steps {
                sh '''
                    echo "PATH = ${PATH}"
                    echo "M2_HOME = ${M2_HOME}"
                '''
            }
        }
    }
}
