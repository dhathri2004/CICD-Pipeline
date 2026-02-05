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
