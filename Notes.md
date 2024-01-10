use git clone in IDE to take the repo from github for the first time.
use git pull for any time after that to get the most updated version from the github repo.
git fetch followed by git status will show whether your file is different from the repo in github.
if the file you are on and the github repo have diverged( the same lines are different ), you will need to use git pull to have the differences injected into your file.
from there make the necessary adjustments, then use commands git add . followed by a git commit then a git push. this should solve the diversion and get the github repo and the file on your IDE to be the same.