# Spek

Spek is an acoustic spectrum analyser written in C and C++. It uses FFmpeg
libraries for audio decoding and wxWidgets for the GUI.

Spek is available on *BSD, GNU/Linux, Windows and Mac OS X.

Find out more about Spek on its website: <http://spek.cc/>

## Spek 0.8.2.3 - Released 2017-12-08

### New Features And Enhancements

Spek 0.8.2.3 is a fork of the original Spek.

New features since 0.7:

 * Adjustable spectral density range (#4).
 * Switched from GTK+ to wxWidgets for better Windows and OS X integration.
 * Single .exe version for Windows.
 * Added translations in 11 more languages (totalling 19).
 * Open .opus audio files (#39).

Enhancements:

 * Switched to .xz tarballs.
 * Split out libspek and added unit tests.
 * 24-bit APE support (upstream fix).
 * Better toolbar icons on Windows and OS X (#21).
 * Installer options for app shortcuts on Windows (#1).
 * Associate with audio/video files on OS X (#2).
 * Online manual (#24).
 * Use non-deprecated FFmpeg decoding API.
 * Moved downloads to Google Code since GitHub no longer offers downloads (#38).
 * Compatibility with retina-based Macs (#32).

Bugfixes:

 * Fixed crash when the preferences file is not writable.
 * Fixed crash when the home directory is not writable.
 * Fixed duration and rendering for some video files.
 * Fixed compilation with newer FFmpeg and libav versions.
 * Proper handling of Unicode file names under Windows (upstream fix).
 * Don't lock the input file on Windows (#26).
 * Fixed mapping of the spectral density into the palette.
 * Fix magnitude calculation for the first and the last frequency band.
 * Support planar sample formats (#44).

### Sources / Packages

Spek 0.8.2 tarball:

 * <https://github.com/withmorten/spek-alternative/archive/0.8.2.3.tar.gz>

Windows and Mac OS X binaries:

 * <https://github.com/withmorten/spek-alternative/releases/download/0.8.2.3/spek-alternative-0.8.2.3.msi>
 * <https://github.com/withmorten/spek-alternative/releases/download/0.8.2.3/spek-alternative-0.8.2.3.zip>
 * <https://github.com/withmorten/spek-alternative/releases/download/0.8.2.3/spek-alternative-0.8.2.3.dmg>

Unix packages:

 * <https://github.com/withmorten/spek-alternative/blob/master/INSTALL.md#bsd-and-gnulinux>

### Dependencies

 * wxWidgets >= 2.8
 * A recent version of FFmpeg or libav
