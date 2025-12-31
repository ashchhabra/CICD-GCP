# Implement CI/CD Pipeline on Google Cloud


## Artifact Registry
In this lab you learned about some of the features available in Artifact Registry. You first created repositories for containers and language packages. You then managed container images with Artifact Registry and integrated it with Cloud Code. Finally, you configured Maven to use Artifact Registry for Java dependencies. You now have a solid understanding of features available in Artifact Registry.

https://www.skills.google/course_templates/691/labs/612996

## Cloud Build
In this lab, you create a continuous integration and continuous deployment (CI/CD) pipeline that automatically builds a container image from committed code, stores the image in Artifact Registry, updates a Kubernetes manifest in a Git repository, and deploys the application to Google Kubernetes Engine using that manifest.

<img width="1600" height="434" alt="image" src="https://github.com/user-attachments/assets/1e478fe6-2c0f-4cca-844a-d1d2194c2fb6" />


## Challenge


PRE-WORK - Enable APIs, Create GKE clusters and create a Docker repository in Artifact Registry.
Clone source code, build image, and push to artifact registry.
Create delivery pipeline, targets, and release.
Rebuild and push image, tag with latest.
Create new release with latest version.
Promote the latest release to second cluster.
Rollback changes to second cluster, modify, and re-release.
