pipeline {
    agent any
    // options {
    //     // Timeout counter starts AFTER agent is allocated
    //     timeout(time: 1, unit: 'SECONDS')
    // }
//     agent {
//   label 'jenkins-slave-1'
// }

    tools {
        maven 'mymvn'
    }

    stages {
        stage('build') {
            steps {
                sh 'mvn clean package -DskipTests=true'
            }
        }
        stage('Test') {
            steps {
                echo 'Running testing ?'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Running testing ?'
            }
        }
    }
}
