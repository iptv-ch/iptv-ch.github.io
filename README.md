# IPTV m3u Playlists for Swiss Providers

Still waiting iptv stream multicast from upc (now: sunrise upc)

This repository contains M3U playlist files for Swiss IPTV Providers. Here are the files available:

IPTV open channels from Netplus + Swisscom as language french only, english only, german only, italian only.

**https://iptv-ch.github.io/tvopenchfr.m3u**

**https://iptv-ch.github.io/tvopenchen.m3u**

**https://iptv-ch.github.io/tvopenchde.m3u**

**https://iptv-ch.github.io/tvopenchit.m3u**

## CityCable TV Lausanne ftth

**https://iptv-ch.github.io/citycable.m3u**

special thanks to bendreth for their update for community and customers of CityCable TV Lausanne over ftth date 2019-12-18

## Netplus TV HD + SD protocol mpeg dash
**https://iptv-ch.github.io/netplus.mpd**

## Netplus TV HD + SD protocol hls8
**https://iptv-ch.github.io/netplus.m3u8**

Many of the channels available on [Netplus TV partners](https://citycable.ch/tv/chaines-tv/tv-numerique/).<br>
work over stable mobile cellular network and wifi and wired network cooper, hybrid fiber cooper and full fiber wired whatever your internet service provider.
Don't know if geoblocked to Switzerland or not, not tested outside country.
[More information](https://www.regardtv.net/t7600-netplus-iptv-gratuit-free).


## Swisscom TV SD only (codec video h264)

**https://iptv-ch.github.io/swisscom-sd.m3u**

Many of the channels available on [Swisscom TV](https://www.swisscom.ch/en/residential/internet-television-fixednetwork/swisscom-tv.html).<br>
This will only work on your home network if Swisscom is your broadband provider.<br>
This file only lists the SD channels.<br>
EPG information from https://xmltv.ch/ is included.<br>
[More information](https://www.regardtv.net/t6105-flux-iptv-swisscom).


## Swisscom TV HD + SD (codec video h264)

**https://iptv-ch.github.io/swisscom-hd.m3u**

Many of the channels available on [Swisscom TV](https://www.swisscom.ch/en/residential/internet-television-fixednetwork/swisscom-tv.html).<br>
This will only work on your home network if Swisscom is your broadband provider.<br>
This file only lists the HD channels in the case where a channel is available on both HD and non-HD.<br>
EPG information from https://xmltv.ch/ is included.<br>
[More information](https://www.regardtv.net/t6105-flux-iptv-swisscom).

## Swisscom TV UHD only (required codec video h265)

**https://iptv-ch.github.io/swisscom-uhd.m3u**

Many of the channels available on [Swisscom TV](https://www.swisscom.ch/en/residential/internet-television-fixednetwork/swisscom-tv.html).<br>
This will only work on your home network if Swisscom is your broadband provider.<br>
This file only lists the UHD channels.<br>
EPG information from https://xmltv.ch/ is included.<br>
[More information]( https://www.regardtv.net/t6105p325-flux-iptv-swisscom#77698 ).

**https://iptv-ch.github.io/SwisscomIPTVfreeCA.m3u**

Only channels available on [Swisscom blue TV](https://www.swisscom.ch/en/residential/tv/channel-lists.html).<br>
This will only work on your home network if Swisscom is your broadband provider or partner sharing or hosted on Swiscom network ISO layer3<br>
--== Warning: This file list SD/HD/UHD channels by ip order stream free content access module ==--<br>
No TV Guide/Electronic Program Guide, EPG managed by your media center <br>

## Sunrise TV SD/HD (codec video h264) (legacy network trough netstream network ended)

iptv-ch.github.io/sunrise-tv.m3u end of life

Many of the channels available on [Sunrise TV](https://sunrise.ch/tv).<br>
This will only work on your home network if Sunrise/netstream is your broadband provider.<br>
This file lists the Sunrise TV SD/HD channels.<br>
EPG information from https://xmltv.ch/ is included.<br>
[More information](https://www.regardtv.net/t6207-sunrise-iptv-libre-en-clair-non-brouille).

## Sunrise Radio 
(mpeg1-layer2 mpg-audio, datarate=256kbit/s sampling=48khz 32bit)

iptv-ch.github.io/sunrise-radio.m3u (legacy network trough netstream network ended)

Many of the channels available on [Sunrise TV](https://sunrise.ch/tv).<br>
This will only work on your home network if Sunrise/netstream/Swisscom is your broadband provider<br>
This file lists only radio channels.<br>
[More information](https://www.regardtv.net/t6207-sunrise-iptv-libre-en-clair-non-brouille)

## Init7 TV7

### Channel Overview:
https://www.init7.net/de/tv/channels/ 

### Playlists
* **Multicast**: [XSPF (VLC)](https://api.init7.net/tvchannels.xspf) / [M3U](https://api.init7.net/tvchannels.m3u)
* **HLS**: [XSPF (VLC)](https://api.init7.net/tvchannels.xspf?rp=true) / [M3U](https://api.init7.net/tvchannels.m3u?rp=true)

#### SRG channels Full HD?
> SRG only provides its FHD signal in H.265 format. This format requires a lot more hardware resources, so it only works smoothly with the latest Apple TV and >Android TV setup boxes. We generally do not use transcoding, but instead focus on the unencrypted transmission of TV signals with our TV7. That is why we do not broadcast these channels in the TV7 app in FHD but only in 720p format. Instead, we provide the signals in FHD as a separate playlist for consumption on a separate player

Translated with DeepL.com (free version) thanks to FR-95
**Playlist Multicast**
* [SRG Sender FHD MC.m3u](https://www.init7.net/de/support/faq/srg-sender-full-hd/srg-fhd-mc.m3u)
* [SRG Sender FHD MC.xspf](https://www.init7.net/de/support/faq/srg-sender-full-hd/srg-fhd-mc.xspf)

Apple TV (tvOS) Apple TV 4 and 5 and above, olders are not supported.
https://www.init7.net/en/support/faq/tv-apple-geraete/

Android TV Android 7.0 onwards.
https://www.init7.net/en/support/faq/tv-android-geraete/


All channels available (191) if Init7 is your broadband provider<br>
This file lists SD (80) and HD (111) channels. replay (158) <br>
[More information](https://www.init7.net/en/tv/offer/
