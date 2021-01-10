# What is Git?

Git is free and open source version control system.

# What is the difference between Git and Github?

Git is the tool. Github is a website to host your repositories.

# Important Terms
* **Repository**:Project or the folder where your project is kept.

# Git Commands

* **clone**: Bring a repository that is hosted somewhere like Github into a folder on your local machine. (Github üzerinde host edilmiş bir projeyi makinenize çekmenize yarar.)
* **add**:Track your files and changes in Git.
* **commit**:Save your files in Git.(Dosyalarınızı git içerisine kayıt etmenizi sağlar.)
* **push**:Upload git commits to a remote repo,like Github.(Git commitlerimizi uzaktaki repository içine upload etmeyi sağlar.)
* **pull**:Download changes from remote repo to your local machine,the opposite of push.(Uzak repo içerisindeki değişiklikleri makinemize indirmemizi sağlar.)
* **ls** **-la**: This command show a file which is include with hidden folders. (Bu komut gizli dosyalar ile birlikte tüm dosyaların listesini getirir.)
* **git** **status**: This command shows status of your repo. 
* **git** **branch** : This command shows your branch list.
* **git** **checkout** **-b** **nameofyourbranch** :  This command creates a new branch with name.
* **git** **merge**: This command merge your changes from branch to another branch
* **git** **branch** **-d** **nameofyourbranch** : This command deletes your branch
* **git** **commit** **-am** **“message”** : This command is a shortcut add and message together. It only works for modified files.
* **git** **reset** **nameoffile**: This command resets your commits.
* **git** **reset** **HEAD~1** : If you commit wrong things to your repo. You can turn back  one step back.
* **git** **log** : This command shows all commit history in your repo.


## Git Branching

If you are working with team. It’s very useful and necessary. What it does? It  takes copy from master file. It’s same. If you want to add new feature to your project, you can use those mechanism. Your master project doesn’t effect when you change an new feature branch.

## What is Fork?

This button copies the repository to your local machine. If you don’t any access other persons repos. You have to fork and send PR(Pull request).
