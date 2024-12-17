# Jenkins-CICD-Pipeline
Project scope: create a Declarative Jenkinsfile  for a CI pipeline.

Overview of Jenkinsfile:
1. Fetch code from Github.
2. Perform 'Build' with Maven.
3. Perform 'Unit Test' with Maven.
4. perform 'Code Analysis' with SonarQube.
5. Upload the 'Artifact" to NexusOSS Sonatype Repository.
6. Post a notification to a slack channel to confirm if the pipeline ran successfully or failed. 
