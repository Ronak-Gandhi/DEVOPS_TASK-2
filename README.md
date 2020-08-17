# DEVOPS_TASK-2

## TASK OBJECTIVE:-

1. **Create container image that has Jenkins installed using Dockerfile**..
2. **When we launch this image,it  should automatically starts jenkins service in the container**..
3. **Create a job chain of job1,job2,job3 and job4 using Build Pipeline plugin in Jenkins**..
4. **Job 1:- Pull the Github repo automatically when some developers push repo to Github**..
5. **Job 2:- By looking at the code or program file, Jenkins should automatically start the respective language interpreter installed image container to deploy code ( eg. If code is of PHP, then Jenkins should start the container that has PHP already installed )**..
6. **Job 3:- Test your app if it is working or not**..
7. **Job 4:- If app is not working , then send email to developer with error messages**..
8. **Create One extra job, Job 5 for monitor : If container where app is running, fails due to any reson then this job should automatically start the container again**..

### _PREREQUISITE_:-
                    * Docker  * Jenkins  * Github

### Step by Step Process as Follow:-

* _**First of all i created a container image that has jenkins installed using Dockerfile**_ !

![dockerfile](https://user-images.githubusercontent.com/64469896/90393857-2dc4eb00-e0af-11ea-8d80-054824194e3c.png)

* _**After that ,i build that Dockerfile using command <docker build -t jenkins:v1>**..

![build](https://user-images.githubusercontent.com/64469896/90394186-d1ae9680-e0af-11ea-9a21-8ce04050c78b.png)

* _**To lauch Docker inside Docker**_

![docker](https://user-images.githubusercontent.com/64469896/90394718-c740cc80-e0b0-11ea-8b07-8a846415a421.png)

* _**To unlock jenkins**_

![Screenshot (115)](https://user-images.githubusercontent.com/64469896/90395919-f6f0d400-e0b2-11ea-91d3-ad1108f19a25.png)

![Screenshot (116)](https://user-images.githubusercontent.com/64469896/90395752-b09b7500-e0b2-11ea-9ef6-9ce1a78f6635.png)

![Screenshot (117)](https://user-images.githubusercontent.com/64469896/90395762-b6915600-e0b2-11ea-8613-9c2980c8ad58.png)

![Screenshot (118)](https://user-images.githubusercontent.com/64469896/90395769-babd7380-e0b2-11ea-86d7-141b3a91f179.png)

---

>>> `JOB-1`. **Pull the Github repo automatically when some developers push repo to Github**.

* _**Firstly i created job1 in jenkins and then configured it**_












