
Build  Machine Images for Jenkins, R1soft and Wordpress using Packer
===========
Packer 


[![CI](https://travis-ci.org/sadsfae/ansible-elk.svg?branch=master)](https://travis-ci.org/sadsfae/ansible-elk)

## What does it do?
Building AWS Mashine image for Jenkins, R1soft and Wordpress 

![packer](/image/uses.png?raw=true "Click Discover")


## Copy and paste commands 
* To run Jenkins:
```
   packer build -var-file vars/jenkins_vars.json  tools/jenkins.json
```   
* To run r1soft:
```
   cd to tools then packer build r1soft.json
```
* To run Wordpress:
```
   packer build -var-file vars/wordpress_vars.json tools/wordpress.json 
```



