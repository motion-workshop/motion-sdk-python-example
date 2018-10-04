# Motion SDK Python Example

## Run the example

By default, the example application will read as many samples as possible and
print them to the standard output. The samples are printed as they arrive,
every ~10 milliseconds.

```
python example.py  --help

usage: example.py [-h] [--file FILE] [--frames FRAMES] [--header]
                  [--host HOST] [--port PORT]

optional arguments:
  -h, --help       show this help message and exit
  --file FILE      output file
  --frames FRAMES  read N frames
  --header         show channel names in the first row
  --host HOST      IP address of the Motion Service
  --port PORT      port number of the Motion Service
```
