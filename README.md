# mozdownload

[mozdownload](https://github.com/mozilla/mozdownload)
is a [python package](http://pypi.python.org/pypi/mozdownload)
which handles downloading of Mozilla applications.

## Command Line Usage

The `mozdownload` command will download the application based on the provided
command line options.

### Examples

Download the latest official Firefox release for your platform:

    mozdownload --version=latest

Download the latest Firefox Aurora build for Windows (32bit):

    mozdownload --type=daily --branch=mozilla-aurora --platform=win32

Download the latest official Thunderbird release for your platform: 

    mozdownload --application=thunderbird --version=latest

Download the latest Earlybird build for Linux (64bit): 

    mozdownload --application=thunderbird --type=daily --branch=comm-aurora --platform=linux64

Download this README file: 

    mozdownload --url=https://raw.github.com/mozilla/mozdownload/master/README.md

Download a file from a URL protected with basic authentication: 

    mozdownload --url=http://example.com/secrets.txt --username=admin --password=password

Run `mozdownload --help` for detailed information on the command line options.
