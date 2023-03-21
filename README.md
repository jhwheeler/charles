# Charles - Code Execution Engine for CodeGenie
Charles is a simple yet powerful code execution engine, designed as an initial component of the CodeGenie project. It supports executing JavaScript, Python, and shell scripts from the command line with ease.

## Getting Started
Follow these steps to use Charles to execute your scripts:

1. Set up Charles
Clone the Charles repository or download the charles script file.

Make the script executable by running:

```
chmod +x charles
```
Create a symlink to the charles script in a directory listed in your PATH environment variable, such as /usr/local/bin:

```
sudo ln -s "$(pwd)/charles" /usr/local/bin/charles
```

2. Running Charles
To run Charles with your desired script, use the following command:

```
charles /path/to/your/script.ext
```
(Replace `/path/to/your/script.ext` with the actual path to your script file. The file extension (.js, .py, or .sh) determines the language that Charles will use to execute the script.

For example, if you have a Python script called hello_world.py, you would run:

```
charles hello_world.py
```

Charles will execute the script and display the output in the terminal.

That's it! You're now ready to use Charles as a versatile code execution engine for CodeGenie.
