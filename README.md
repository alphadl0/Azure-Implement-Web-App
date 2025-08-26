# Azure-Implement-Web-App
This lab showcases a full-cycle deployment scenario using Azure App Services, emphasizing scalability, zero-downtime deployment, and CI/CD integration
### Architecture
<img width="3193" height="4156" alt="az104-rg9" src="https://github.com/user-attachments/assets/4c0106c6-6aef-41a1-8d20-4443f8b9356f" />

### Depployment slot
- Slot Name: staging
- Purpose: Pre-production testing
- Outcome: Isolated staging environment with unique URL
<img width="1605" height="401" alt="image" src="https://github.com/user-attachments/assets/9ded5859-48ed-4fca-8970-668aa5a0f3aa" />

### Deployment Settings
- Source: External GitHub repo
- Repo: https://github.com/Azure-Samples/php-docs-hello-world
- Branch: master
<img width="632" height="344" alt="image" src="https://github.com/user-attachments/assets/375eb6b4-1bcd-4c62-b1d6-2d923d8b1f92" />


### Swap Deployment Slots
- Action: Swapped staging with production
- Outcome: Hello World app live in production with zero downtime
<img width="539" height="207" alt="image" src="https://github.com/user-attachments/assets/504c72bf-d46f-47e5-baa0-737fb078be4f" />

### Autoscaling
- Scaling Mode: Automatic
- Max Burst: 2 instances

<img width="835" height="435" alt="image" src="https://github.com/user-attachments/assets/e9203c29-8e94-460a-b0c0-71d227d004df" />

### Load Test
- Load-tested app with dynamic scaling based on traffic
<img width="1626" height="713" alt="image" src="https://github.com/user-attachments/assets/285139c8-4c74-4bd6-a926-d6c80a8633bd" />
