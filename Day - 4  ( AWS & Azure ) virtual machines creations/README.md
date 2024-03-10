
# 🔖 Creation of virtual Machine in AWS


Amazon Elastic Compute Cloud (EC2) is the Amazon Web Service you use to create and run virtual machines in the cloud (we call these virtual machines 'instances').

Amazon Elastic Compute Cloud (Amazon EC2) is a web service that provides secure, resizable compute capacity in the cloud. It is designed to make web-scale cloud computing easier for developers. Amazon EC2's simple web service interface allows you to obtain and configure capacity with minimal friction.

# 📕 How to Launch the instance :


To create a new virtual machine instance on AWS, follow these steps:

◦ Open the Amazon EC2 console.

◦ From the EC2 console dashboard, select Launch Instance.

◦ Provide a name for the VM instance. For this tutorial, we’ll use the name “test”.

◦ Under the section titled Application and OS Images, click on the ubuntu button under the Quick Start tab. Under the Amazon Machine Image (AMI) section there should be a drop-down menu listing all of the available machine images. Select the AMI for ubuntu Server 22.04 Base.





![App Screenshot](https://developer.rhino3d.com/images/AWS_Setup_11.png)



![App Screenshot](https://developer.rhino3d.com/images/AWS_Setup_12.png)

◦ n the Instance Type section, select the t2.micro instance type (default) or a larger instance type if needed. Note: the t2.micro instance type is elegible for the free tier. In regions where t2.micro is unavailable, you can use a t3.micro* instance under the free tier.

◦ In the Key Pair (login) section, select the key pair name that you created in step 2 of the prerequisite section prerequisite section from the drop-down list.


![App Screenshot](https://developer.rhino3d.com/images/AWS_Setup_13.png)

◦ At last we will get success message .

![App Screenshot](https://developer.rhino3d.com/images/AWS_Setup_15.png)

