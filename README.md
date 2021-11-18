
    docker build -t sahasamik/jenkins .

    docker run -p 8080:8080 -p 50000:50000 -v jenkins_home:/var/jenkins_home -v /var/run/docker.sock:/var/run/docker.sock -u root sahasamik/jenkins
