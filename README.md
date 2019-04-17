# Better git log

Put the `alias` section at the bottom of your `~/.gitconfig` to get 
better git log graphs.  

Usage: `git lg`

Result:
```
git lg
* 2203495 - (53 minutes ago) Missed a word - ahester (HEAD, origin/dev) 
* 28de101 - (57 minutes ago) Add Quick Start guide to README 
| *   494d24d - (20 hours ago) Merge pull request #62 from PR/dev
| |\  
| |/  
|/|   
* |   84d0a85 - (20 hours ago) Merge pull request #63 from PR/branch
|\ \  
| * | a82cdfa - (5 days ago) update version flag to 1.1 
* | |   ad622e6 - (5 days ago) Merge pull request #55 from PR/branch
|\ \ \  
| * | | 7c96e46 - (5 days ago) reduce mass of blank lines 
| * | |   361246b - (5 days ago) Merge pull request #60 from PR/branch
| |\ \ \  
| | * | | 72832e2 - (5 days ago) add module table to detailed report  
| |/ / /  

```

`git lg2` is a more spread out version of `git lg`.

`git adog` is a novelty.
