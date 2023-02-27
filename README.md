# JenkinsHDL2

![image](https://user-images.githubusercontent.com/123473640/221445155-0695511b-4b89-47cf-9827-9caac7188cc0.png)


Step 1: Install Java JRE and Java Version 11/17 (Version 19 is not supported by Jenkins Windows)

![image](https://user-images.githubusercontent.com/123473640/221445215-a3d496fc-c53e-41a2-a9f7-1defa7c78d22.png)

![image](https://user-images.githubusercontent.com/123473640/221445226-6948dc45-eb44-4845-ab89-433c42fcfd14.png)

![image](https://user-images.githubusercontent.com/123473640/221445264-cf7fa7cc-547f-4e0d-8205-b74c26ddcc61.png)

(If there is an older version installed, make sure to uninstall Old version after installing Java)

Proceed to CMD then type java -version

Step 2:
Make new system variables for Java and Java Runtime Environment under Environment Variables.

![image](https://user-images.githubusercontent.com/123473640/221445307-cc442305-685c-4d22-9d74-a74ca2d5f508.png)

Step 3:
Download and Install Docker

![image](https://user-images.githubusercontent.com/123473640/221445336-80b247e3-57e9-4aa2-a173-9e86f34bd7d0.png)

![image](https://user-images.githubusercontent.com/123473640/221445353-88eb3ca3-9c59-4984-9675-a8726073eae7.png)

, Proceed to verify Docker Installation after Restarting your Personal Device.

![image](https://user-images.githubusercontent.com/123473640/221445371-94255f4d-039e-4a70-833b-49f00b2c981a.png)

IF
WSL Service needs to be updated, Open CMD and execute wsl --update
![image](https://user-images.githubusercontent.com/123473640/221445401-4fb7d4f4-de50-4891-af00-eccd6ad3ea90.png)

Step 4 Head into Visual Studio Code and then run the docker-compose.yaml file.

![image](https://user-images.githubusercontent.com/123473640/221445442-b6f9e076-3416-4271-a093-5ff0981d03f8.png)

Step 5 Verify Docker Container

![image](https://user-images.githubusercontent.com/123473640/221445500-a2d3c1ea-7279-4400-9d41-fdb4ce69e6b3.png)

Step 5: Make Jenkins File and Upload to Git Repository

![image](https://user-images.githubusercontent.com/123473640/221445529-3a2dfc01-4f4f-4a4c-8470-00af6288b4cc.png)

Step 6: Open Jenkins using the localhost port indicated on docker-compose.yaml file. (8081 and 9080 in this case.)

![image](https://user-images.githubusercontent.com/123473640/221445570-69a54a83-35e1-4037-8a9d-2804e209257c.png)

Then install recommended Plugins.

Step 7: Verify that Jenkins works as intended.

![image](https://user-images.githubusercontent.com/123473640/221445597-e482ce0b-e784-43db-9511-01dc48404e37.png)

Step 8:
Create Pipeline Jenkins to git repo.

![image](https://user-images.githubusercontent.com/123473640/221445637-ee4e4aae-afad-4abf-a82a-a20ee1c9c891.png)


Step 9:
Click Build Now once Pipeline is connected with Git Repo and verify that it works.

[9080]
![image](https://user-images.githubusercontent.com/123473640/221445744-cbbfddfa-d123-4c40-be2b-5133bb2d9264.png)

[8081]
![image](https://user-images.githubusercontent.com/123473640/221445753-616dd2b8-4f1d-4089-b5a8-b634c7ae43f0.png)


