## SiriKali works on Linux and OSX

SiriKali is a Qt/C++ GUI application that manages <a href="http://ecryptfs.org/">ecryptfs</a>,<a href="https://www.cryfs.org/">cryfs</a>,<a href="http://www.arg0.net/#!encfs/c1awt">encfs</a>,<a href="https://nuetzlich.net/gocryptfs">gocryptfs</a> and <a href="https://github.com/netheril96/securefs">securefs</a> based encrypted folders. These projects are compared <a href="https://nuetzlich.net/gocryptfs/comparison/">here.</a>

<a href="https://github.com/mhogomchungu/ecryptfs-simple">ecryptfs-simple</a> binary application is required to be installed for SiriKali to gain support for ecryptfs volumes.

```cryfs``` binary application is required to be installed for SiriKali to gain support for cryfs volumes.

```gocryptfs``` binary application is required to be installed for SiriKali to gain support for gocryptfs volumes.

```encfs``` binary application is required to be installed for SiriKali to gain support for encfs volumes.

```securefs``` binary application is required to be installed for SiriKali to gain support for securefs volumes.

Encrypted container ```folders``` have an advantage over encrypted container ```files``` like the ones that are created by <a href="http://mhogomchungu.github.io/zuluCrypt/">zuluCrypt</a>,TrueCrypt,VeraCrypt among other projects that use file based encrypted containers.

#### Advantages are:

The encrypted container folder can freely grow and shrink as files are added,removed,grow or shrink. File based encrypted containers are limited to the size of the container and the size is set when the container is created and does not change to reflect the amount of data the container is hosting.

#### Disadvantages are:

The encrypted container folder does not hide the space usage of its contents and an adversary can derive meaning from space usage of the encrypted container folder. File based container hides the space utilization of the volume and the only thing an adversary can see is the fixed size of the container.

More advantages/disadvantages are discussed <a href="https://www.cryfs.org/comparison">here.</a>

## FAQ

Most frequently asked questions are answered <a href="https://github.com/mhogomchungu/SiriKali/wiki/Frequently-Asked-Questions">here.</a>


## Download link

Latest released version is 1.2.4 and it can be downloaded by clicking below link.

<a href="https://github.com/mhogomchungu/sirikali/releases/download/1.2.4/SiriKali-1.2.4.tar.xz">SiriKali-1.2.4.tar.xz</a>

Older versions can be downloaded <a href="https://github.com/mhogomchungu/sirikali/releases">here.</a>

## Binary packages

```Fedora,opensuse,ubuntu and debian``` users can install binary packages by following instructions on <a href="http://software.opensuse.org/download.html?project=home%3Amhogomchungu&package=sirikali">this</a> link.

```Ubuntu 16.04 and 16.10``` packages have a known problem of causing ```synaptic/apt-get``` to complain about usage of SHA1. This is known problem solution and i am waiting for upstream to fix it.

## Screenshots

<a href="http://tinypic.com?ref=v81umb" target="_blank"><img src="http://i64.tinypic.com/v81umb.png" border="0" alt="Image and video hosting by TinyPic"></a>

<a href="http://tinypic.com?ref=2h2hax3" target="_blank"><img src="http://i67.tinypic.com/2h2hax3.png" border="0" alt="Image and video hosting by TinyPic"></a>

<a href="http://tinypic.com?ref=2rojij6" target="_blank"><img src="http://i65.tinypic.com/2rojij6.png" border="0" alt="Image and video hosting by TinyPic"></a>

## Contact info:
```
Name: Francis Banyikwa
email: mhogomchungu@gmail.com

-----BEGIN PGP PUBLIC KEY BLOCK-----
Version: GnuPG v1

mQINBFX2u/UBEADAeacwlUtm2jKJBGyYIWD1h1EpUglAqh8bn7rHmdvs1IZWZEmE
xMoc1jujrGdBx6mguuKWY0VLGzgKhdrVv/rYsVbYlqH3Vz4mamBHOBjIcR317PVI
jV7xdGu76VQkIw1MiJR2TKADFYfe12mEMCTLG6lLAYcxaaIr6jPSZbaP+PUvAhQB
nCHqyA4uSlJnnzyfQuWnTxaedG2Qc0FAUHOnet/7wk3j/TTRXg7mFJVA+EXBwjUy
dJ2V3H/A1UDQ1FRhMw3L2Pjk4/Ast4f1yWmpJwNB8Zk9H8ezTFgnZW72Uo5wIGXN
mkA44skhWCB7cK7kCg/m9MCP6WCSVwqrSps5h1sM2ks32CyRikVXgK0Nbv3bB4+r
PY+ZEVvvts+Wj2KF+94OUUuAyklpb1M51JlScEcouV2oxDB0ijqqCaHugziLCifu
3gjtNacKP3lbBeGh4YjrXmrXpLOYhkrKLWCdv1rt2dcsehNhj7cRMkWoP4h28wbS
MQPgQW25w6QsDGU2uagsNg6It5hJGRuASRyqf/KddmUtSoaxmUwh/4aJo+R9oymQ
wYiHbxgx5OUTeCUv0Qjv2WPPYeYZkwxZbdYWiAPczC+PRXTGa00RgVBxOBMHcJl9
ZcxbC9QgUExPeh8ntK7rG+dpDj3GJ2qk8JUyWm7r2Ar3nCtfYl9LmV0JZQARAQAB
tClGcmFuY2lzIEJhbnlpa3dhIDxtaG9nb21jaHVuZ3VAZ21haWwuY29tPokCOAQT
AQIAIgUCVfa79QIbLwYLCQgHAwIGFQgCCQoLBBYCAwECHgECF4AACgkQPh84BCel
08rtahAAkdotOv7TfLJga/UgIU0AbBVEGgty41JFuILeUjA6TiHUCRDbAW73aiBw
poLe5Z3ZJH4UDEo3SWpilXks7PEBArP75EvG7XabPGQOjQ8ys8AcIpXHSUAvgYD/
OM6Bvcb1gNV81hqNl/Wh3mIvnk0hbyqecrRSm5a2cExJeHAuIdb991CI69oOgDBu
UcoI1FqBbcfuyBRAIl0WkvTcxHLGZLfRd/ZrSWB2FMt+Sj26V1VGGy4Jtb2S47Fw
xMkOOI6R5MH88I/jokNB7kCNUR33uNDVO2ugS4WpLStC0fX7GJY/RUMBH81OXKIy
dlPOjmpU/Ga3UgM6PeJJgrKjKSLuAFFynp0MogNU2o0bFrCR8PI0ZQxbN2h3X6Lb
uRqbqrNkPcBLtlRgp3uzia2/bzCSfZWcgmakW2yBxL6NSVMoDnYq5bXrWZOwE6n5
F2dHj40kZTa7nl4rDaAal791SIFWPKtt4g/CsMn5qxIZ3OQ0JD/ZsdSJ5BehNFdD
tJjPtk8fPdwY2t0JjaQeBYF04DMpT79f3S92fOqLYhIlkpxpdOEtp5hnjDuSHijP
PkkXWcTqDzm/B00EbMV/TL/2bTODHKVX4F2nDJfP9Qycu8wNc4FMS0knG+13sgte
bBIkAJ67KdfI0ex2/6YcrzgLlHSh0YypsvWb1L/usayLF9eRnRi5Ag0EVfa79QEQ
ANef8DH/z21+WdQuBs+/rSWMt3TnQbu+6ClZatBgQNb/Eedo6dY7v81NveLJLB/4
nwC3hJvmQCT/Lo8iiKr5/rq2ETfog8CVNGk4413X5SI5Y+WEMeimuJQOnPNemPEE
+aEyIwSWr2h30XzXJ89Q7chwj4M9minfnCGN8YndLljNWXXTuVCt30MvvdToxcw8
j0Gz+IdcdiTaq8r3S5ADk95hlVOztnL16agcX4YLZi1BpNBIle/ErCaHEmMdOtJl
vjH2I2metqOsd6i3TPgH/S2+U6HDPAL2G9bn68CNTOywwdGlAakNL91AAqxbbEBJ
4iNJ8mSoDrsq0PbFWYMR/BMR5tzRQnocl8jlZGEY0C32uidXzkK/NtrBm47WkedJ
VWyktUO29qB8MX2e1k4aJoZ4ODLZyXLybGVlIbLithonekH6X0H0UOMgHzeW7P6n
xn3gw5QALkmJ4w/C9g1n3EkoCCNbkSBzeE6ZJK535aSl8jQxcN07o8Y9MnB4qvyF
KNsv+82+ScdWOSi8M2KeHqS8t8PSiNgn9ckD5oyV7HoiQo90LrWvpmeBpS+jetAR
luTnwbfy7HwSjLerGPJtSul6q3wD93iLkljy9TOzaj+Wv7jZvhkhXhBWez/+x3Z8
ZFAHllKKJIWcdFr+AVADfmF4EgfllVpY3qTpV8mvXABBABEBAAGJBD4EGAECAAkF
AlX2u/UCGy4CKQkQPh84BCel08rBXSAEGQECAAYFAlX2u/UACgkQX5amBsT3KQV1
Rw//X3gGgdB1TNLuewZ3+y0kDBGSwwH/IxBTSn2IMoiwh+QdRQy/xmayQ4097iAk
3gHFtt49EPAl6ohWkKeGYRfq+3/hg5xKfmzwWMw5yRoHKZ8QhpJ5YpZBCRR0edeu
RNg6Qyx6cgr9mDIvB1k45DMpgNtMFfmSTigVvyTA+mfCGOdz2w9E6PRPTnddR7Gp
6HZvwvHBfshZuPGI1KTchfa07ibHazMpZKlw43V0vz0nz6wjmzjgGWsnbdbIT47+
mvAbFcG9lyDHoXlI02skvuqmImIvoKlRSTYdxsbZHGus0USFJXw0E7JkA42KFf5M
YbuwDD706Zbl672+yXxKkRKmp8c8zePL7PEwgADFHrxlrgaM+Qc8WDTCvy6FA6qd
LAkr9mOztO40sge92C9zmjFjwr3PJ7yxlIZh5wLAQD5tCFahKu1JdQG8DCTK6o6F
+oqTX1v4j2psfAxoQ0b0wkG1T/B8HSmp+oNZh/VRG7mTX6azqaIIPlyjKBN3w5xq
UVYqy2FNOyft5q5iuEeTcw4gxGGffDOieHdzoHcDKpmBzr0iJC52ajKC+PEnNxiA
CcvkpU34nbuPIGEbiL/TdWe88H7g0YJDkBqxmQxN5eJDSavi9MQ0fGP2khD1CDIk
dIC4qOr/GQ2NRqV6m5BsMDMVCX7kqn/xvACDc3XgoMWb+AXsIw/+Ka4NTdof18zP
5iGVMuLG6PBls6VcRNy8Ypr/spNJ1xHWl2f1yNyNX0MeZ8MswbWlE6ESZJ/PcVtD
dxjqZdhm3Z91CVbE9AxNhfSLsb3llLIK75J90Mo2Hx+GfLHCEbajpJfdfRENxIHb
HsE3QHDdDToY9NuCg40yOGdH+H/x+Qun9iuL7MuNZiibZfY1MD0ThlCUBmXDOdLV
l37Na2UvN3tBWsuOCSHqFZeivArfyv1Ez9ziVofmEPVQw3XkMVblxj8FvuIJzs8W
KrvShO4WLi69tTql4fVC9PzfhspgEphSo9wVuXuYj/CsxgF8wn6d27Oox3LR+Grs
w/oimllTMiNc7On5oZluZpHMyxMfgemsOs6XQXknbXA6lTYZo5JF7mUlf+4IoNlw
SdvbY7S+4enblKFmZ/ndsccFUOv3tpGBRhYu+7AszhZngB2P02vXBkdjhatK2FZH
zfdIrSpp0gs1J+xOdF/clQOPFn2oXdTcaBCUCp4d5rDszW4ItRyAgmhvMNbYZvVK
h/19Gl88Dj49v7SS83DqAtURjtXny2lo37uTAAZYgqMVeMff4Y8UJnYSomNwoBqf
pEH3RYyz2GwvaLpUvPUZvVr0x+dFSrHr3ze6v/q48OlmOTCkyukjYqsSOFgMIwBR
i/gJN6mX3AIU7HHEHnP5ty8mwbb8ROc=
=VDxL
-----END PGP PUBLIC KEY BLOCK-----
```

last update: Sun Dec 25 19:38:58 EAT 2016