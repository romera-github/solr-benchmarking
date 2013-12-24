### [apachesolr-benchs]()

Benchmarking script for running stress-tests to your site

### Requirements

- Python
- ab (Apache Benchmarks)
- gnuplot

### Installation 

    $ wget https://github.com/julianromerajuarez/apachesolr-benchs/archive/master.zip
    $ unzip master.zip
    $ cd apachesolr-benchs
    
    $ python tests.py
    
### Commandline arguments

    tests.py [-v|--vertical] | [-h|--horizontal] | [-c|--cache] | -H "Help"'
    
    -v Vertical Scalability tests
    -h Horizontal scalability tests
    -c Cleans caches
    -H this help

### Features

- Adjustable search words domain
- Graphic results (.jpeg)


### 'License'

This is free and unemcumbered software released into the public domain. For more information, see the accompanying UNLICENSE file.

If you're unfamiliar with public domain, that means it's perfectly fine to start with this skeleton and code away, later relicensing as you see fit.
