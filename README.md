## runit

This package provides [`runit`](http://smarden.org/runit/) support for Fedora and can be used alongside systemd.

Source is maintained in branch `ver-{VERSION}-{RELEASE}`. Pre-built RPMs and SRPM can be downloaded from [here](https://drive.google.com/open?id=0B_tTbuxmuRzIR05wQ3E1eWVyaGs).

**Note:** Runit is configured to use `/etc/service` as its service directory. You can maintain runit services under this directory or by creating a symlink into it. `runit-pause` command is available to run _oneshot_ services.
