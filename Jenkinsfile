node('slave-x1') {
	deleteDir()
	checkout scm
	stage("run") {
	    sh "sleep 10"
	    sh "exit 0"
	}
}
