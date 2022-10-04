node{
     
    stage('SCM Checkout'){
        git url: 'https://github.com/prashanth19975/java-web-app-docker.git',branch: 'master'
    }
    
    stage(" Maven Clean Package"){
      sh "clean package"
      
    }
     
     
}
