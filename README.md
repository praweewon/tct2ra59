# tct2ra59
home work


## How to using GIT

## Step 1
fork repo to your (make via github UI)

## Step 2
clone your repo to your machine
```bash
git clone {your-repo}
#exp => git clone http://github.com/prawee/tct2ra59.git
```

## Step 3 
create remote master repo
```bash
git remote add upstream {destination-url}
#exp => git remote add upstream http://github.com/praweewon/tct2ra59.git
git fetch upstream
```

## Step 4
merge master to your repo
```bash
git merge upstream/master  master
```

## Step 5
update your file

## Step 6
push update file to your repo
```bash
git status
git add {edit-file}
#exp => git add 4820750141.html
git status
git push
```

## Step 7
make pull request (make via github UI)