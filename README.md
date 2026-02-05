Welcome to the ** Application CI/CD Pipeline** project! This repository demonstrates how I designed and implemented a Continuous Integration and Continuous Deployment (CI/CD) pipeline for a Spring Boot application using a variety of modern tools and technologies.

---

## Project Structure

```plaintext
.
├── Argo-CD.png                   # Image demonstrating ArgoCD deployment success
├── Manifests
│   ├── deployment.yml            # Kubernetes deployment manifest
│   └── service.yml               # Kubernetes service manifest
├── SonarQube.png                 # Image demonstrating SonarQube analysis success
└── spring-boot-app
    ├── Dockerfile                # Docker configuration file for containerizing the app
    ├── JenkinsFile               # Jenkins pipeline configuration
    ├── argocd-basic.yml          # Basic ArgoCD configuration file
    ├── pom.xml                   # Maven build configuration
    └── src
        └── main
            ├── java
            │   └── com
            │            StartApplication.java  # Main entry point for the Spring Boot app
            └── resources
                ├── application.properties          # Spring Boot configuration
                ├── static                          # Static assets
                │   ├── css
                │   │   └── main.css
                │   └── js
                │       └── main.js
                └── templates                       # HTML templates
```

---




<img width="2778" height="1070" alt="image" src="https://github.com/user-attachments/assets/b79f00f7-55f0-4cf8-93b4-075816d52d54" />


<img width="2862" height="1240" alt="image" src="https://github.com/user-attachments/assets/1f031adf-1d0d-415e-981e-2db57722521e" />


