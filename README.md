# Nebflix

### Welcome to the Nebflix host page

If Nebflix is live, users should be redirected automatically from the page to the Plex server page.  
If users are not redirected then information (such as maintenance) will be displayed on the webpage.

 - [ ] Catch. With ShowRSS.
 - [ ] [CouchPotato](https://couchpota.to/)
 - [ ] [Hazel](https://www.noodlesoft.com/)

__Migrate Plex Server to new Macintosh__  
[Move an Install to Another System](https://support.plex.tv/hc/en-us/articles/201370363-Move-an-Install-to-Another-System)

### Migration

Migration was carried out for the following applications:
 - Hazel (to move the 'rules')
 - uTorrent (to move the RSS automatic downloads feeds)
 
```~/Library/Application Support/```
This was utilised to move the relevant support files for each application.

```~/Library/Preferences/```
In here the relevant __plist__ file was copied across for Noodlesoft's Hazel (`com.noodlesoft`).

> __NB. A restart is always recommended following a plist copy - and always ensure the program is closed first.__

