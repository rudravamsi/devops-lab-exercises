pipeline { 
    agent any 
    parameters { 
        string(name: 'VERSION', defaultValue: '1.0', description: 'Build version') 
    } 
    stages { 
        stage('Build') { 
            steps { 
                bat "echo Building version \${VERSION} > pipeline-output.txt" 
            } 
        } 
        stage('Test') { 
            steps { 
                bat "echo Testing version \${VERSION} > test-output.txt" 
            } 
        } 
    } 
} 
