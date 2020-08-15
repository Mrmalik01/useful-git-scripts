# Useful Git Scripts
You can use these basic scripts to automate your git processes. For example, I can type gcompush to add and commit all the changes I've made, and then push them to my github repository. 

# Instructions (Mac)
1. Open terminal and type the following command
```bash
nano ~/.bash_profile
```
2. Include the following lines anywhere in the file. Note the <location_to_your_script> is the local path to the folder where you cloned or downloaded this repository.
```bash
alias gcompush=<location_to_your_script>/commit_git_push.sh"
alias gcom=<location_to_your_script>/commit_git.sh"
```
3. Exit the file by pressing control+x and respond yes to the confirmation messages.
4. To make these commands available to your terminal, you need to execute the bash_profile file.
```bash
source ~/.bash_profile
```

#HappyCoding
