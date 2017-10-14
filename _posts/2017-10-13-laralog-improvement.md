## Set up synchronization by git

#### check-out git version
git --version

#### check-out git configuration
git config --list

#### Set up git synchronization between github,aws and mac
git remote -v
git remote add origin https://github.com/Cassini17/laralog.git
git push --set-upstream origin master

#### synchronize github with aws
git push

#### remove config directory for security reason
git remove -r config/
git commit -m "remove config directory for security reason"
git push


