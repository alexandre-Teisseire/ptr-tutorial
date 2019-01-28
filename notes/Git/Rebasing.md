# From merging to rebasing

Until now i never considered rebasing a git repository. In my mind merging was
efficient enough (aka it was ok in most situations) and i didnt have the curiosity
to go any further.

So when i stumble upon this during this course it was kind of brand new.

# Rebasing : first approach

![alt-text](rebaseFailed.PNG ":(" ) ![alt-text](rebaseFailed2.PNG ":(" )

... Was a failure. Then, there is no point in pulling while rebasing. If you want to get
changes from remote, fetch it before rebasing.

# Rebasing : Good practise

```console
git log --oneline --graph --color --decorate --branches
```
(props to Booooby for this one !)

I abused of this one line to assess the situation multiple times. Then, to have a better
understanding of the process of rebasing, i worked exclusively with the interactive mode.
I like how it let you keep control over the workflow.

# Rebasing : EndGame

After several attempts i ended up with what i intended to do with it. Talking about the
problem with several people and working on it erased some of the misconceptions i had about
rebasing and git in general.

That was refreshing :)