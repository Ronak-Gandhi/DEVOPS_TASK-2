# DEVOPS_TASK-2

## TASK OBJECTIVE:-

1. **Create container image that has Jenkins installed using Dockerfile**..
2. **When we launch this image,it  should automatically starts jenkins service in the container..
3. **Create a job chain of job1,job2,job3 and job4 using Build Pipeline plugin in Jenkins..
4. **Job 1:- Pull the Github repo automatically when some developers push repo to Github..
5. **Job 2:- By looking at the code or program file, Jenkins should automatically start the respective language interpreter installed image container to deploy code ( eg. If code is of PHP, then Jenkins should start the container that has PHP already installed )..
6. **Job 3:- Test your app if it is working or not..
7. **Job 4:- If app is not working , then send email to developer with error messages..
8. **Create One extra job, Job 5 for monitor : If container where app is running, fails due to any reson then this job should automatically start the container again..

### _PREREQUISITE_:-
                    * Docker  * Jenkins  * Github

### Step by Step Process as Follow:-

* _**First of all i created a container image that has jenkins installed using Dockerfile !

