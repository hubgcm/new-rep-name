# old-rep-name

This is just a test to see the effect of changing repoository names under github.

1. Pushing commits the result to origin master worked even though that generated the following warning:
	- remote: This repository moved. Please use the new location:
	- remote:   https://github.com/hubgcm/new-rep-name.git
2. Pushing to https://github.com/hubgcm/new-rep-name master worked without warning.

In a second test I edited the remote README.md via browser and I made a different set of changes to the local README.md. 

The fecth part worked seamlessly. The pull part stopped with a conflict. I then edited the auto-merge result for README.md, and finally executed:

 1. `git add README.md` 
 2. `git commit README.md`
 3. `git push origin master`


