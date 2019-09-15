# Python proxy checker
## Description
Simple multithreaded proxy checker. Takes several text files as inputs.

## Usage
The script extracts a list of files to be verified named 'proxys.txt' and outputs a list of successful verifications 'checkedproxylist.txt'
The input format is "ip:port" (e.g., "127.0.0.1:8080").

So, to change the input directory and the output file, you have to alter the following lines:
```
filetocheck = 'proxys.txt'
out_filename = 'checkedproxylist.txt'
```


For example:
```
python-proxy-checker
|-- proxy.py
|
|-- README.md
|
|-- input
|   |-- first.txt
|   |-- second.txt
|   |-- third.txt
|
|-- output
    |-- out_filtered.txt
```
