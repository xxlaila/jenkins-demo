node('agent-jnlp') {
    stage('Prepare') {
        echo "${JOB_NAME}"
        script {
            def JOB_NAME='${JOB_NAME}|awk -F'/' '{print $1}''
            echo "${JOB_NAME}"
        }
    }
}
