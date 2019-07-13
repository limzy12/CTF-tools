# CTF Tools
## A collection of useful tool scripts for CTFs

Just clone this to some directory and add the path to the `$PATH` environment variable

1. git-downloader (Adapted from [SLMT](https://github.com/SLMT/ctf-tools/tree/master/git-repository/downloader))

    Used to download the `.git` directory from websites when available.
    Requires:
    * Python 2
    * HTTP Requests Library for Python (`pip install python`)

    ```bash
    ./git-downloader.py [URL]
    ```

    The original seems to be made for Windows OS, I adapted it for UNIX systems.
   
