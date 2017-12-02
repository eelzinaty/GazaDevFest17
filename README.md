# Google DevFest17 - Gaza
## Deep Learning using Tensorflow - Code Lab Session 

This repo contains a quick overview of applying deep learning using tensorflow. It was created for Gaza DevFest17 as a code lab demonestration.

### Installing and Using Docker

In order to use tensorflow and applying basic deep learning example we are going to use a pre-configured docker instance. This will help us getting a ready to use environment.

##### 1. Install docker for windows
 
 * To run Docker, your machine must have a 64-bit operating system running Windows 7 or higher.
 * Make sure that [Hyper-V is disabled](https://superuser.com/questions/540055/convenient-way-to-enable-disable-hyper-v-in-windows-8) if it is installed on your pc.
 * If you are using Windows 10 you can directly download docker and install it from [Docker Store](https://store.docker.com/editions/community/docker-ce-desktop-windows).
 * Otherwise, you can download and install [Docker Toolbox](https://docs.docker.com/toolbox/toolbox_install_windows/).
 * After installation is done, open new cmd window and type `docker ps`. If you encountered an error running this command, you should follow [these steps](https://forums.docker.com/t/windows-an-error-occurred-trying-to-connect/4384).
 * If the above command does not work and you get error message says `Error checking TLS connection:..`, try to run this command `docker-machine restart` then run the above step.
 * Finally, it is worth to spend few minutes on reading [Get Started Tutorial](https://docs.docker.com/get-started/)

##### 2. Run Tensorflow using docker

 * Open new cmd window and run `docker image ls`. It should list available docker images.
 * To install a tensorflow docker image we need first to download it. run `docker pull tensorflow/tensorflow`.
 * After downloading and unpacking is done, you can start new container by running this command `docker run -it --rm --name="tf" -p 8888:8888 -p 6006:6006 tensorflow/tensorflow`
 *  Copy the link generated and paste it on new browser window. It should point to a jupyter notebook working directory.
 *  If link is not working try to replace `localhost` by `192.168.99.100`
 * Now you are ready to rock :+1:

##### 3. Presentation
 * Find My presentation about Neural Network and Deep Learning at [SlideShare](https://www.slideshare.net/secret/1edlP8zEzjPcwv)
 
##### 4. [Introduction to Tensorflow](https://github.com/eelzinaty/GazaDevFest17/blob/master/Tensorflow%20Introduction.ipynb)
 
##### 5. Sample Code Lab
 * Code Sample for Simple Linear Model [Code](https://github.com/eelzinaty/GazaDevFest17/blob/master/Simple%20Linear%20Model.ipynb)
 
 ##### 6. Learning Resources
- Get started with [Tensorflow](https://www.tensorflow.org/)
- Tutorials
	1. TensorFlow Tutorial and Examples for Beginners [repo](https://github.com/aymericdamien/TensorFlow-Examples)
	2. TensorFlow [Tutorials](https://github.com/Hvass-Labs/TensorFlow-Tutorials) with [YouTube Videos](https://www.youtube.com/playlist?list=PL9Hr9sNUjfsmEu1ZniY0XpHSzl5uihcXZ)

- Basic Introduction to Neural Networks and Deep Learning, [Article1](https://www.codeproject.com/Articles/1200392/Neural-Network) [Article2](https://medium.freecodecamp.org/want-to-know-how-deep-learning-works-heres-a-quick-guide-for-everyone-1aedeca88076)
- Machine Learning [course](https://www.coursera.org/learn/machine-learning) tought by the best. 
- Deep Learning [course](https://www.coursera.org/specializations/deep-learning) that covers almost every model of use with good introduction.
