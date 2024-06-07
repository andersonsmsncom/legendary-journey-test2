
C:\Github\andersonsmsncom\legendary-journey-test2>dir
 Volume in drive C has no label.
 Volume Serial Number is D667-E509

 Directory of C:\Github\andersonsmsncom\legendary-journey-test2

06/07/2024  12:32 PM    <DIR>          .
06/07/2024  12:32 PM    <DIR>          ..
06/07/2024  12:32 PM                25 README.md
               1 File(s)             25 bytes
               2 Dir(s)  67,212,443,648 bytes free

C:\Github\andersonsmsncom\legendary-journey-test2>git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

C:\Github\andersonsmsncom\legendary-journey-test2>git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        index.html

nothing added to commit but untracked files present (use "git add" to track)

C:\Github\andersonsmsncom\legendary-journey-test2>git add index.html

C:\Github\andersonsmsncom\legendary-journey-test2>git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   index.html


C:\Github\andersonsmsncom\legendary-journey-test2>git commit -m "index.html"
[main 0ac6033] index.html
 1 file changed, 15 insertions(+)
 create mode 100644 index.html

C:\Github\andersonsmsncom\legendary-journey-test2>git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

C:\Github\andersonsmsncom\legendary-journey-test2>git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 428 bytes | 428.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/andersonsmsncom/legendary-journey-test2
   0fce83d..0ac6033  main -> main

C:\Github\andersonsmsncom\legendary-journey-test2>