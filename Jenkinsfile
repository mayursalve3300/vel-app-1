pipeline {
	agent {
		label{
			label "slave-2"
			}
		}
		
		stages {
			stage ('deploy-index') {
				steps {
					sh "sudo cp -r index.html /var/www/html/"
					sh "sudo chmod -R 777 /var/www/html"
				}
			
			}
		}
}
