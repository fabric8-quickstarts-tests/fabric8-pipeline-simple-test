@Library('github.com/fabric8io/fabric8-pipeline-library@master')_
clientsTemplate{
    mavenNode{
        container('maven'){
            sh 'mvn -version'
        }
        container('clients'){
            sh 'kedge version'
        } 
    }
}
