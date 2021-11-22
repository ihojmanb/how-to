create a new Rails project
```
rails new sample_app
```

add gems to Gemfile

run `bundle install` to install and include the gems in the specified `Gemfile`
while skiping the nstallation of production gems using the option `--withou production`:
```
bundle install --without production
```

update the gems to with `bundle update` to make sure the versions match:
```
bundle update
```

init git repository 
``` git init
  git add -A
  git commit -m "initialize repository"
```

create a github repository and push your directory to it
```
git remote add origin https://github.com/<username>/sample_app.git
git push -u origin master
```
