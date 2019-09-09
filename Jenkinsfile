pipeline {

 
agent any
 
 tools{
maven 'maven'


jdk 'jdk8'
}

 
stages {

 
stage ('Compile Stage') {

 
 

 
steps {

 
 

 
bat 'mvn clean compile'

 
}

 
}

 
 

 
 

 
stage ('Deploy Stage') {

 
 

 
steps {

 
 

 
bat 'mvn deploy'

 
}

 
}

 
 

 
 

 
}

 
}