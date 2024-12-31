node {
	stage('Clone') {
		git 'https://github.com/Sokhnasoso/jenkins-helloworld1'
	}
	stage('Build') {
		sh label: '', script: 'javac Main;java'
	}
	stage('Run') {
		sh label: '', script: 'java Main'
	}
}
