node('agent-jnlp') {
    stage('Prepare') {
        echo "${JOB_NAME}"
        def log = "Exception on saving user with username:johntheripper"  
   
        def username = log.substring(log.lastIndexOf(":") + 1, log.length())    
        println username // johntheripper   
  
        def usernameWithoutEndIndex = log.substring(log.lastIndexOf(":") + 1)    
        println usernameWithoutEndIndex // johntheripper
    }
}
