# Useful Linux Commands

- To see what's in the directory that you're in, type ```ls```
- To navigate "up" into any higher directory, type ```cd ../```
- To navigate "down" into a directory named foo, type ```cd ./foo```
- To create a file named 'foo', type ```touch foo```
- To create a directory named 'foo', type ```mkdir foo```
- To remove a file named 'foo', type ```rm foo```
- To remove a directory named 'foo', type ```rmdir foo```
- To move a file to a directory, type ```mv filename directory_path```
- Just about any program, when you type it's name and ```-h``` or ```--help``` will print out a usage message.
- if you want to view what's in "foo":
  ```less foo``` or ```emacs foo```
- if you can't find "foo", type:
  ```locate -i foo``` or ```whereis foo```
- If you don't know about "foo", type:
  ```info foo``` or ```man foo```
- To search inside a file named 'foo', use ```grep "text to be searched" foo```
- Use ```!!``` to repeat the last command entered.
- To save the output of a command 'cmd' in terminal in a file named 'foo', use ```cmd > foo```
- To know your username, type ```whoami```
