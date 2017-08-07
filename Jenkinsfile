#!groovy

node('linux'){

sh 'echo "Hello"

parallel(
"stream 1" : {
		node('windows'){
		bat 'dir'
		bat 'ipconfig'
}}
)} 
