pipeline {
    agent any

    stages {
        stage('Evaluate Conditions') {
            steps {
                script {
                    def condition1 = (1 == 1)
                    def condition2 = (0 != 1)

                    if (condition1 && condition2) {
                        echo "Both conditions are true."
                    } else {
                        echo "One or both conditions are false."
                    }
                }
            }
        }
    }
}
