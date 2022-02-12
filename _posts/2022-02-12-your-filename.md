---
published: false
---
## Terraform


- What is terraform?

Terraform is an open source software tool that was created by HashiCorp in 2014. The main reason HashiCorp chose to have this be open source as this can help the community by having them be able to give any feedback, improvements and as well customization. The way terraform works is by having it done by infrastructure as code that hashicorp created using their own language called HCL. Using terraform you can be able to write the code to modify cloud api to make changes to the configuration files. Terraform plan allows you to have a check before any changes are actually made to the infrastructure. Lastly if the code meets your expectations you can then apply the changes to a cloud service provider with one example being Amazon Web service (AWS). Terraform Can help manage components like storage and networking along with more advanced high level functions such as DNS entries and SaaS features. 


- What are the benefits? 
By using Terraform for your cloud service provider can be very beneficial as terraform can help reduce any human error by being able to automate the process.  Of course as mentioned terraform can be used on many cloud providers with the company mentioning it can be used on over 300 different public clouds and services.  Some of the big names are AWS, Azure, Google cloud, Kubernetes, GIthub and Helm. By being an open source tool the terraform community can help provide any assistance needed. 


## Install method for AWS EC2 instance Ubuntu
- step one allow the system to trust hashicorp key

~~~

curl -fsSL https://apt.releases.hashicorp.com/gpg | sudo apt-key add -

~~~

- step two add hashicorp repository

~~~

sudo apt-add-repository "deb [arch=$(dpkg --print-architecture)] https://apt.releases.hashicorp.com $(lsb_release -cs) main"

~~~

- step three install terraform

~~~

sudo apt install terraform

~~~## A New Post

Enter text in [Markdown](http://daringfireball.net/projects/markdown/). Use the toolbar above, or click the **?** button for formatting help.
