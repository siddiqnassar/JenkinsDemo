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

}
}