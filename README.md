# Personal Git Wiki (commands and notes for personal use)

## Git Fundamentals

### Main or Master
When you create a git repository, the default brands are Main or Master, often the main ones.

### Git states
  - Modified: 
    The file has changed but there is no confirmation to send.
  - Staged:
    The file is modified and marked as ready.
  - Committed:
    The file is saved in the repository.

### .gitignore
The file indicates that git must ignore certain name files to be tracked in the repository.

## Git Commands

- show installed git version
```
git version
```

### Git Config
> add --system, --global or local to a git config command to specify where the configuration will be established
> 
> --system -> The configuration will be applied for the entire systems and repository including all the users
> 
> --global -> The configuration will be applied for the current user"
> 
> --local -> The configuration will be applied for the current repository"

- show current git configuration "add --system, --global or --local for filter the configuration you want to see"
```
git config --list
```

- associate username and email to commits in your device
```
git config  user.name "<your name>"
git config  user.email "<your email>"
```

- set git default editor
```
git config --global core.editor "editor name"
```
### Git Commands

- show a command description
```
git <verb> --help
```
  

