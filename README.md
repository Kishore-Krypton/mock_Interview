# mock_Interview
- Mock interview video - https://youtu.be/i7YJesoeWFI
- Mock interview Answers - https://youtu.be/5w8qVukxXXY 

GIT
---------------------------------------------------------------------------------------------------------------------------------
1. Why we need git? What makes git unique from other tools like SVN?
2. Let's say i have maven repo cloned on to my local, did some changes and i have build the code now target folder will be generated. So now when i do git operations like git add, git commit or any other git operations target folder should not be considered, how would you achieve the same?
3. difference between git pull and git fetch?
4. How to clone specific branch in git?

Maven
--------------------------------------------------------------------------------------------------------------------------
5. when i issue mvn install what all things happen in background?
6. what are the settings you need to do before running mvn deploy?
7. why maven takes much time for 1st execution and from 2nd execution it will take less time?

Unix and Shell Scripting 
--------------------------------------------------------------------------------------------------------
8. How to get present working folder?
9. How to copy files from local windows machine to cloud based Linux machine?
10. A shell script named test.sh can accept 4 parameters i.e, a,b,c,d. the parameters wont be supplied in order always and number of parameters might also vary( only 2 parameters user might supply sometimes), how to identify position of letter c?

Ansible
---------------------------------------------------------------------------------------------------------------------
11. Why we need ad-hoc ansible commands, scenario where you have used ansible ad-hoc command?
12. When i need detailed logs on executing ansible playbook what option i need to use?
13. what is ansible.cfg file?
14. what are the modules have you worked on? which module will you use for getting the file from node to master?
15. Lets say i have a playbook which has 5 tasks in playbook, first 2 tasks should run on local machine and other 3 tasks should run on node?

Jenkins
-----------------------------------------------------------------------------------------------------------------------
16. How to save only last 5 builds of jenkins job?
17. Have you worked on Jenknsfile? can we use docker container as a node in Jenkinsfile? Who will handle docker container creation and deletion? If i am building a maven project always docker container is fresh instance it will try to download dependency from repository, what measures you will take to reduce build time?
18. Why we need multi branch pipeline?
19. If you forget Jenkins password, how would you login back?

Docker
------------------------------------------------------------------------------------------------------------------------------
20. Any 3 best practices of docker?
21. Difference between docker stop and docker kill?
22. Command to list conatiners which state is exited?
23. command to clean-up docker host ( deleting stopped conatiners, dangling images and unused networks)?
24. What version of docker you have used? Specific reason to use that particular version?
25. Can we have multiple CMD in Dockerfile?
26. Have you worked on docker swarm and docker compose?

Kubernetes
--------------------------------------------------------------------------------------------------------------------------------------
27. Can we have multiple conatiners in a pod? Can we have similar conatiners in a pod? Lets say i have 4 conatiners, one of them has failed how would you check which container has failed?
28. What is liveness and readiness probe? Why we need them?
29. Have you worked on kubernetes monitoring? Which tools you have used?
30. Can we deploy a pod on particular node?

2Nd MOCK INTERVIEW
- Mock interview video - https://youtu.be/lXGAJElFxaA
- Mock interview Answers - https://youtu.be/7WJ31VFk1_Y


GIT
---------------------------------------------------------------------------------------------------------------------------------
1. Lets say your organization has github and bitbucket to store code, you have cloned a repo onto your local and changed directory name. after some days one of your team members asks you to share clone link, how would you provide the same?
2. I have shell script to delete particular dependency ( repo is maven project ). before running the script i need to clone repo to my local, here point to note i should only clone master branch and only last commit ( last commit has all the code ) how would you do this?
3. what is submodule and why we need submodule?
4. Lets say you have changed 5 files a,b,c,d and e in a repo and you did git add ., now all the files are in staging area, now i decided not to commit file d. how would delete it from staging area?

Maven
--------------------------------------------------------------------------------------------------------------------------
5. what is multi module project in maven and what are the setting you want to do in multi module parent and child project? what is dependency management?
6. what is transitive dependency?

Jenkins 
--------------------------------------------------------------------------------------------------------
7. Have you worked on commit based job in jenkins? what settings you need to do in jenkins and github to setup commit based job?
8. you want to create 50 freestyle jobs with same configurations, but only change is job name. how would you achieve the same?
9. How can you copy job from your local jenkins instance to other local jenkins instance?

Unix and Shell scripting 
---------------------------------------------------------------------------------------------------------------------
10. write a script which accepts file or folder, if its folder delete it else print "this is a file"?
11. How to check whether particular port is already in use or not?
12. Logic for checking whether supplied string for a script is palindrome or not? what are all the commands you will use?
13. command to get number of lines in a file?

Ansible
-----------------------------------------------------------------------------------------------------------------------
14. Lets say i have 4 machines consider 1 as ansible master other 3 as nodes, what are the basic setup you need to do for ansible cluster?
15. what are ansible roles? why we need ansible roles? have you worked on ansible galaxy?
16. What are ansible facts?
17. Can we have windows machine as ansible master? as node?have you worked on any windows modules? can you list few?any extra configuration do we need to do?

Docker
------------------------------------------------------------------------------------------------------------------------------
18. Have you worked on multi-stage dockerfile and why we need that?
19. Lets say i have container which is attached with a volume, if container crashes what happens to volume?
20. can you copy a file form local to run container?


Kubernetes
--------------------------------------------------------------------------------------------------------------------------------------
21. what is init container and side-car container?can you give simple scenario where we use these conatiners?
22. which one is default deployment strategy? how it works?
23. command to check the container logs in pod?
24. what are the types of services present in kubernetes?
25. What is the link between pod and service?
