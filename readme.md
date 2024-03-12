 docker-compose build
 docker-compose up --scale runner=2 -d
 docker-compose logs -f


  docker-compose up --scale runner=4 -d


ref:

https://baccini-al.medium.com/how-to-containerize-a-github-actions-self-hosted-runner-5994cc08b9fb
https://testdriven.io/blog/github-actions-docker/
