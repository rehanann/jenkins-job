@Library('jenkins-shared-library')_

node {
    stage('GIT Checkout'){
        echo 'Git pull'
    }
    stage('Share lib demo'){
        echo 'Shared lib demo'
        def base_var = base_var.call()
        base_var
    }
    stage('Share lib demo from class config'){
        echo 'Shared lib demo from class config'
        def base_conf = base_conf.conf()
        base_conf
    }
    stage('Share lib demo from config'){
        echo 'Shared lib demo from config'
        def myFile = base_file.myFile()
        println myFile
    }
}