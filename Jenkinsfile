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
          env.abc = "hello"
          def xyz = 10

          print "abc = ${abc}"
          print "xyz = ${xyz}"

          print abc
        }
      }
    }
    stage('test2') {
      steps {
        script {
          print abc
        }
      }
    }
  }
}