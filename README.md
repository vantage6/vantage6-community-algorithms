# vantage6-community-algorithms
A collection of algorithms available to everyone in the vantage6 community

# Add your algorithm
Add the algorithm reposiroty ass submodule:
```
git submodule add <http_repository_url>
```
This will add your algorithm repository as subdirectory. 
It does so by targeting and pinning the latest commit hash.

Add the submodule docs to the overview index page: `index.rst`

# Update your algorithm

In order to get the latest docs you need to update the 
submodule in this repository to the latest commit hash. 

Move into the submodule directory:

```bash
cd <your_submodule>
```

Then pull the lastest (or any other commit, branch, ...):

```bash
git pull
```

Now move to the main repository and commit the update to 
the submodule:

```bash
cd ..
git commit -am "Updated <submodule> to latest"
```

