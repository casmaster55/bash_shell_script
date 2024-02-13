# bash_shell_script
# what is a $? in bash shell script?
In Bash, $? is a special variable that tells you whether the last command you ran was successful 
if [ $? -eq 0 ]; then
    echo "Command succeeded"
else
    echo "Command failed"
fi
