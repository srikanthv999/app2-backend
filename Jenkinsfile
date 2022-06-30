pipeline {
    agent any
    stages {
        stage('Build')
        {
            steps 
            {
                sh '''#!/bin/bash
                javac Hello.java
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
                echo Test Stage
                '''
            }
        }
        
    }
}