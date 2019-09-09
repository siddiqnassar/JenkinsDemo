pipeline {

 
agent any
 
 

 
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