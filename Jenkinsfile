node( 'buildvm-devops' ) {
	input 'Are you certain you want to perform an install on the dev-preview-int cluster?'
	sshagent(['dev-preview-int']) {
    		sh 'ssh -o StrictHostKeyChecking=no opsmedic@use-tower1.ops.rhcloud.com install'
	}
}

