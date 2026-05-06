pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Task: Compiling source code and packaging the application.'
                echo 'Tool: Apache Maven'
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo 'Task: Running JUnit tests for logic and Selenium for component interaction.'
                echo 'Tools: JUnit, Selenium'
            }
        }

        stage('Code Analysis') {
            steps {
                echo 'Task: Analyzing code quality against industry standards.'
                echo 'Tool: SonarQube'
            }
        }

        stage('Security Scan') {
            steps {
                echo 'Task: Identifying vulnerabilities in code and dependencies.'
                echo 'Tool: Snyk'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Task: Deploying application to the staging environment.'
                echo 'Tool: AWS EC2 / Ansible'
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo 'Task: Running E2E tests in a production-like environment.'
                echo 'Tool: Postman/Newman'
            }
        }

        stage('Deploy to Production') {
            steps {
                echo 'Task: Final deployment to the live production server.'
                echo 'Tool: AWS EC2'
            }
        }
    }
}
