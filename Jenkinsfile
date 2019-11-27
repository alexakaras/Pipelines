pipeline {
    agent any
    stages {
        stage('---ifconfig---') {
            steps {
                sh "ifconfig"
            }
        }
        stage('--Copy--') {
            steps {
                sh "Xcopy \\FS4\Projects\Development\Internal\Builds\17.00\14_17_00_808\release\enodeb.14_17_00_808.enc \\192.168.60.252\sftp\upload\enodeb.14_17_00_808.enc /syq"
            }
        }
        stage('--Verify--') {
            steps {
                sh "whoami"
            }
        }
    }
}
