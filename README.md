
# Make a new project in Ximera


The workflow is relatively simple. You need a Github account, and a premium Overleaf account. Basically, it consists of the following steps:

1. Create a copy of this repository. You will have to do this again for each of your courses.
2. Your website will be: https://xerxes.ximera.org/github-username-github-repository-name. For example, my website is "https://xerxes.ximera.org/zamorabarser-ximera-simple" becuase zamorabarser is my github username and ximera-simple is the name of the repository.
3. Go to Overleaf - > New Project -> Import from Github -> choose the repository you created in step 1. The first time you do this, you will be prompted to link your Overleaf account with your Github account.
4. In this Overleaf project, go to main.tex and compile. Also in this Overleaf project: "Integrations -> Sync with a Github repository -> Push Overleaf changes to Github -> write a message -> Sync". Wait for the website to update. This may take a few minutes.
5. Go back to Overleaf, and edit the files to customize the content of your course. Initially, you have worksheet1.tex and worksheet2.tex. Ultimately, you create more, and include them at main.tex. After you're done editing the .tex files, repeat step 4.

##

- The original repository I copied is this: https://github.com/ximeraProject/ximeraFirstOverleafSteps.
- The PDF you get from Overleaf is not accessible. A screen reader will fail to correctly read the equations.
- A video essentially containing the instructions I outlined above can be found here: https://mediasite.osu.edu/Mediasite/Play/481087c0da1149479a41866fdb5d9eb71d
-The key files for Ximera deployment are: xmScripts (contains a configfile, and the script 'xmlatex' that Ximera needs), global.css (for look on the web), and .gitignore (update to the most recent version).

## License
The contents of this repository (unless otherwise stated) are in the Public Domain.
