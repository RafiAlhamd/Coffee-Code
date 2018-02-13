# Coffee-Code

## Create a portfolio website in 3 steps

### Step 1: Sign up for IBM Cloud and download CLI

Go to http://ibm.biz/astrolabs, click 'Create a free account' 

![1](images/1.PNG)

and fill in email, name, password, etc

![2](images/2.PNG)

Download the IBM Cloud CLI from https://clis.ng.bluemix.net/

### Step 2: Download and modify application files

Download the application files and save them from: 

Open the 'Manifest.yml' file and edit the name of your app.
Make sure that it is something uniques as this will be your host name too.

IMAGE



### Step 3: Deploy using CLI

If you're running on Windows, open up command line(cmd)
If you're running on Mac, open up the terminal

Navigate to the folder with the application files using 'cd' followed by the folder path 

IMAGE

Log into your IBM Cloud account through the CLI with the following command: 

``` bx login -a https://api.eu-gb.bluemix.net -u [youremail] -p [yourpassword] ```

Select the organization and space in which you would create the app.

The organizatoin name is the same as your email, the space is usually called 'dev'

``` bx target -o [organization_name] -s [space_name] ```







