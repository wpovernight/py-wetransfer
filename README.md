py-wetransfer
=============

Python 3 script for downloading [WeTransfer](https://www.wetransfer.com/) files from the command line

Usage
=====

You should have a WeTransfer address

https://www.wetransfer.com/downloads/XXXXXXXXXX/YYYYYYYYY/ZZZZZZZZ 

or a short-form one

https://we.tl/XXXXXXXXXXXX

Execute:

    python3 wetransfer.py https://we.tl/XXXXXXXXXXXX

and the file will be downloaded.

Requirements
=============

Python 3.8+

[Requests](https://docs.python-requests.org/en/latest/)

[BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)

[pyjson5](https://github.com/dpranke/pyjson5)

    pip install requests beautifulsoup4 json5
    

September 2021 notes
====================

I have updated this script to work with the latest WeTransfer links (as of September 2021).  Many thanks to Alejandro Alonso, Marcos Besteiro López and Gary Watson for starting this off.

I have tested it on macOS with Python 3.9
