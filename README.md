
Repo to demonstrate removing orphaned commits. More info [here](https://stackoverflow.com/a/78392060/24712545) and [here](https://stackoverflow.com/a/78392204/24712545).

---------
---------

Compiling
---------

To compile ConnectBot using Ant, you must specify where your Android SDK is via the local.properties file. Insert a line similar to the following with the full path to your SDK:

sdk.dir=/usr/local/android


ProGuard Support
----------------

Download the ProGuard distribution from its website at http://proguard.sourceforge.net/ and place the proguard.jar into the "tools" subdirectory in the ConnectBot root directory.

When running ant to build ConnectBot and engage ProGuard, use:

ant proguard release
