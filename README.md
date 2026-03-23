
# cache cleaner for macosx files
- i found myself clearing out spotify, telegram, what's app, and other caches
- just make a script and be done with it

### prompt
- let's make scripts to help me clean up some caches on my computern
- here are some of the locations that i want cleaned
```
alias bkups='sudo open ~/Library/Application\ Support/MobileSync/Backup/'
alias qt='sudo open ~/Library/Containers/com.apple.QuickTimePlayerX/Data/Library/Autosave\ Information'
alias sp1='cd /Users/fronk/Library/Caches/com.spotify.client/Data; open .'
alias sp2='cd /Users/fronk/Library/Application\ Support/Spotify/PersistentCache/Storage; open .'
```
- check online to see where other common caches are stored
- make sure we do not delete any files that may disable or cripple the application
- please move then first to the trash, so i can take a look before finally deleting them
- no gui necessary, we can just run this from `.zshrc` as a exported command from the repo
