# Media Player 2 #
This plugin was created, because of lack of possibility to show subtitles in **mediaplayer** on certain images of IPBox sh4 sattelite receivers.

Media Player source is from [Openpli project](http://openpli.org/)

If you are satisfied with this project and you would like to support me please consider donation:

<a href='https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=Y4J4HAWCPTE78&lc=SK&item_name=mediaplayer2%20donation&currency_code=EUR&bn=PP%2dDonationsBF%3abtn_donate_LG%2egif%3aNonHosted'><img src='https://www.paypalobjects.com/en_US/i/btn/btn_donate_LG.gif' border='0'></img></a>

![http://mediaplayer2-for-sh4.googlecode.com/svn/trunk/images/compound_lq.jpg](http://mediaplayer2-for-sh4.googlecode.com/svn/trunk/images/compound_lq.jpg)

---


# Enhanced Movie Center with Subsupport #
Now you can try also EMC with subtitles support instead of MP2

EMC is based on latest source from https://github.com/betonme/e2openplugin-EnhancedMovieCenter + added support for subssupport

```
opkg install http://dl.bintray.com/mx3l/generic/enigma2-plugin-extensions-subssupport_1.4.7_20150108_all.ipk
opkg install http://dl.bintray.com/mx3l/generic/enigma2-plugin-extensions-enhancedmoviecenter_git+888+b459bbc-r1_mips32el.ipk
opkg install http://dl.bintray.com/mx3l/generic/python-xmlrpc_2.7.2-r7.17_mips32el.ipk
```


# Installation #

SSH/Telnet:
```
opkg remove enigma2-plugin-mediaplayer2
opkg remove enigma2-plugin-mediaplayer2ab
opkg update
```

**mp2 v0.57** [download](http://dl.bintray.com/mx3l/generic/enigma2-plugin-extensions-mediaplayer2_0.57_20150204_all.ipk) [changelog](Changelog.md) + **subssupport v1.5.0 beta** [download](http://dl.bintray.com/mx3l/generic/enigma2-plugin-extensions-subssupport_1.5.0_20150304_all.ipk) [changelog](ChangelogSubsSupport.md)

- this version introduces more changes and it's not fully tested therefore is marked as beta. In case there will be no reported issues beta suffix will be removed.

**update1**
  * fixed GS on opening context menu in subtitles downloader
  * fixed flag position in download history
**update2**
  * fixed serbian country code
  * fixed option "Always ask before overwriting existing subtitles"
  * fixed downloading subtitles with diacritics in filename
  * fixed GS when loading subtitles with diacritics in filename
```
opkg install http://dl.bintray.com/mx3l/generic/enigma2-plugin-extensions-subssupport_1.5.0_20150304_all.ipk
opkg install http://dl.bintray.com/mx3l/generic/enigma2-plugin-extensions-mediaplayer2_0.57_20150204_all.ipk
opkg install http://dl.bintray.com/mx3l/generic/python-xmlrpc_2.7.2-r7.17_mips32el.ipk
```

**mp2 v0.57** [download](http://dl.bintray.com/mx3l/generic/enigma2-plugin-extensions-mediaplayer2_0.57_20150204_all.ipk) [changelog](Changelog.md) + **subssupport v1.4.9** [download](http://dl.bintray.com/mx3l/generic/enigma2-plugin-extensions-subssupport_1.4.9_20150204_all.ipk) [changelog](ChangelogSubsSupport.md)
```
opkg install http://dl.bintray.com/mx3l/generic/enigma2-plugin-extensions-subssupport_1.4.9_20150126_all.ipk
opkg install http://dl.bintray.com/mx3l/generic/enigma2-plugin-extensions-mediaplayer2_0.57_20140905_all.ipk
opkg install http://dl.bintray.com/mx3l/generic/python-xmlrpc_2.7.2-r7.17_mips32el.ipk
```


**mp2 v0.56** [download](http://dl.bintray.com/mx3l/generic/enigma2-plugin-extensions-mediaplayer2_0.56_20140905_all.ipk) [changelog](Changelog.md) + **subssupport v1.4.8** [download](http://dl.bintray.com/mx3l/generic/enigma2-plugin-extensions-subssupport_1.4.8_20150126_all.ipk) [changelog](ChangelogSubsSupport.md)
```
opkg install http://dl.bintray.com/mx3l/generic/enigma2-plugin-extensions-subssupport_1.4.8_20150126_all.ipk
opkg install http://dl.bintray.com/mx3l/generic/enigma2-plugin-extensions-mediaplayer2_0.56_20140905_all.ipk
opkg install http://dl.bintray.com/mx3l/generic/python-xmlrpc_2.7.2-r7.17_mips32el.ipk
```

**mp2 v0.56** [download](http://dl.bintray.com/mx3l/generic/enigma2-plugin-extensions-mediaplayer2_0.56_20140905_all.ipk) [changelog](Changelog.md) + **subssupport v1.4.7** [download](http://dl.bintray.com/mx3l/generic/enigma2-plugin-extensions-subssupport_1.4.7_20150108_all.ipk) [changelog](ChangelogSubsSupport.md)
```
opkg install http://dl.bintray.com/mx3l/generic/enigma2-plugin-extensions-subssupport_1.4.7_20150108_all.ipk
opkg install http://dl.bintray.com/mx3l/generic/enigma2-plugin-extensions-mediaplayer2_0.56_20140905_all.ipk
opkg install http://dl.bintray.com/mx3l/generic/python-xmlrpc_2.7.2-r7.17_mips32el.ipk
```

**mp2 v0.56** [download](http://dl.bintray.com/mx3l/generic/enigma2-plugin-extensions-mediaplayer2_0.56_20140905_all.ipk) [changelog](Changelog.md) + **subssupport v1.4.6** [download](http://dl.bintray.com/mx3l/generic/enigma2-plugin-extensions-subssupport_1.4.6_20141117_all.ipk) [changelog](ChangelogSubsSupport.md)
```
opkg install http://dl.bintray.com/mx3l/generic/enigma2-plugin-extensions-subssupport_1.4.6_20141117_all.ipk
opkg install http://dl.bintray.com/mx3l/generic/enigma2-plugin-extensions-mediaplayer2_0.56_20140905_all.ipk
opkg install http://dl.bintray.com/mx3l/generic/python-xmlrpc_2.7.2-r7.17_mips32el.ipk
```


**mp2 v0.56** [download](http://dl.bintray.com/mx3l/generic/enigma2-plugin-extensions-mediaplayer2_0.56_20140905_all.ipk) [changelog](Changelog.md) + **subssupport v1.4.5** [download](http://dl.bintray.com/mx3l/generic/enigma2-plugin-extensions-subssupport_1.4.5_20140911_all.ipk) [changelog](ChangelogSubsSupport.md)
```
opkg install http://dl.bintray.com/mx3l/generic/enigma2-plugin-extensions-subssupport_1.4.5_20140911_all.ipk
opkg install http://dl.bintray.com/mx3l/generic/enigma2-plugin-extensions-mediaplayer2_0.56_20140905_all.ipk
opkg install http://dl.bintray.com/mx3l/generic/python-xmlrpc_2.7.2-r7.17_mips32el.ipk
```

**mp2 v0.56** [download](http://dl.bintray.com/mx3l/generic/enigma2-plugin-extensions-mediaplayer2_0.56_20140905_all.ipk) [changelog](Changelog.md) + **subssupport v1.4.4** [download](http://dl.bintray.com/mx3l/generic/enigma2-plugin-extensions-subssupport_1.4.4_20140910_all.ipk) [changelog](ChangelogSubsSupport.md)
```
opkg install http://dl.bintray.com/mx3l/generic/enigma2-plugin-extensions-subssupport_1.4.4_20140910_all.ipk
opkg install http://dl.bintray.com/mx3l/generic/enigma2-plugin-extensions-mediaplayer2_0.56_20140905_all.ipk
opkg install http://dl.bintray.com/mx3l/generic/python-xmlrpc_2.7.2-r7.17_mips32el.ipk
```

**mp2 v0.56** [download](http://dl.bintray.com/mx3l/generic/enigma2-plugin-extensions-mediaplayer2_0.56_20140905_all.ipk) [changelog](Changelog.md) + **subssupport v1.4.3** [download](http://dl.bintray.com/mx3l/generic/enigma2-plugin-extensions-subssupport_1.4.3_20140904_all.ipk) [changelog](ChangelogSubsSupport.md)
```
opkg install http://dl.bintray.com/mx3l/generic/enigma2-plugin-extensions-subssupport_1.4.3_20140904_all.ipk
opkg install http://dl.bintray.com/mx3l/generic/enigma2-plugin-extensions-mediaplayer2_0.56_20140905_all.ipk
opkg install http://dl.bintray.com/mx3l/generic/python-xmlrpc_2.7.2-r7.17_mips32el.ipk
```



**mp2 v0.55 + subssupport v1.4.2** [download](http://dl.bintray.com/mx3l/generic/enigma2-plugin-extensions-subssupport_1.4.2_20140901_all.ipk) [changelog](ChangelogSubsSupport.md)
```
opkg install http://dl.bintray.com/mx3l/generic/enigma2-plugin-extensions-subssupport_1.4.2_20140901_all.ipk
opkg install http://dl.bintray.com/mx3l/generic/enigma2-plugin-extensions-mediaplayer2_0.55_20140403_all.ipk
opkg install http://dl.bintray.com/mx3l/generic/python-xmlrpc_2.7.2-r7.17_mips32el.ipk
```

[older versions](DownloadsPage.md)

**Restart Enigma2**


---


# Features #

## Media Player ##
  * added possibility to correctly display external subtitles
  * added possibility to show info from file/folder names in [CSFD plugin](http://www.cssf.cz/showthread.php?38339-Plugin-CSFD) (plugin created by petrkl12)
  * added possibility to change aspect ratio
  * added possibility to open extensions menu
  * added possibility to change media framework(eplayer3/gstreamer) when supported by **Mickey GMouse**
  * added cuesheet support for all media types

### Subtitles ###
  * support for SubRIP (.srt) subtitles (supported all tags - Ubuntu font)
  * support for MicroDVD (.sub) subtitles (supported style/color tags - Ubuntu font)
  * correct displaying of special characters (automatic encoding to utf-8)
  * dynamic change of encoding in case special characters are not shown properly
  * auto-load of supported subtitles
  * choosing size, color, font, shadow, background and position of subtitles
  * possibility to choose external subtitles from filelist
  * SD/HD skin compatible

### Subtitles search ###
  * based on [xbmc-subtitles](https://github.com/amet/script.xbmc.subtitles) project(service scripts)
  * Currently supported providers:
    * [Titulkycom](http://www.titulky.com) (login optional)
    * [Edna.cz](http://edna.cz)
    * [SerialZone.cz](http://www.serialzone.cz)
    * [OpenSubtitles](http://opensubtitles.org)
    * [Podnapisi](http://www.podnapisi.net) (login neccesary)
    * [Subscene](http://subscene.com) (needs update)
    * [Itasa](http://www.italiansubs.net) (login neccessary)
    * [SubtitlesGR](http://www.subtitles.gr)

---

# Controls #
  * **ZOOM/5** - change aspect ratio
  * **RIGHT/LEFT** - increase/decrease subtitles delay
  * **INFO(I)** - when pressed in file/play list, it shows info in CSFD plugin
  * **SUBTITLES/TEXT** - shows subtitles menu
  * **TV** - refreshes subtitles position
  * **0** - mark position
  * **NEXT(>)** - go to next mark if available/go to next item in playlist
  * **PREVIOUS(<)** - go to previous mark if available/go to previous item in playlist


---

# Customization #
  * [How to add custom colors](Colors.md)
  * [How to add custom fonts](Fonts.md)

---

# Compatibility with other platforms #
Plugin is platform independent, its completely written in python, so if you have enigma2 satellite receiver, it should work.

Tested on **sh4, mipsel** platform

---

# Localization and Encodings #
**Supported locales:**
  * english
  * slovak
  * czech (by **Vlad Kuzba**)
  * polish (by **Micky GMouse**)

**Supported encodings:**
  * Arabic
  * Greek
  * Central and Eastern European
  * Western European
  * Russian
  * Turkish

---

# Issues #
In case of any problems please fill an issue [here](http://code.google.com/p/mediaplayer2-for-sh4/issues/entry).