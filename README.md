# gh-action-test-rmd
Test Github Action with an Rmarkdown file


## Commit changes

Error:

```
[main 1b722df] ∆'s from github.workflow render-Rmd [skip render-Rmd]
 1 file changed, 28 insertions(+), 21 deletions(-)
remote: fatal error in commit_refs        
To https://github.com/bbest/gh-action-test-rmd
 ! [remote rejected] main -> main (failure)
error: failed to push some refs to 'https://github.com/bbest/gh-action-test-rmd'
No changes to commit
```


* [How do I fix "remote: fatal error in commit_refs" errors trying to push with Git? - Stack Overflow](https://stackoverflow.com/questions/37341960/how-do-i-fix-remote-fatal-error-in-commit-refs-errors-trying-to-push-with-git)

```bash
git fsck; git gc
```
