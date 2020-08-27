# CKAD-free-course
## Configure Minikube K8S environment 
   1. Install and Set Up kubectl
      ## Windows
      1. Download from below location and add the kubectl.exe to PATH variable.<br/>
      https://storage.googleapis.com/kubernetes-release/release/v1.19.0/bin/windows/amd64/kubectl.exe
      2. Test to ensure the version you installed is up-to-date
        <br/> kubectl version --client
       ## MAC
      1. Download the latest release
      <br/>curl -LO "https://storage.googleapis.com/kubernetes-release/release/$(curl -s https://storage.googleapis.com/kubernetes-release/release/stable.txt)/bin/darwin/amd64/kubectl"
      2. Make the kubectl binary executable.
      <br/>chmod +x ./kubectl
      3. Move the binary in to your PATH.
      <br/>sudo mv ./kubectl /usr/local/bin/kubectl
      4. Test to ensure the version you installed is up-to-date
        <br/> kubectl version --client
      
