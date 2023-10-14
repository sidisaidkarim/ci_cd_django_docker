# ci_cd_django_docker
a simple ci/cd pipeline with github actions for testing and deploying a dockerized Django application 

composed of one single job and 2 steps
- step one for executing tests
- step two: checkout code in the server, build container and start docker containers
P.S : if test step fail, deployment will not be executed 
