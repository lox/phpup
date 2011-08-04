Phpup 
=====

Often in development you'll want to run a php project without writing up a full 
apache config for it. This generates a minimal apache config and runs an apache
instance in the foreground.

This was developed under OSX 10.7, although I'm fairly sure most modern OSX's will
work.

Running
=======

```bash
./phpup -p 8000 -f helloworld.php
```

Disclaimer
==========

This is a 20 minute hack. I'm sure I missed some critical apache config. Patches
appreciated!


