pipeline{
	agent any
	stages{
		stage('build') {
  steps {
    mvn package
  }

  tools {
    maven 'mymvn'
  }
}

	}
}
