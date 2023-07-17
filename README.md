# capstone-aws
AWS Developer Capstone

Steps taken:
Created repository on GitHub, repository url https://github.com/renatomoroniruz/capstone.git (made repository public).
Cloned Jama’s code to my repository.
Edited faq.html file
Changed line 7, from “Wild Rydes” to “Wild Rides”
Changed line 17, from “Wild Rydes” to “Wild Rides”
Updated the README.md file with changes made to the code.
Cloned my repository to my computer.
Opened files from repository in VS Studio.
Created new Docker file.
Added code from instructions (FROM nginx, etc.) to Docker file.
Ran the Docker desktop app.
Used command docker build -t capstone-container .
Used command docker run -d -p 80:80 capstone-container
Updated my repository

I had a very difficult time trying to understand Docker. I tried for multiple days to figure out how to containerize my application, I believe I was able to do it correctly but I’m not entirely sure.

Used AWS Sandbox environment, created new EC2 instance, named it console-ec2
Once I created the instance, I went to Instances, clicked on my new instance ID, clicked on “Connect” at the top, then on the next screen clicked on “Connect” at the bottom of the screen.
Installed both Docker and Git successfully on EC2 instance using the CLI.
Used the command “git clone” then my repository url. AWS asked for my user ID (email) and Access Token.
Had to go back to GitHub, generated an Access Token, went back to AWS and successfully cloned my code to the EC2 instance.



Findings:

Like I mentioned before, I had a really difficult time trying to figure out how Docker works. GitHub was also new to me and difficult at first, but I was able to understand how things worked fairly quickly. After spending multiple days trying to understand how Docker works, I believe I was able to successfully containerize my application but I’m not entirely sure. I also did not quite understand how to create my Cloudformation stack using the text that was given to use in the instructions.
