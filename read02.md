# Git
![](https://res.cloudinary.com/practicaldev/image/fetch/s--bjpVKHPe--/c_imagga_scale,f_auto,fl_progressive,h_420,q_auto,w_1000/https://dev-to-uploads.s3.amazonaws.com/i/8ogqpfkvqqpyfbs3w6p7.png)
## what is git

### Git allows groups of people to work together, use the same files, and deal with overlap when multiple people edit the same files.

# git add
### Replacing <filename> with the name of the file or path and then the name of the file, if you want to add everything, put a star * instead of the file name:

# git commit
### Replace commit message in parentheses, i.e. git commit -m "modify" Here I'm giving a message that I've modified something.

### For best use, make this message clearly express the changes you've made, the message will appear online, and when you review the changes archive later, it will show you the sequence of operations and show you things if they are well written.


# git push
### where origin is the name of the package folder and master is the name of the branch you want to send changes to -u part of the command is to save the branch on your local machine (origin) and on the internet (master), i.e. you will write this command only once



# git pull
### If there are any conflicts it will then show you file by file, line by line, and you can merge or resolve these conflicts, and then upload your changes using git add and git commit .
### The git pull command loads the modifications made by others to the package and automatically integrates them directly with the existing package locally. If you want to view the modifications before merging, you can use the git fetch command, which loads the modifications from the package on the Internet without merging it with the local package, then to view these modifications use the git checkout command and finally to merge you can use the git merge command