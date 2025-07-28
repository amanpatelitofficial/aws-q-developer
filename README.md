### You can also use blog - https://builder.aws.com/content/2zaNNxWt2oth2OU3jruPDXHV0yu/how-to-install-aws-q-developer-cli-on-ubuntu

# aws-q-developer

### Make sure your machine is updated and has Libfuse2 installed

````bash
sudo apt-get update
````

`````bash
sudo apt install libfuse2

`````

### Install the deb file for Amazon Q

````bash
curl --proto '=https' --tlsv1.2 -sSf https://desktop-release.q.us-east-1.amazonaws.com/latest/amazon-q.deb -o amazon-q.deb
````

### Install Amazon Q debian file

````bash
sudo apt install -y ./amazon-q.deb
````

### Login 

````bash
q login
````


### AWS Q CLI with Kubernetes MCP Server

<img width="1752" height="768" alt="image" src="https://github.com/user-attachments/assets/d607c4f3-4004-4481-9a1f-f6d3534b84eb" />


