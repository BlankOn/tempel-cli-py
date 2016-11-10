### Tempel-CLI uses Python
=========
#### Dependencies:
* python
* requests  
* pyperclip  
  
#### Description:  
tool for paste your snippet to http://tempel.blankon.in as default it will get data from clipboard as text.  
clipboard only available for GUI env, for limited env which not support clipboard you may run `tempel` as follows  
`$ dmesg | tempel bash -s`  
`$ tempel -t 'free text'`  
`$ tempel python -s /path/to/file.py`

#### Usage:

usage: `tempel [-h] [-t TEXT | -s STREAM] [-v] language`

tempel your source code to http://tempel.blankon.in

positional arguments:  
```
  {language}              language of source code; bash c cpp css diff html
                          html+django ini java lua make perl php python rst ruby
                          sql text xml yaml  
```

optional arguments:  
```
  -h, --help            				          show this help message and exit  
  -t TEXT, --text TEXT                    from text  
  -s STREAM, --stream STREAM              from stdin  
  -v, --version         				          show program's version number and exit  
```

#### TODO:  
1. Create pypi package  
2. Create GUI app  

### License MIT
Project License can be found [here](LICENSE.md).
