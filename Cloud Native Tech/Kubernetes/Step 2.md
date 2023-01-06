## Containers 

## What are containers ? <a href="https://www.ibm.com/in-en/topics/containers">here</a>

- For now consider container as a place in which ur application runs
- Consider you have a basic web application with following files

1. index.html
2. style.css
3. index.js 

![img 3](https://user-images.githubusercontent.com/72307121/210931550-7ba2059f-be05-4d28-919c-54624181b7a3.png)

- Your web application is running inside a container.
- It provide an isolated environment for your application to run.
- But how a container is different from a <a href="https://www.redhat.com/en/topics/virtualization/what-is-a-virtual-machine">Virtual machine </a>

- Lets see the difference between an VM and Container 

![img 4](https://user-images.githubusercontent.com/72307121/210931569-96cae315-e6a4-4c2e-9ddd-31a88e43cadf.png)

- A Virtual Machine has it's own <a href="https://www.techtarget.com/searchdatacenter/definition/kernel">kernel</a> whereas the container shares the kernel of host machine (Machine on which we install container)
- This makes the Container more lighter than the VM 
- Container are more application centric 
- With Container we can deliver high performance and they are easy to scale compare to VM 


## Container Image

- To run our Application in a container we require an container image of that application.
- This means our container is running an image of our application. 
- We will also have practical demo on how to create an image of a simple web application 
- We will be using <a href="https://www.ibm.com/in-en/topics/docker">Docker</a>
- You are requested to do through the <a href="">Docker</a> and then come back to <a href="">Step 3.md file</a>

Note: If you already know what docker is pls continue with setp 3.md file 



