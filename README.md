# jsocache
A javascript object cache written in emcascript for node, browser and embedded platforms.

To install:
```
git clone https://github.com/LaughingSun/jsocache.git
cd jsocache
./build
```
or you can just download it.  We will be adding it to npm soon, so check back from time to time.

To use:
```
const JSOC = require( './jsoc' )
  , cache0 = new JSOC
    ;
cache0.put( 'key', { 'message': 'this is my message' } );
var msg = cache0.get( 'key' )'

## for more inmformation check the markdown files especially in the docs dirctory.

MIT license.
