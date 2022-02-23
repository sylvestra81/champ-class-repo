#!/bin/Groovy
pipeline {
agent any
stages {
stage( 'Create user account') {

steps {

sh 'useradd fola && echo “reset4U$” |passwd — stdin fola'

}
}
stage('Check fola ID') {

steps {

sh 'id fola'

}
}
}
}
