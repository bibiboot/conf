$ git config credential.helper store
$ git push http://example.com/repo.git
Username: <type your username>
Password: <type your password>

git config --global credential.helper "cache --timeout=7776000"
