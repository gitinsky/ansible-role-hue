Hue
=========

This role just installs [hue](http://gethue.com) to /opt/hue, supervisor is not included. Tested on ubuntu 14.04 and based on [generic](https://github.com/cloudera/hue) and [ubuntu 14.04](http://gethue.com/how-to-build-hue-on-ubuntu-14-04-trusty/) official guides.

To run the hue server run the following command:

```bash
/opt/hue/build/env/bin/hue runserver 0.0.0.0:8000
```
