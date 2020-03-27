pipeline {
   agent any

   stages {
      stage('Running Job3') {
         steps {
            build 'job3'
         }
      }
      stage('Running Job2') {
         steps {
            build 'job2'
         }
      }
      stage('Running Job1') {
         steps {
            build 'job1'
         }
      }
   }
