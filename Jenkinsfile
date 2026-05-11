pipeline {
 agent any
 stages {
 stage('Clone') {
 steps {
 git 'https://github.com/deekshithgt07/MyMavenSeleniumApp.git'
 }
 }
 stage('Build') {
 steps {
 sh 'mvn clean compile'
 }
 }
 stage('Test Automation') {
 steps {
 sh 'mvn test'
 }
 }
 }
}
