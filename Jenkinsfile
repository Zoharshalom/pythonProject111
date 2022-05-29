properties([pipelineTriggers([pollSCM('* * * * *')])])
node {
    stage('clone'){
        git "https://github.com/Zoharshalom/pythonProject111.git"
    }
    stage('show files'){
        bat "dir"
    }
        
}
