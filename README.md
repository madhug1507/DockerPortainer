# DockerPortainer

**_Portainer_** is a lightweight management UI which allows you to **easily** manage your different Docker environments (Docker hosts or Swarm clusters).

**_Portainer_** is meant to be as **simple** to deploy as it is to use. It consists of a single container that can run on any Docker engine (can be deployed as Linux container or a Windows native container).

**_Portainer_** allows you to manage your Docker containers, images, volumes, networks and more ! It is compatible with the *standalone Docker* engine and with *Docker Swarm mode*.

docker pull portainer/portainer and then run the below command

docker run -d -p 9000:9000 --name portainer --restart always -v /var/run/docker.sock:/var/run/docker.sock -v portainer_data:/data portainer/portainer

Goto Browser and access it by http://localhost:9000 and then create username
 
 ![portainer](https://user-images.githubusercontent.com/13721528/40578537-882b6462-610d-11e8-9c43-0c885f83293a.PNG)
 
Dashboard looks like below

![image](https://user-images.githubusercontent.com/13721528/40578595-53e64bc6-610e-11e8-926d-d90613ce0afa.png)

  
  
