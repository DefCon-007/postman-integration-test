pipeline {
  agent any

  tools {nodejs "node"}

  stages {
    stage('Installing newman') {
      steps {
        sh 'npm install -g newman' 
      }
    }

    stage('Running Swagger collection') {
      steps {
        sh 'newman run https://api.getpostman-beta.com/collections/533486-3a50e001-84ac-46ca-8add-027338c71be9?apikey='
      }
    }
  }
}
// Script //
node {
    stage('Build') {
        echo 'Building....'
    }
    stage('Test') {
        echo 'Building....'
    }
    stage('Deploy') {
        echo 'Deploying....'
    }
}
