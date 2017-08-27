# Nebflix

### Welcome to the Nebflix host page

[Nebflix.uk](http://nebflix.uk) is the home page to the media server. Information is displayed here as well as a link to get to Plex.  
Content can be viewed at [watch.nebflix.uk](http://watch.nebflix.uk) linked to on the Home page.  
Maintenance or other issues will be put on the Home page.

Software in use:
- [x] [showRSS](http://showrss.info/) - RSS Feed of TV shows episodes linking to torrent.
- [x] [Catch](http://giorgiocalderolla.com/catch.html) - Watch RSS feed and automatically add to preferred BT client.
- [x] [uTorrent](http://www.utorrent.com/) - Download torrent and move to a '_Completed Download_' folder.
- [x] [Hazel](https://www.noodlesoft.com/) - Watch '_Completed Download_' folder and move new files to the correct directories.

- [ ] [CouchPotato](https://couchpota.to/)


### Migration

[__Move an Install to Another System (Plex)__](https://support.plex.tv/hc/en-us/articles/201370363-Move-an-Install-to-Another-System)

Migration was carried out for the following applications:
 - Hazel (to move the 'rules')
 - uTorrent (to move the RSS automatic downloads feeds)
 
```~/Library/Application Support/```
This was utilised to move the relevant support files for each application.

```~/Library/Preferences/```
In here the relevant __plist__ file was copied across for Noodlesoft's Hazel (`com.noodlesoft`).

> __NB. A restart is always recommended following a plist copy - and always ensure the program is closed first.__

