node {
    def mvnfile = "HelloWorld/pom.xml"
   
    stage ("checkout") {
      checkout scm
      sh "mvn -f ${mvnfile} clean install" 
    }
}
