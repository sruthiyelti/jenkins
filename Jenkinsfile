node{
    
    
stage('clone java code ') {
  git 'https://github.com/vtvc/mahalogin.git'  
}

stage('maven targets') {
    sh label: '', script: 'mvn install'
}

stage('shell script') {
    sh label: '', script: 'echo "this is java project"'
}
    
stage('myshell') {
    sh label: '', script: 'echo "this is java project2"'
}
}
