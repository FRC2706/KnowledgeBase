1. Created ‘playVideo’ script:
 ```bash
#!/bin/bash

while :
do
  omxplayer -b –loop video.mp4
done
```

2. Added script to `.bashrc`

3. Optional. Set network interfaces to `manual` in `/etc/network/interfaces`
