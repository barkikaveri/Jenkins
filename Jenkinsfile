pipeline{
    agent any
    stage('BUILD'){
        steps{
            sh '''
            #! /bin/bash
            pwd
            ls
            echo "This is BUILD stage"
            '''
        }
    }
    stage('DEPLOY'){
        steps{
            sh '"This is DEPLOY stage"'
        }
    }
    stage('TESTING1'){
        steps{
            sh 'echo "This is TESTING1 stage"'
        }
    }
    stage('TETING2'){
        steps{
          echo "This is TESTING2 stage"  
        }
    }
    }
}
