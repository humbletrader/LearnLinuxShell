# What is pass
pass is the default password manager for Unix environments

# How to use pass
```bash
pass  # shows a listing of the password stoer

pass show notes/mysecret # shows the encripted file notes/mysecret

pass insert work/prod.env # inserts a new password into work/prod.env

pass insert -m work/prod.addresses # inserts multiline note / file into the password store

pass rm work/prod.env # deletes the specified password
  
pass -c Email/zx2c4.com # copies the given password to clipboard


```

[official website](https://www.passwordstore.org/)
