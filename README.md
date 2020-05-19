# Refreshable Picture card #


<img src="https://github.com/dimagoltsman/refreshable-picture-card/raw/master/example1.png" height="400">

```
resources:
  - url: /hacsfiles/refreshable-picture-card/refreshable-picture-card.js
    type: module
```


configuration is very easy. you can set a picture from a URL or a picture from an entity attribute

attribute picture example:

```
type: 'custom:refreshable-picture-card'
title: My Mibox
update_interval: 3 # default is 30
entity_picture: media_player.livingroom_mibox
attribute: entity_picture

```

url image exampl:
```
type: 'custom:refreshable-picture-card'
title: My Mibox
update_interval: 3 # default is 30
static_picture: /api/media_player_proxy/media_player.livingroom_mibox?token=11111111111111222222222233333333&cache=1589898123.724253

```



# you are also welcome to contribute new templates. you can add new buttons and remove buttons, just make sure their id matches the id you put in the yaml #

