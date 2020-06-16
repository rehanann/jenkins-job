@Library('jenkins-shared-library')_

stage('GIT Checkout'){
    echo 'Git pull'
}
stage('Share lib demo'){
    echo 'Shared lib demo'
    def base_var = base_var.call()
    println base_var
}
stage('Share lib demo from config'){
    echo 'Shared lib demo from config'
    // sh "pwd"
    // sh "ls -l"
    def base_conf = base_conf.conf_tag()
    println base_conf.branching
}