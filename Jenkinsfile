pipeline {

agent any

tools {

maven 'Maven'

}

stages {

stage('Build') {

steps {

sh 'mvn clean compile'

}

}

stage('Test') {

steps {

sh 'mvn test'
#instead of bat write sh
}

}

}

}
