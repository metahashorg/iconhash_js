# iconhash_js
This repository contains JavaScript library which allows to generate personal identification icon for any Metahash address. Even if addresses seem to be very similar and are only slightly different, they will have totally different icon representations. This makes addresses more recognisable and convenient for users of the Metahash network.

## Usage

```shell
<script src="blockies.js"></script>
<script> 
  function SetIcon() {
    var address = document.getElementById('addr').value; 
    var icon = document.getElementById('icon');
    icon.style.backgroundImage = 'url(' + blockies.create({ seed:address ,size: 8,scale: 16}).toDataURL()+')' 
  }
</script>
```

For more details about icon generation with `iconhash_js` see [index.html](https://github.com/metahashorg/iconhash_js/blob/master/index.html).

## Examples

Metahash address  | Icon                             |
--- | -------------------------------- |
0x004912b752f4b2588b8195f65b77289c44f2bc06c1f117b4bf | <img width="64" height="64" src="https://github.com/metahashorg/iconhash_js/blob/master/Examples/0x004912b752f4b2588b8195f65b77289c44f2bc06c1f117b4bf.png"> |
0x001119e0af87a72bec580f7288001943496b790c1ad887456e | <img width="64" height="64" src="https://github.com/metahashorg/iconhash_js/blob/master/Examples/0x001119e0af87a72bec580f7288001943496b790c1ad887456e.png"> |
0x007679e0af87a72bec580f7288001943496b790c1ad887456e | <img width="64" height="64" src="https://github.com/metahashorg/iconhash_js/blob/master/Examples/0x007679e0af87a72bec580f7288001943496b790c1ad887456e.png"> |
0x00f05b89b4bc1023dbf34b8cb209cadc8d68580db7d7ae3723 | <img width="64" height="64" src="https://github.com/metahashorg/iconhash_js/blob/master/Examples/0x00f05b89b4bc1023dbf34b8cb209cadc8d68580db7d7ae3723.png"> |
0x00f05b89b4bc1023dbf34b8cb209cadc8d68580db7d7ae37ca | <img width="64" height="64" src="https://github.com/metahashorg/iconhash_js/blob/master/Examples/0x00f05b89b4bc1023dbf34b8cb209cadc8d68580db7d7ae37ca.png"> |
 
