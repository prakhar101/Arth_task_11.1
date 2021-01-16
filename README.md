# Arth_task_11.1
Set-up the hadoop cluster in the AWS cloud (ec2) using ansible as automation tool for configuration management and provisioning..
<h2> Since I have made the use of the dynamic inventory so dynamic inventory file should be present at the controller node</h2>
<p> master.yml should be run at first followed by the slave.yml</p>
<p>before running master.yml and slave.yml make sure that u have set the values of variables either in vars.yml or in shell environment variables<br>export AWS_DEFAULT_REGION='ap-south-1(This is example you can decide your own)'<br> export AWS_ACCESS_KEY_ID='access key id of your aws account'<br> export AWS_SECRET_ACCESS_KEY='secret-key'
