pipeline { 
agent any
 tools{
maven 'maven'


jdk 'jdk'
}
 
stages {
stage ('Compile Stage') { 
steps {
bat 'mvn clean install'
}
}
stage ('Deploy Stage')
 {

 
 


 
steps 
{

 



 
bat 'mvn deploy'

 

}

 

}
}
}