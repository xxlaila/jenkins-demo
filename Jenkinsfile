node('agent-jnlp') {
    stage('Prepare') {
        echo "${JOB_NAME}"
        def JOB_NAME = JOB_NAME.substring(JOB_NAME.lastIndexOf("/") - 0)
        println JOB_NAME //JOB_NAME

        echo "it's ok"
        def log = "Exception on saving user with username:johntheripper"  
   
        def username = log.substring(log.lastIndexOf(":") + 1, log.length())    
        println username // johntheripper   
  
        def usernameWithoutEndIndex = log.substring(log.lastIndexOf(":") + 1)    
        println usernameWithoutEndIndex // johntheripper
        def text1 = "My last character will be removed soon"    

        println text1[0..-2] // My last character will be removed soo   

  

        def text2 = "My first word will be removed soon";    

        println text2[3..-1] // first word will be removed soon   

  

        def text3 = "noos em daer lliw uoy ,tneitap eB"    

        println text3[-1..0] 
    }
}
