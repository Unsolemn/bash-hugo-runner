Must have [docker](https://docs.docker.com/engine/installation/) installed.  
Install runner with:
```
$ git clone git@github.com:Unsolemn/bash-hugo-runner.git
$ cd bash-hugo-runner
$ chmod +x hugoc
$ sudo mv hugoc /usr/bin
```

Run Hugo command:
```
$ hugoc "new site ./my-site"
```

Try to run the following command to add yourself to the group if you're getting "Couldn't connect to Docker daemon.."
```
$ usermod -aG docker ${USER}
```
