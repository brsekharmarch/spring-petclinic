node('MAVEN_JDK8') {
    stage('version control') {
        git url: 'https://github.com/brsekharmarch/spring-petclinic.git',
           branch: 'scripted'
    }
    stage('build the code') {
        sh 'export PATH="/usr/lib/jvm/java-1.11.0-openjdk-amd64/bin:$PATH" && mvn package'       
    }

}