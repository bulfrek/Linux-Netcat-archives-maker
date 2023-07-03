# Running the 2 scripts

To run the server script, run 
```
sh server_script <port>
```

To run the client script, run 

```
sh client_script
```


# Archives modes 

There is 3 commands from the client side 

## list mode 

This mode lists all the archives on the server, to run this mode, enter in the prompt
```
-> vsh -list <address> <port>
```

## browse mode 

This mode allow to naviguate in one of the archive in the server with basic linux commands like pwd, ls, cat, cd but also modify it with commands rm, touch and mkdir

```
-> vsh -browse <address> <port> <archive_name>
```

## create mode 

This mode create an archive of your directory tree in the server with all directories, files and files content in your local directory

```
-> vsh -browse <address> <port> <archive_name>
```


