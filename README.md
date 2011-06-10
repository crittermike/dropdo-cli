## A command line file uploader for Dropdo

### Installation

- Download the "dropdo" script
- Make it executable:

    `$ chmod o+x ./dropdo`
- Move the script to /usr/local/bin/

### Usage

    $ dropdo yourfile.txt

### Result

The link to the file will be output to stdout.

Also, if you have xclip installed, it will copy the link to your clipboard.

### Notes

At this point, the script uploads files anonymously, so any files you upload won't be tied to your Dropdo.com account, which means you can't easily delete them.
