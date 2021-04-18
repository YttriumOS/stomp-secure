## using stomp-secure custom repo to install binaries 

**1.** 
```
sudo touch /etc/xbps.d/stomp-secure
```

**2. append this to the respective file :** 

```
repository=https://github.com/YttriumOS/stomp-secure/tree/main/core/

```
**3. Update your repos<br><br>**

**4. sudo xbps-install -S packagename**

