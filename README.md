** THIS PROJECT IS DEPRECATED **

As of Jai 0.1.040, this library has been merged into the standard library. It will therefore
no longer be maintained separately. 

~~~~


# Jai Socket Library

Basic socket/networking library for Jai. Currently pretty rudimentary, but fills
in some gaps in Jai's standard library. This library may become partially or 
entirely obsolete as Jai's library backfills its networking stuff. In the meantime,
I'm using this for some of my experiments.

Cannibalizing this is highly encouraged.

# Usage

Easiest is to load it into your program like so:

```
#load "jai-socket/module.jai";
```

But if you want to provide it as a local module, you can put it in Jai's `modules/` directory
(or better yet, symlink it in there). I call it `Socket` there. Then you can do:

```
#import "Socket";
```

Beware, if you do this, that at some point Jai will probably have a library called `Socket`,
that may or may not be based on this one. You may end up confusing yourself or others!

# License

Released to the Public Domain. If you wish to cite the original author, that'd be nice.
