REPO moved to [Codeberg][4]

media.ccc.de on LG WebOS
========================

This simple app brings you the awesome content of [media.ccc.de][1] onto your LG WebOS device

# Installation with developer mode
1. Download our current [release][2]
2. Install [LG Developer Mode][3] on your PC and TV
3. Run Install 

``` ares-install --device $YOURTV com.srsh.io.media.ccc.de_1.0.0_all.ipk ```

4. Profit

As soon as the app is accepted by the LG content store i'll give an update

# Building 
Adapt the application for your needs and build the `.ipk` file with
```
ares-package ./media.ccc.de/
```

[1]: https://media.ccc.de
[2]: https://github.com/raben2/WebOS_media_ccc_de/releases
[3]: http://webostv.developer.lge.com/develop/app-test/
[4]: https://codeberg.org/srsh/WebOS_media_ccc_de
