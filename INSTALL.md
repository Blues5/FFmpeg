#Installing FFmpeg:

1. Type `./configure` to create the configuration. A list of configure
options is printed by running `configure --help`.

    `configure` can be launched from a directory different from the FFmpeg
sources to build the objects out of tree. To do this, use an absolute
path when launching `configure`, e.g. `/ffmpegdir/ffmpeg/configure`.

2. Then type `make` to build FFmpeg. GNU Make 3.81 or later is required.

3. Type `make install` to install all binaries and libraries you built.

NOTICE
------

 - Non system dependencies (e.g. libx264, libvpx) are disabled by default.


If the error “yasm/nasm not found or too old” is displayed after typing the ./configure command. Steps to follow: 
1.  “wget http://www.tortall.net/projects/yasm/releases/yasm-1.3.0.tar.gz”

2. ” tar -xvf yasm-1.3.0.tar.gz” to uncompressed the yasm-1.3.0.tar.gz file

3. “cd yasm-1.3.0”  

4. ‘./configure‘ 

5. ‘make‘ to build FFmpeg.

6. ‘make install‘ to install all binaries and libraries you built.

7. type “yasm –version” to check installation.
