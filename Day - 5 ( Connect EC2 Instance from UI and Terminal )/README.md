
# 🔖 AWS CLI ( Full Guide )

## How to connect EC2 instances from UI 


First of all we will login to our AWS console after that we have created a Instances named test , so we will start the Instance after getting the message of success we will connect this instances by clicking on id .


![App Screenshot](https://media.licdn.com/dms/image/D5622AQEwSQrEuI8w2Q/feedshare-shrink_2048_1536/0/1707156416022?e=1709769600&v=beta&t=QTWA-AclBpin54x6Pibn-Huf45LJ_Y6j-molb6BQ1cQ)


After that AWS console will opend , then we can create a file name by the Command ,

 ● touch rishabh ,

when we will do 

● ls 

then we can see that rishabh file is created .

## Now to connect EC2 instances to our terminal 
we will download 

● iTerm  

which is specially for Macos it work as a Terminal ,
so to login in this terminal we have to provide the path of our 

● pem file 

as well as the public Id of our Instances



## Step to connect EC2 is :

![App Screenshot](https://media.licdn.com/dms/image/D5622AQEVx2ZMezj5wA/feedshare-shrink_2048_1536/0/1707156419560?e=1709769600&v=beta&t=tf_4I23nbf7DW76YEFOwDN85-lS-0MaWDChn5nETbSs)



● Open iTerm

● Location of file ( chmod 600 /Users/rishabhraj/Downloads/test111.pem )

● Location of file + public ipv4 address ( ssh -i /Users/rishabhraj/Downloads/test111.pem ubuntu@54.238.134.226 )

Finally we will successfully login to the AWS instance .
