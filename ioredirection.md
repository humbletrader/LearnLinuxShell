# Input / Output redirection
```bash
cat # cat simple reads stdin from keyboard
1
2
CTRL+D # send the EOF 

cat < listing.txt # standard input from file

time > out_time.txt  # outputs stdout to out_time.txt and overwrites the file if exists

time >> out_time.txt #  appends stdout to the file

ls non_existent_dir 2> errors.txt  # redirects the standard error to errors.txt

ls non_existend_dir 2>> errors.txt

ls &> listing.txt redirects both stdout and stderr to listing.txt

ls &>> listing.txt appends stdout and stderr to listing.txt

```



# Pipes
Sends the stdout of first command to the sdtin of the second
```bash
cat errors.txt | grep Exception
```

# Scripts - redirecting the standard output / error for the whole script
If you are writing a script and want to redirect data streams without appending the redirect operator or every line
```
#!/bin/bash
# Redirect all stdout to output.txt
exec 1> output.txt
# Redirect all stderr to errors.txt
exec 2> errors.txt
```


