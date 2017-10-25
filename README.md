# Google DevFest17 - Gaza
## Deep Learning using Tensorflow - Code Lab Session 

This repo contains a quick overview of applying deep learning using tensorflow. It was created for Gaza DevFest17 as a code lab demonestration.

### Installing and Using Docker

In order to use tensorflow and applying basic deep learning example we are going to use a pre-configured docker instance. This will help us getting a ready to use environment.

##### 1. Installing docker for windows
 
 * To run Docker, your machine must have a 64-bit operating system running Windows 7 or higher.
 * Make sure that [Hyper-V is disabled](https://superuser.com/questions/540055/convenient-way-to-enable-disable-hyper-v-in-windows-8) if it is installed on your pc.
 * If you are using Windows 10 you can directly download docker and install it from [Docker Store](https://store.docker.com/editions/community/docker-ce-desktop-windows).
 * Otherwise, you can download and install [Docker Toolbox](https://docs.docker.com/toolbox/toolbox_install_windows/).
 * After installation is done, open new cmd window and type `docker ps`. If you encountered an error running this command, you should follow [these steps](https://forums.docker.com/t/windows-an-error-occurred-trying-to-connect/4384).
 * Finally, it is worth to spend few minutes on reading [Get Started Tutorial](https://docs.docker.com/get-started/)

##### 2. Installing Tensorflow docker instance

 * Open new cmd window and run `docker image ls`. It should list available docker images.
 * To install a tensorflow docker instance we need first to download it. run `docker pull tensorflow\tensorflow`.
 * After downloading and unpacking is done, you can start new instance by running this command `docker run -it --rm --name="tf" -p 8888:8888 -p 6006:6006 tensorflow/tensorflow`
 *  Copy the link generated and paste it on new browser window. It should point to a jupyter notebook working directory.
 *  If link is not working try to replace `localhost` by `192.168.99.100`
 * Now you are ready to rock :+1:
