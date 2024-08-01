 created: 2024-07-25 16:53
[[Git basics]] [[How the Internet works]]

**GIT BASICS**
We learnt about Git and the commands that would help in our development and also make working with others seamless. We also learnt about the .git folder, the .git folder is what tracks everything you do in your repository. 
The commits are stored in subfolders using their first 2 letters to create them
Using "git cat-file <commit SHA>" you can trace back and get the project of a repo using the commit the user made
We also learnt about some basic git commands like the git add <file_name>, git commit -m, git pull, git push, git merge and git rebase. I cleared my confusion i have always had with git rebase when i learnt what it actually does which is changing the base of the commit to the current commit. it will bring all the commits to the branch you are rebasing on.

**HOW THE INTERNET/BROWSER WORKS**

DNS - the Domain Name System. This maps the names of sites to their IP addresses on the servers. 
Browser - This has its own cache and when a request is made it checks it's cache if the client has visited before and if not it checks the OS to see if that site exists, if the OS does not have that data on it, it moves to the Resolver to check if it has that data from there then finally it checks the Authoritative also known as the root server. The root server is the last source and if the root server does not know the the IP of a particular domain then it means that site does not exist.

We got know about ICANN which is the Internet Corporation for Assigned Names and Numbers. This is the body in charge of assigning IP addresses and domain names. They have 13 IP addresses/Servers that handle every IP assignment.

During the class we used the command <dig +noall +answer "domain"> to get the IP address of a website. this truncates all the detailed info that comes when you run dig but to see all that detail you can run the command without "+noall". 

On the side we got to know the difference between a CDN and a Proxy. A CDN caches data so client requests will not have to hit the servers every time but a Proxy will hit the servers on every request.




