# Docker Image: 
`docker pull dasr4/my-jenkins:v2` [added maven, npm as env variable]

# Run:
`docker run -d --name jenkins -p 8080:8080 --env JENKINS_ADMIN_ID=admin --env JENKINS_ADMIN_PASSWORD=XXX -v /opt/jenkins_home:/var/jenkins_home dasr4/my-jenkins:v2`

# To create new image
`bash jenkinsScript`

## Imgage URL:
[Jenkins](https://hub.docker.com/repository/docker/dasr4/my-jenkins)
