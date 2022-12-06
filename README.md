# github-runner

Build docker 

docker build --build-arg RUNNER_VERSION=2.292.0 --tag docker-github-runner-lin .


Run the docker please trigger below command 

docker run -e GH_TOKEN='myPatToken' -e GH_OWNER='orgName' -e GH_REPOSITORY='repoName' -d docker-github-runner-lin



Start.sh file is used to add the runner container to github repo or Org
