## AMD University Program
### Texas A&M Tutorial 2026
### Clone the Repo

##### Copy the below code and run it in a Jupyter notebook in the AUP Learning Cloud 
---
```Python
!pip install pygit2

import pygit2

# URL of the Git repository
repo_url = "https://github.com/andrewgschmidt-amd/tamu-tutorial2026.git"

# Path to clone into
local_path = "./tamu-tutorial2026"

# Clone the repo
repo = pygit2.clone_repository(repo_url, local_path)

print("Repo cloned at:", repo.workdir)
```
---
