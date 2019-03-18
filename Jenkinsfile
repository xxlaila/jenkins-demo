node('agent-jnlp') {
    stage('Prepare') {
        echo "${JOB_NAME}"
        sh "JOB_NAME=echo "${JOB_NAME}"| awk -F'/' '{print $1}'" 
    }
}
