node {
    stage('clone') {
        
        git 'https://github.com/ahmedchouchen/jenkins-helloworld.git'
    }
        stage('build') {
            
    sh label: '',script: 'javac Main.java'
    }
    stage('run') {
    sh label: '',script: 'java Main'

}
}
