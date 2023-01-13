hello 
PS D:\DESK\demo2> git init
        Initialized empty Git repository in D:/DESK/demo2/.git/

PS D:\DESK\demo2> git commit -m "start from local initializing git "

PS D:\DESK\demo2> git remote add git@github.com:mamme123/demo2.git
        usage: git remote add [<options>] <name> <url>

        -f, --fetch           fetch the remote branches   
        --tags                import all tags and associatll (--no-tags)
        -t, --track <branch>  branch(es) to track
                            master branch
        --mirror[=(push|fetch)]
                            set up remote as a mirror to push to or fetch from
PS D:\DESK\demo2> git remote add origin git@github.comPS D:\DESK\demo2> git remote -v
        origin  git@github.com:mamme123/demo2.git (fetch)     
        origin  git@github.com:mamme123/demo2.git (push)  

PS D:\DESK\demo2> git push origin master

        Enumerating objects: 3, done.
        Counting objects: 100% (3/3), done.
        Writing objects: 100% (3/3), 233 bytes | 116.00 KiB/s, done.
        Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
        To github.com:mamme123/demo2.git
        * [new branch]      master -> master