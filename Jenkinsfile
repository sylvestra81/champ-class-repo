#!/bin/Groovy
pipeline {
agent none
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
