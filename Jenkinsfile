node{
    stage('Checkout'){
        git branch: 'main', url: 'https://github.com/Prithvi2801/SpringPetClinic.git'
    }
    stage('Build'){
        withMaven(maven: 'M3'){
            sh 'mvn compile'
        }
    }
}
