#!groovy

node('linux'){

sh 'echo "Hello"'
sh 'ls -al'
sh 'whoami'

parallel(
"stream 1" : {
		node('windows'){
		bat 'dir'
		bat 'ipconfig'
}}
)} 
