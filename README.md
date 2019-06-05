# 4chan-image-downloader
Bash script that uses wget to follow hyperlinks of a 4chan thread and downloads images to the folder named 4chan.
Note: By default this script will download the images in your current directory.

wget -nd -H -r -l 1 -p -Dis2.4chan.org -A jpg,jpeg,png,gif -e robots=off $1
