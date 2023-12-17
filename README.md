# ansible-config-mgt
Ansible Configuration Management
## Introduction
This is a Dockerfile to build a debian based container image running nginx and php-fpm 7.3.x / 7.2.x / 7.1.x / 7.0.x & Composer.

### Versioning
| Docker Tag | GitHub Release | Nginx Version | PHP Version | Debian Version |
|-----|-------|-----|--------|--------|
| latest | master Branch |1.17.2 | 7.3.8 | buster |


## How to use this repository
The build is automatically triggered by a git push to your feature/[branch]

## First clone the repository to your workstation
```
$ git clone https://gitlab.com/propitix/microservices/php-frontend.git
$ cd frontend-propitix
```

Create a feature branch. # Always start with feature/[name of your branch]
```
git branch -b feature/add-css-style-to-about-us-page
```


Update the application code in
```
./html/
```

Then add/commit/push to gitlab

```
git status # to see your changes
```

## First clone the repository to your workstation
```
$ git clone https://gitlab.com/propitix/microservices/php-frontend.git
$ cd frontend-propitix
```

Create a feature branch. # Always start with feature/[name of your branch]
```
git branch -b feature/add-css-style-to-about-us-page
```


Update the application code in
```
./html/
```

Then add/commit/push to gitlab

```
git status # to see your changes
```

## First clone the repository to your workstation
```
$ git clone https://gitlab.com/propitix/microservices/php-frontend.git
$ cd frontend-propitix
```

Create a feature branch. # Always start with feature/[name of your branch]
```
git branch -b feature/add-css-style-to-about-us-page
```


Update the application code in
```
./html/
```

Then add/commit/push to gitlab

```
git status # to see your changes
```

### If both Jenkins jobs have completed one after another - you shall see your files inside /home/ubuntu/ansible-config-artifact directory and it will be updated with every commit to your master branch.

### Now your Jenkins pipeline is more neat and clean.