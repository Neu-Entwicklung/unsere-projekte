# unsere-projekte

You will soon be able to see the relevant steps to be taken here. :)
Please stay tuned.

# How can I download the project to my computer?

If you have already added SSH code to GitHub, you can download the project using SSH.

    git clone git@github.com:Neu-Entwicklung/unsere-projekte.git

Or alternatively you can download using HTTPS.

    git clone https://github.com/Neu-Entwicklung/unsere-projekte.git

# How do I start working on the project?

- First of all, I create a branch. For this;

        git branch [NAME OR GITHUB_USERNAME]/[NAME_OF_PROJECT]

        e.g.:

        git branch yasir/google
        or
        git branch yykoca/google

- Then I create a folder for myself in the relevant project file and save all the files related to the project in the file.

        mkdir [NAME or GITHUB_USERNAME]
        cd [NAME OF FOLDER]

        e.g.:

        mkdir yasir
        cd yasir

        or 
        
        mkdir yykoca
        cd yykoca

- I commit the steps taken during the project process and upload them to Github.

        git add [FILE_NAME]
        git commit -m [COMMIT_MESSAGE]
        git push

## NOTICE !!! 
** Before I push the files to GitHub, I need to make sure I'm working on the correct branch.