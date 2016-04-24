1. CI server creates a docker image with the application
2. publish image
3. deploy image

--
1. Change the code and commit
$ git commit -a -m "changes"
$ git push origin master

2. Docker hub automated build
# wait for the CI to build the image

3. Deploy and run
$ docker pull rcbmor/docker_ci_example
$ docker run rcbmor/docker_ci_example
Java Hello World

