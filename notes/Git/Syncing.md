# Syncing

## Setting up a new remote repository

```console
git remote add <name> <url>
```
If you want to keep your repository up to date with some kind of upstream project (such as forked repo).
The git remote command is essentially an interface for managing a list of remote entries that are stored in the repository's ./.git/config file.

```console
git remote -v
```
let you list your current remote repos.

-Behind the scenes; in the repository's ./.git/objects directory; Git stores all commits; local and remote.

## Syncing your project with upstream(s)

```console
git fetch <name>
```
If you want to download and review the changes on the upstream before integrating it.

```console
git pull <name>
```
Merges the changes from upstream to your local branch. Usually we add the --rebase to change the merge strategy to a rebase so we can avoid merge conflict.


```console
git push <name>
```
Not much to say about git push. It s the counterpart of fetching. Git won’t let you push when it results in a non-fast-forward merge in the destination repository.
