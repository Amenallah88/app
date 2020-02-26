node {
      stage ('SCM chekout'){
                git 'https://github.com/Amenallah88/app.git'
       }
      stage('build') {
            with (jdk: 'java8', maven: 'maven3', tempBinDir: ' '){
            sh "mvn clean install package"
          }
       }
}
