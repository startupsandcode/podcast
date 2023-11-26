## Episode 2: Github and SSH Keys

To setup an ssh key...

```
ssh-keygen -b 4096 -t rsa 
``````

Then copy the key to your clipboard...

```
pbcopy < ~/.ssh/id_rsa.pub
```

Then paste it into Github under Settings > SSH and GPG Keys > New SSH Key

Now you can use ssh to clone your repos...

```
git clone
```

Popular commands in git

To get the current status of your repo...
```
git status
````
To add all of your files from your current directory down to staging...
```
git add .
```
To commit your changes to your local repo...
```
git commit -m "message"
```
To push your changes to the remote repo...
```
git push
```
To pull changes from the remote repo...
```
git pull
```
To create a new branch...
```
git checkout -b "branch name"
```
To switch to an existing branch...
```
git checkout "branch name"
```
