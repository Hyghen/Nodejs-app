🚀 Successfully Deployed a Node.js Web Application on Kubernetes with Full CI/CD Pipeline!

Over the past couple of days, I worked on a DevOps project that automates the build and deployment process of a Node.js application using:

🔧 Tools Used:
Git | GitHub | GitHub Actions | Docker | DockerHub | Kubernetes | Linux

🛠️ What I Did:
GitHub Setup:

Created a new GitHub repository for my Node.js app.

Cloned the repository to my Linux server and added essential files like index.js, Dockerfile, and Kubernetes manifests (deployment.yaml, service.yaml).

CI/CD with GitHub Actions:

Wrote a GitHub Actions workflow to:

Build a Docker image of my app.

Push it to Docker Hub.

Automatically deploy it to my Kubernetes cluster.

Infrastructure:

Set up two virtual machines (RHEL 9):

One as a Kubernetes master.

The other as a worker node to run the pods.

Configured a self-hosted GitHub Actions runner on the server to deploy the app from GitHub Actions directly to my cluster.

✅ Results:
With every code push, the pipeline automatically builds the image, pushes it to DockerHub, and deploys the latest version to my Kubernetes cluster.

I confirmed deployment using kubectl get pods and kubectl get svc.

🎯 Why This Matters:
This project shows the power of automation in DevOps. By using GitHub Actions, Docker, and Kubernetes, I removed all manual deployment steps. It’s faster, more reliable, and scalable.

#DevOps #GitHubActions #Docker #Kubernetes #CI_CD #Nodejs #Automation #ChitranshJangid #OpenSource #CloudNative
