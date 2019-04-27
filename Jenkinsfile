pipeline {
 agent any
  stages {
 stage ('clean') {
  steps {
 sh "mvn clean"
}
}
stages {
 stage ('compile') {
  steps {
 sh "mvn compile"
}
}
 stages {
 stage ('test') {
  steps {
 sh "mvn test"
}
}
stages {
 stage ('package') {
  steps {
 sh "mvn package"
}
}
}
}  
