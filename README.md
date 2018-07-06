# InitialCheck

This app allows to add checks to Nextcloud initialization.

# How to use it

1) Place this app in **nextcloud/apps/**;

2) Add a php file with desired check into folder `check`;

3) Enable app in Nextcloud.

There is a sample in file check_sample.php.dist, that checks if browser is Firefox* and denies user to use Nextcloud.
For testing it, rename file as check_sample.php. So, in the next request you will see a message and application will be aborted.

\* _Firefox was chosen as example only because it is free_

## Credits 

InitialCheck by [fgsl](www.fgsl.eti.br)
