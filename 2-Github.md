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
