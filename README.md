# exifsort

Update of the exifsort script written by wb243 optimized for bash on Mac OSX, with a couple of tweaks of my own.


The following script was written in bash on Ubuntu Linux and automatically sorts your images into directories based on the date and time the photo was taken. How does it do this? By making use of the EXIF data your digital camera stores inside the image. The date and time the photo was taken is stored in that EXIF data. When an image doesn't have EXIF data (such as when it was downloaded from the Internet, or taken from a camera that doesn't support adding EXIF data), it will use the files last-modified time.

First, this should be run in the top-most directory of wherever your pictures are stored. If you have pictures/foldername/somepics/ and pictures/anotherfolder/morepics, run it from your pictures/ directory.

There are quite a few opportunities to improve this script -- and some cautionary notes as well -- marked within the script with FIXME tags. I'm already finished sorting my images, but anyone is welcome to contribute suggestions and improvements, which I'll look into incorporating the next time I'm using this.

Usage: Copy the script into a file, editing options where appropriate, and save it. Make it executable and run it from the command line or window, from the directory where your pictures are stored. No command-line arguments. Back up your stuff first :)
