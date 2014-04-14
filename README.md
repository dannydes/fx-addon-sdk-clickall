fx-addon-sdk-clickall
=====================

This is a lightweight library to allow triggering clicks on a set of 
elements within content-mode.

Simply copy the files retaining the same directory structure, 
import the module content-clickall:
<code>
let clickAll = require( 'content-clickall' );
</code>
and call the fire() method.
<code>
clickAll.fire( CSSselector );
</code>
