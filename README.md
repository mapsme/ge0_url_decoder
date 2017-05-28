# [MAPS.ME](https://github.com/mapsme/) ge0 url decoder

The PHP code in this repository shows how to decode [MAPS.ME](https://github.com/mapsme/) shared links and extract coordinates from them.

Please check [this repository](https://github.com/georgjaehnig/mapsme-ge0) for the JavaScript example.

@MAPS.ME shares links in two formats:
1. *[http://ge0.me/w4aXJwx_yz/Minsk,_Belarus](http://ge0.me/w4aXJwx_yz/Minsk,_Belarus)* — works on all platforms if you are connected to the Internet, works offline on Android devices only.
2. *[ge0://w4aXJwx_yz/Minsk,_Belarus](ge0://w4aXJwx_yz/Minsk,_Belarus)* — works offline on iOS devices only.

Why coordinates should be encoded at all? The main idea was to save bytes when you share messages via SMS while in roaming (without Internet data plan). SMS messages are costly in roaming and are limited to 140 characters maximum (ASCII) or 70 characters maximum (non-ASCII).

Please [create a new issue](https://github.com/georgjaehnig/mapsme-ge0/issues/new) if you have any questions or suggestions and make a pull-request if you want to contribute or add a link to your version of ge0 decoder.
