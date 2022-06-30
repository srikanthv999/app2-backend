pipeline {
    agent any
    stages {
        stage('Build')
        {
            steps 
            {
                sh '''#!/bin/bash
                mvn compiler:compile
                '''
            }
        }
      stage('Execute')
        {
            steps 
            {
                sh '''#!/bin/bash
                java Hello
                '''
            }
        }
      stage('Test')
        {
            steps 
            {
                sh '''#!/bin/bash
                mvn test
                '''
            }
        }
        
    }
}