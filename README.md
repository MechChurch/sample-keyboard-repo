# _sample-keyboard-repo_
_This is MechChurch sample keyboard repository._

_Use this readme for your keyboard pcb sources if they're public available.
Please keep the structure, such as section order, image height, table columns.
Things written in italic are comments, remove them from your readme._

_Examples:_
* _[jiran-keyboard](https://github.com/Ladniy/jiran-keyboard/blob/master/README.md)_


# \<keyboard name>

_(If this is a fork of another keyboard)_ This is a fork of the [__\<Original-keyboard-name>__](link.to.original.keyboard) keyboard

\<optional keyboard description>

<img src="https://i.imgur.com/wWjpgZU.png" data-canonical-src="Photo/Render/Layout" height="300"/>


* __Layout:__ [\<link.to.layout>](http://www.keyboard-layout-editor.com/#/gists/a40840a99de144a561b8c5759ac75534)
* __Hardware Availability:__ \<[link.to.get]()/contact info/open source/not available>
* __Link to firmware:__ [\<link.to.firmware>](https://github.com/qmk/qmk_firmware/tree/master/keyboards/2_milk)
* _(If there is an option to assemble by yourself)_ __Building guide:__  [\<link.to.guide>](place-guide-in-separate-file-in-the-same-repo)
* _(If there is an option to buy parts by yourself)_ __BOM:__

| Name           | Value         | Package           | Count        | Optional  | Comment                           |
| :------------- | ------------: | :---------------- | -----------: | :-------- | :-------------------------------- |
| \<part name>   | \<value>      | \<package type>   | \<count>     |  \<yes/  >| \<[link.to.source]()/function/etc>|
| Pro Micro      | 5V 16MHz      |     17.78x33.02mm | 1            |           | [sparkfun.com](https://www.sparkfun.com/products/12640) |
| Switch         |               | Cherry MX         | 40           |           |                                   |
| Tact button    |               | DIP 3X6X4,3mm     | 1            |     yes   | Need to reset pcb without firmware, you can do this with tweezers |
|            ... |           ... |               ... |         ...  |       ... |                               ... |
