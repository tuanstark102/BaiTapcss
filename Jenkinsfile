pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                echo 'Cloning repository...'
                // Jenkins tự clone nên chỉ cần log
            }
        }

        stage('Build') {
            steps {
                echo 'Building project...'
                // Không có bước build vì đây là HTML/CSS
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                // Bạn có thể thêm kiểm tra định dạng HTML/CSS nếu muốn
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Có thể dùng rsync, FTP, hoặc đẩy sang S3 nếu cần
            }
        }
    }
}
