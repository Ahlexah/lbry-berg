lbry-berg(*) - Project Gutenberg importer/publisher.
====

# Importing Gutenberg's open files to LBRY's blockchain.

Dependencies upon running: (coming soon)

`The program should look for any publish with the exact naming convention ([title] - [author]:[fileType])
if it exists, it will skip that file.
The process should be indiscriminate, it will download the next file and can only be cancelled through closing
the window or stopping the program.
There is also the option when starting on how many books, to save on either bandwidth, or disk space.`

(Planned) example of use:

    python lbry-berg 0 -e

`Download and publish until the script is cancelled or finished, download only .EPUB files`

    python lbry-berg 500 -a

`Download and publish the next 500 books from the last uploaded file, and do this for every file.`

[n] - being optional on how many to download in this particular run of the script. 0 is continuous.


[-e|-h|-t|-a] - Select ePUB, HTML, TXT or All file types.

Future releases:

    python lbry 500 -a C:\Desktop\lbry-berg

`This is not the highest priority for this initial release - however this will be a feature that can be developed later.`


Disclaimer:

Upon downloading this software, you are accepting that you are liable for whatever happens due to misuse of
of the program. 

There is no tracker on how much storage this will use or has used. If no directory is set, it will be downloaded to the
programs' directory - it is advisable that you ensure this is not your desktop folder. For simplicity.

This program is not affiliated or endorsed with Project Gutenberg, though do be sure to go 
visit them here -> http://www.gutenberg.org/
