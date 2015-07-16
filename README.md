passh
=====

Passh is an ssh wrapper for pass password store (https://github.com/zx2c4/password-store)

Requirements:

* pass password store
* sshpass

Instructions:

Copy the passh executable to /usr/bin/ or similar 

Copy the bash completion file password-store-ssh to /usr/share/bash-completion/completions/ or similar

Source the completion file in your .bash_profile or similar

Make sure you have sshpass installed on your machine or it wont work:

For osx install https://raw.github.com/eugeneoden/homebrew/eca9de1/Library/Formula/sshpass.rb



Note:

Password files should be in the following format:

```
$password
login: $user
url: $url
```

![Sean Connery](https://annejan.com/media/passh.jpg)
