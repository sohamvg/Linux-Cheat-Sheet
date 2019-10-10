# Useful Linux Commands

- To see what's in the directory that you're in, type ```ls```
- To navigate "up" into any higher directory, type ```cd ../```
- To navigate "down" into a directory named foo, type ```cd ./foo```
- To create a file named 'foo', type ```touch foo```
- To create a directory named 'foo', type ```mkdir foo```
- To remove a file named 'foo', type ```rm foo```
- To remove a directory named 'foo', type ```rmdir foo```
- Print working directory, use ```pwd```
- To move a file to a directory, type ```mv filename directory_path```
- Just about any program, when you type it's name and ```-h``` or ```--help``` will print out a usage message.
- if you want to view what's in "foo":
  ```less foo``` or ```emacs foo```
- To open a file or URL in the user's preferred application, use ```xdg-open { file | URL }```
- if you can't find "foo", type:
  ```locate -i foo``` or ```whereis foo```
- If you don't know about "foo", type:
  ```info foo``` or ```man foo```
- To find files in a directory, use ```find {directory} -name {name}```.
  Use ```-type f``` for files and ```-type d``` for directories
- To search inside a file named 'foo', use ```grep "text to be searched" foo```
- To kill a process, use ```kill -15 {pid}``` or ```kill -9 {pid}``` where 'pid' is the process id.
- Use ```!!``` to repeat the last command entered. e.g. ```sudo !!``` is same as ```sudo {previous command}```
- To save the output of a command 'cmd' in terminal in a file named 'foo', use ```cmd > foo```
- To know your username :), type ```whoami```
