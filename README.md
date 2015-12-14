# Devel::NYTProf

Devel::NYTProf is a powerful feature-rich perl source code profiler.

[![Build Status](https://secure.travis-ci.org/timbunce/devel-nytprof.png)](http://travis-ci.org/timbunce/devel-nytprof)

For more information see:

    https://www.youtube.com/watch?v=T7EK6RZAnEA
    http://www.slideshare.net/Tim.Bunce/nyt-prof-201406key
    http://blog.timbunce.org/tag/nytprof/

## DOWNLOAD AND INSTALLATION

Download a release from CPAN using your favorite tool, such as cpanm.  Or else
from https://metacpan.org/release/Devel-NYTProf and then unpack the tar.gz file.

You're most welcome to contribute, in which case cloning or forking the git
repo is a good place to start.

To build and install, just incant the typical mantra:

     perl Makefile.PL
     make
     make test
     make install

## DOWNLOAD & INSTALLATION FOR DUMMIES

Install cpan: 
    
    # Redhat/CentOs/Fedora
    sudo yum install cpan
    
    # Ubuntu/Mint
    sudo apt-get install build-essential # Guessing here

Install devel-nytprof and its dependencies:

    sudo perl -MCPAN -e shell # Invoking with a non-root  user didn't work
    install Devel::NYTProf

