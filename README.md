#netmocker-as3

Developed by Adobe as part of the OSMF test suite, I've found a lot of use for NetMocker's `MockNetStream` and `MockNetConnection` classes, even outside of tests. For example, using `MockNetStream` enables you to check the activity level of one or more `Microphone`s, otherwise impossible (?) without a live `NetStream`.

This tiny library is for those (if there's anyone else out there, besides myself) who wish to use `MockNetConnection` and/or `MockNetStream` without dependencies (like OSMF), which have been deleted from the original Adobe source, found below:

http://opensource.adobe.com/svn//opensource/osmf/tags/1.5gm/
