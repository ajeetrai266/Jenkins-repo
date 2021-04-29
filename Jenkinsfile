pipeline{
  
  agent any
  stages{
  
    stage('pod-launch'){
      
      steps{
        
        sh "sudo kubectl apply -f pod-1.yml --kubeconfig /minikube-admin.conf"
      }
    }
  }
}
