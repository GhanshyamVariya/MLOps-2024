C:\Users\variy\Documents>https://github.com/GhanshyamVariya/MLOps-2024.git
'https:' is not recognized as an internal or external command,
operable program or batch file.

C:\Users\variy\Documents>git clone https://github.com/GhanshyamVariya/MLOps-2024.git
Cloning into 'MLOps-2024'...
warning: You appear to have cloned an empty repository.

C:\Users\variy\Documents>cd MLOps-2024

C:\Users\variy\Documents\MLOps-2024>touch example.txt
'touch' is not recognized as an internal or external command,
operable program or batch file.

C:\Users\variy\Documents\MLOps-2024>ll
'll' is not recognized as an internal or external command,
operable program or batch file.

C:\Users\variy\Documents\MLOps-2024>dir
 Volume in drive C has no label.
 Volume Serial Number is 607A-4111

 Directory of C:\Users\variy\Documents\MLOps-2024

20-10-2024  19:04    <DIR>          .
20-10-2024  19:03    <DIR>          ..
20-10-2024  19:04                24 example.txt
               1 File(s)             24 bytes
               2 Dir(s)  44,089,815,040 bytes free

C:\Users\variy\Documents\MLOps-2024>git add example.txt

C:\Users\variy\Documents\MLOps-2024>git commit -m "Added example.txt"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'variy@gv.(none)')

C:\Users\variy\Documents\MLOps-2024> git config user.email "variya1616@gmail.com"

C:\Users\variy\Documents\MLOps-2024> git config user.name "ghanshyam"

C:\Users\variy\Documents\MLOps-2024>git commit -m "Added example.txt"
[main (root-commit) 47a7d95] Added example.txt
 1 file changed, 1 insertion(+)
 create mode 100644 example.txt

C:\Users\variy\Documents\MLOps-2024>git branch m22ai866

C:\Users\variy\Documents\MLOps-2024>git branch
  m22ai866
* main

C:\Users\variy\Documents\MLOps-2024>git checkout m22ai866
Switched to branch 'm22ai866'

C:\Users\variy\Documents\MLOps-2024>git add example.txt

C:\Users\variy\Documents\MLOps-2024>git commit -m "Modified content in example"
[m22ai866 bf8687e] Modified content in example
 1 file changed, 1 insertion(+), 1 deletion(-)

C:\Users\variy\Documents\MLOps-2024>git checkout master
error: pathspec 'master' did not match any file(s) known to git

C:\Users\variy\Documents\MLOps-2024>git checkout main
Switched to branch 'main'
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

C:\Users\variy\Documents\MLOps-2024>git checkout m22ai866_02
error: pathspec 'm22ai866_02' did not match any file(s) known to git

C:\Users\variy\Documents\MLOps-2024>git branch m22ai866_02

C:\Users\variy\Documents\MLOps-2024>git checkout m22ai866_02
Switched to branch 'm22ai866_02'

C:\Users\variy\Documents\MLOps-2024>git add example.txt

C:\Users\variy\Documents\MLOps-2024>git commit -m "Replaced content in example.txt for M22ai866_02 branch"
[m22ai866_02 5c1965d] Replaced content in example.txt for M22ai866_02 branch
 1 file changed, 1 insertion(+), 1 deletion(-)

C:\Users\variy\Documents\MLOps-2024>git log --graph --oneline
* 5c1965d (HEAD -> m22ai866_02) Replaced content in example.txt for M22ai866_02 branch
* 47a7d95 (main) Added example.txt

C:\Users\variy\Documents\MLOps-2024>git checkout main
Switched to branch 'main'
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

C:\Users\variy\Documents\MLOps-2024>git log --graph --oneline
* bf8687e (HEAD -> m22ai866, origin/m22ai866) Modified content in example
* 47a7d95 Added example.txt

C:\Users\variy\Documents\MLOps-2024>
