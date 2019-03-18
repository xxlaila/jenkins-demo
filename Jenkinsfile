node('agent-jnlp') {
    stage('Prepare') {
        echo "${JOB_NAME}"
        JOB = JOB_NAME.split('/');
        for( String JOB_NAME : JOB )
        println(JOB_NAME);  

        def JOB_NAMEWithoutBeginIndex= JOB_NAME.substring(JOB_NAME.indexOF("/"))
        println JOB_NAMEWithoutBeginIndex //JOB_NAME

        echo "it's ok"
        def log = "Exception on saving user with username:johntheripper"  
   
        def username = log.substring(log.lastIndexOf(":") + 1, log.length())    
        println username // johntheripper   
  
        def usernameWithoutEndIndex = log.substring(log.lastIndexOf(":") + 1)    
        println usernameWithoutEndIndex // johntheripper
    }
}
