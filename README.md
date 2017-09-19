# CSC101

sabrinasvensk@LIBLAB095 MINGW64 ~
$ mkdir cat

sabrinasvensk@LIBLAB095 MINGW64 ~
$ cd cat

sabrinasvensk@LIBLAB095 MINGW64 ~/cat
$ git clone https://github.com/sabrinasvensk/CSC101.git
Cloning into 'CSC101'...
warning: You appear to have cloned an empty repository.

sabrinasvensk@LIBLAB095 MINGW64 ~/cat
$ ls
CSC101/

sabrinasvensk@LIBLAB095 MINGW64 ~/cat
$ cd csc101

sabrinasvensk@LIBLAB095 MINGW64 ~/cat/csc101 (master)
$ echo "sabz" > iphone.txt

sabrinasvensk@LIBLAB095 MINGW64 ~/cat/csc101 (master)
$ ls
iphone.txt

sabrinasvensk@LIBLAB095 MINGW64 ~/cat/csc101 (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        iphone.txt

nothing added to commit but untracked files present (use "git add" to track)

sabrinasvensk@LIBLAB095 MINGW64 ~/cat/csc101 (master)
$ git add
Nothing specified, nothing added.
Maybe you wanted to say 'git add .'?

sabrinasvensk@LIBLAB095 MINGW64 ~/cat/csc101 (master)
$ git add .
warning: LF will be replaced by CRLF in iphone.txt.
The file will have its original line endings in your working directory.

sabrinasvensk@LIBLAB095 MINGW64 ~/cat/csc101 (master)
$ git commit -m "sabz"
[master (root-commit) b7b7882] sabz
 Committer: Sabrina Svensk <sabrinasvensk@uvic.ca>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 1 insertion(+)
 create mode 100644 iphone.txt

sabrinasvensk@LIBLAB095 MINGW64 ~/cat/csc101 (master)
$ git push
Counting objects: 3, done.
Writing objects: 100% (3/3), 217 bytes | 217.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/sabrinasvensk/CSC101.git
 * [new branch]      master -> master
