node {
    stage('Code Clone') {
		git branch: 'main', url: 'https://github.com/Rameshagwd/Multipipeline.git'
    }
	
	stage('MVN Clean') {
		sh 'mvn clean'
    }
	
	stage('MVN validate') {
		sh 'mvn validate'
    }
	
	stage('MVN compile') {
		sh 'mvn compile'
    }
	
	stage('MVN test') {
		sh 'mvn test'
    }
	
	stage('MVN package') {
		sh 'mvn package'
    }
}