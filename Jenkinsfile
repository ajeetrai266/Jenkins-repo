pipeline{
  
  agent any
  stages{
  
    stage{'pod_launch'){
      
      steps{
        
        sh "kubectl apply -f pod-1.yml --kubeconfig /workspace/K8s/minikube-admin.conf"
      }
    }
  }
}
