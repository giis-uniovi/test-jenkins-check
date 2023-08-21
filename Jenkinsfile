node('slave-x1') {
	deleteDir()
	checkout scm
	stage("run") {
	    sh "sleep 30"
	    sh "exit 1"
	}
}
