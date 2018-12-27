# pushd / popd / dirs
  pushd - adds the specified path into the stack 
  popd - navigates to the last path in the stack and removes it from there
  dirs - shows the list of paths in the stack
  
# example
let's start from home
```bash
pushd Desktop
pushd books
pushd literature
dirs -v
 0  ~/Desktop/books/literature
 1  ~/Desktop/books
 2  ~/Desktop
 3  ~
popd 
dirs -v
 0  ~/Desktop/books
 1  ~/Desktop
 2  ~
 
```
# working with indexes in the stack
pushd +n - shifts the values in the stack by n and navigates to the new location
pushd -n - shifts the paths in the stack by n ( in reverse order) and navigates tot the new location 
popd +n - removs the nth item in the stack




  
