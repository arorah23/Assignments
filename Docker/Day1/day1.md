The Assignment

    Use official shell script to install and configure Docker on your control machine.
    > $curl -fsSL get.docker.com -o get-docker.sh
    > $sudo sh get-docker.sh 
    
    Start Docker service and check status of the same.
    > $sudo service docker start
    > $sudo service docker status
    
    Enable Docker service to start at every machine reboot.
    > $sudo systemctl enable docker
    
    Display Docker version.
    > $docker --version
    
    Configure non root user to run docker commands without sudo.
    > $sudo usermod -aG docker $(whoami)
    
    If you need to add a user to the docker group that you're not logged in as, declare that username explicitly using:

    > $sudo usermod -aG docker username

    Type docker on commandline and read output i.e containing related commands.

    ![](media/.png)

    Display System information using Docker.

    > $docker info 
    
    for this command to work without sudo you have to first logout after adding the user to docker group

    Check whether you can access/download images from DockerHub or not.
    ![](media/.png)
