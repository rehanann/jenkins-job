@Library('jenkins-shared-library')_

stage('GIT Checkout'){
    echo 'Git pull'
}
stage('Share lib demo'){
    echo 'Shared lib demo'
    def base_var = base_var.call()
    println base_var
}
stage('Check path'){
    script {
        PWD = sh ('pwd')
    }
    echo "$PWD"
}
stage('Share lib demo from config'){
    echo 'Shared lib demo from config'
    // def base_conf = base_conf.conf()
    // println base_conf
}
