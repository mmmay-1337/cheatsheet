# May's cheat sheet
May's lazy hacks so she can get by easily. 

# Set up

## git global settings

Some useful default settings for your local git (when committing from your local to your remote)

> setting up global variables
```
# sets up your user name
git config --global user.name "<insert_username>"
# set up your user e-mail address
git config --global user.email "<e-mail_address>"
```
> set up other useful settings
```
# set up default editor to be nano instead of Vim. Sorry, no love for Vim
git config --global core.editor "nano -w"
# other stuff I cannot remember
git config --global http.sslVerify false
git config --global branch.autosetuprebase always
# sets up some colour coding to make it easier on the eyes
git config --global color.ui "auto" # helps with automatically assigning colours
git config --global alias.oll 'log --pretty=format:"%C(yellow)%h\\ %ad%Cred%d\\ %Creset%s%Cblue\\ [%cn]" --decorate --date=short' # one line log
```

> some useful Linux commands
```
ls -ltra # lists all files in the current directory, including hidden files
chmod -R 775 <file or directory> # changes file security mode (775 is for read/write)
export EDITOR=nano # set the editor mode to nano, instead of vim
rm -d <directory name> # removes a directory
rm -rf  .git # removes a git init file
nano <filename>
cat file
mv <directory/filename> <target directory>
```
