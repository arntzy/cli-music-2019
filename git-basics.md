# Git Basics

```
git clone https://github.com/arntzy/cli-music-2019
```

Each week, create a new branch with {your_name}/week-{week_number} 

```
git checkout -b aaron/week-01
```


When ever you are going to make changes, pull from master first to avoid conflicts

```
git pull origin master
```

Make modifications to `assignments/{your_name}/week-{week_number}`, commit with:

```
git add {changes}
```

```
git commit -m 'add fix wrong note in clarinet'
```

```
git push origin aaron/week-01
```

Submit code through a pull request on github
