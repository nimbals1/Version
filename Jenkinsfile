node {
	  // Mark the code checkout 'stage'....	  
	stage 'Stage Checkout'
	
	  // Checkout code from repository and update any submodules	  checkout scm
	  sh 'git submodule update --init'  
	
	  stage 'Stage Build'

                    sh './gradlew --console=plain --no-daemon --info --stacktrace'
}
