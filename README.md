# REPO WORK IN PROGRESS

# Adobe Repacker and Installer Script - HyperDrive (HD) for Macintosh (for CC 2015 - present)
A .bat script that compresses unpacked Adobe HyperDrive (HD) assets and installs them.

# CAUTION!
Please, don't use this script for piracy things. I wrote this script for who wants to store HyperDrive (HD)-based Adobe application installers with unpacked assets for various reasons. My reason was maximize deduplication ratings on my Windows Server Storage Spaces storage to store more programs. That's why I wrote this script. I will improve this script day by day.

## What does this script do?
This script compresses all unpacked assets that present on "products" folder to temporary directory set by script, copies HyperDrive installer engine from installation media with unpacked assets excluded via exclude.txt that's generated via script and invokes Set-up.exe on temporary directory set by script to install repacked product.
