## Game CI/CD DevOps  

Automated build, test, and deployment pipelines for game development.  
This repository includes Jenkins pipelines, Kubernetes configurations, and automated testing scripts.

### Features  
- Continuous Integration with Jenkins & GitHub Actions  
- Automated unit and integration testing  
- Kubernetes-based deployment for game servers  
- Infrastructure as Code (IaC) with Terraform  

### Technologies  
- **Jenkins, GitHub Actions**  
- **Docker, Kubernetes**  
- **Terraform, Ansible**  
- **Python, Bash scripting**  

### Folder Structure  
```
/game-ci-cd-devops
    ├── scripts/         # Automation scripts
    ├── configs/         # CI/CD and deployment configs
    ├── logs/            # Log files from automated builds
    ├── README.md        # Documentation
```

### Setup & Execution  
1. Clone the repository  
   ```bash  
   git clone git@github.com:thomas-sdet-qa-test/game-ci-cd-devops.git  
   ```  
2. Install dependencies  
   ```bash  
   pip install -r requirements.txt  
   ```  
3. Run the CI/CD pipeline locally  
   ```bash  
   bash scripts/run_pipeline.sh  
   ```  

### Contribution  
Pull requests are welcome.
