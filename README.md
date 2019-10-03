# Git-push-on-Vision-Studio-Code
trying to push a python program from Vision Studio Code to GitHub.

Objective:
----------
- To push a python project into GitHub from Vision studio Code.

Procedural:
-------------
1. Click on Source Control or short cur key: Ctrl + Shift + G:
![SourceControl](https://trello-attachments.s3.amazonaws.com/5d8b054c3d624239e7d6a5dc/5d95a771a8fcdd3a1a7146be/903f7c332ce5d5dfcb4e7a5b808e493f/image.png)

2. Choose the folder need to be push:
![folder](https://trello-attachments.s3.amazonaws.com/5d8b054c3d624239e7d6a5dc/5d95a771a8fcdd3a1a7146be/d0618497cd68e0ef4bde70058d1c298d/image.png) 

3. you will see many file you need to push, to ignore some file being push, go back to Explorer or short cur key: Ctrl + Shift + E:
![Explorer](https://trello-attachments.s3.amazonaws.com/5d8b054c3d624239e7d6a5dc/5d95a771a8fcdd3a1a7146be/7bd9c3b77e8bd29920df80245033d493/image.png)

4. Create .gitignore file:
![gitignore](https://trello-attachments.s3.amazonaws.com/5d8b054c3d624239e7d6a5dc/5d95a771a8fcdd3a1a7146be/5707b533c623075fc6033c20d03c3417/image.png)

5. we are going to ignore virtual environment and .vscode then save it: type this in your gitignore file.
![ignorefile](https://trello-attachments.s3.amazonaws.com/5d8b054c3d624239e7d6a5dc/5d95a771a8fcdd3a1a7146be/d7ff99abcde10334a345fd0da3b772f4/image.png)

6. Now go back source control than stages the gitignore file and your python source file by click the plus sign.
![stage](https://trello-attachments.s3.amazonaws.com/5d8b054c3d624239e7d6a5dc/5d95a771a8fcdd3a1a7146be/3e97d746ebcde673388ace0ede4c0ca5/image.png)

7. To commit it click the right sign than write some message:
![commit](https://trello-attachments.s3.amazonaws.com/5d8b054c3d624239e7d6a5dc/5d95a771a8fcdd3a1a7146be/267ec2306b76056f64b6bd05a7a6930d/image.png)

8. change the terminal to git bash terminal:
![git](https://trello-attachments.s3.amazonaws.com/5d8b054c3d624239e7d6a5dc/5d95a771a8fcdd3a1a7146be/73f7b896b0cad6aea1372f64428c9a16/image.png)

9. Choose git Bash:
![gitBash](https://trello-attachments.s3.amazonaws.com/5d8b054c3d624239e7d6a5dc/5d95a771a8fcdd3a1a7146be/1e5cc1760e471cc5be88a9b48f14db35/image.png)

10. kill the current terminal then open again the terminal *key:Ctrl + '* 
![killT](https://trello-attachments.s3.amazonaws.com/5d8b054c3d624239e7d6a5dc/5d95a771a8fcdd3a1a7146be/325c2d69b7271c1e782c794a073d4582/image.png)

11. your git Bash terminal will look like this:
![gitbashT](https://trello-attachments.s3.amazonaws.com/5d8b054c3d624239e7d6a5dc/5d95a771a8fcdd3a1a7146be/fe31ebfad3aa2ba43e0198ccfa8ba236/image.png)

12. go to your GitHub create a new repository, copy the origin line then type in git bash terminal on Vision Studio Code.
![repository](https://trello-attachments.s3.amazonaws.com/5d8b054c3d624239e7d6a5dc/5d95a771a8fcdd3a1a7146be/949180af27346b4bdc45811bd5b0fe64/image.png)

13. then go to source control check ... sign choose push to then select your link to push then change back your terminal to CMD then kill the git Bash terminal:
![push](https://trello-attachments.s3.amazonaws.com/5d8b054c3d624239e7d6a5dc/5d95a771a8fcdd3a1a7146be/a237a81a70eaefe2a7fe91805cadda80/image.png) 

14. Refresh your Git page to see the pushed program.

References:
-------------
- git push reference by Corey Schafer, [around 48:00 timer video](https://www.youtube.com/watch?v=-nh9rCzPJ20)


