# OverTheWire_NATAS
This course is meant to teach people the fundamentals of web security. I'm going to document the following on my run of natas course.
Here is the URL if any one once to test their knowledge :D
URL: https://overthewire.org/wargames/natas/

## NATAS0
Just need to use the "inspect" tool on the website by right clicking on the website
<img width="1910" height="990" alt="Screenshot 2026-01-11 005645" src="https://github.com/user-attachments/assets/890f9232-9f49-4da3-a3db-0e9c1399203f" />
On the right you will have a side bar pop up and see the password to NATAS1

## NATAS1
On this level you can use F12 key and find the website inspector bar and the password will be there like the last one.
<img width="1915" height="948" alt="Screenshot 2026-01-11 010547" src="https://github.com/user-attachments/assets/d91932f2-0331-4e08-8b6a-a0758c47220f" />
Using the F12 opens the Developer tools directly and the right-click is more unreliable and can be disabled.

## NATAS2
In this level you should use F12 again and look for file directory in the html code and you will find the image source so that mean there is a file directory in the website "files/pixel.png" shows that there is the files directory and i simply just jus this on the end of the page "/files/" and we can find the index of files.

<img width="603" height="352" alt="Screenshot 2026-01-11 011806" src="https://github.com/user-attachments/assets/c00104e6-6aca-4f4e-89d4-b7dff04f4f04" />

And by clicking on the users.txt we find the password.

<img width="783" height="791" alt="Screenshot 2026-01-11 011851" src="https://github.com/user-attachments/assets/fdccca9c-b81c-49c4-8528-6c46b852c976" />

## NATAS3
By finding out that not even google can find the vulnerability that means simply scanning the inspection tool wont work so by knowing that there are simple applications that crawl through links on websites. they read HTML, metadata, headers. So website block those application by creating "robots.txt"  text file and it controls the crawlers access. By knowing this and by typing at the end of the url "robots.txt" can find the text file where it shows us the "Disallow" section where they put the blocking text for those applications. 

<img width="794" height="165" alt="Screenshot 2026-01-11 020540" src="https://github.com/user-attachments/assets/eb8b3514-7fcb-428e-9154-fcf228505a3c" />

And we find the index "/s3cr3t/" and it will lead us to the users.txt file where we will find the password for the next level.

<img width="793" height="278" alt="Screenshot 2026-01-11 020917" src="https://github.com/user-attachments/assets/bd5e5079-dc75-4c02-8f8d-e4681718d52f" />
<img width="801" height="171" alt="Screenshot 2026-01-11 020933" src="https://github.com/user-attachments/assets/549d13bf-0f04-4c28-b732-157951410d39" />
