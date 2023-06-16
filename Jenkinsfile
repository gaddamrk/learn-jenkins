// pipeline {
//   agent 'ansible'
//
//   stages {
//     stage ('hello world') {
//       steps {
//         echo 'hello world'
//       }
//     }
//   }
// }


@Library('roboshop') _

pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        script {
          test
        }
      }
    }
  }
}