# SCM for Device Configurations on Aruba Central
- Jenkins integration with GitHub 
- GitHub Webhooks are sent as a JSON payload to Jenkins, when a change is made to a templates/variables file
- This webhook acts as a trigger for the Jenkins pipeline which is used to build a job
- A Build in Jenkins is nothing but a set of steps that Jenkins is configured to perform
