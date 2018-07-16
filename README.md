# wsgi-server
Simple python WSGI server


## Usage

    Usage: wsgi_server [options]
    
    Options:
      --version             show program's version number and exit
      -h, --help            show this help message and exit
      -P PORT, --port=PORT
      -D DIRECTORY, --directory=DIRECTORY
      
      
This is just a simple python script you can run to quickly run a wsgi server on your system. You need to specify the port and dircetory containing `index.html` in order to run this script. Your site would also need a file titled `404.html` in the `resources` folder. Otherwise all the `404 NOT FOUND` responses would send `500 INTERNAL SERVER ERROR` instead.

This program is licensed with GPL3
