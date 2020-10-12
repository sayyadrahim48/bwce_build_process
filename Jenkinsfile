node {
	checkout scm
	docker.withRegistry('https://registry.hub.docker.com','dockerHub'){
		def customImage = docker.build("sayyad8855/rahim-repository:myapp")
		customImage.push()
		}
}


