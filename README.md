# Trackboxx [UNOFFICIAL]
**Custom Tag Template for server-side Google Tag Manager**

Send pageviews, downloads, links or ecom events to Trackboxx 

[![Template Status](https://img.shields.io/badge/Community%20Template%20Gallery%20Status-beta-orange)](https://tagmanager.google.com/gallery/#/owners/mbaersch/templates/trackboxx-tag-server) ![Repo Size](https://img.shields.io/github/repo-size/mbaersch/trackboxx-tag-server) ![License](https://img.shields.io/github/license/mbaersch/trackboxx-tag-server)
    
---

## Usage
Install the tag template and add a new *Trackboxx* tag. Enter your Site ID and domain (including https://). Per default, the tag sends a page view when loaded and processes ecom events and external links. 

### Sending Goal Conversions
Change "Tracking Type" in order to send a goal instead of "base tracking" with this tag and enter a Goal ID from your Trackboxx backend.   

### Advanced Settings
This section contains additional options that allows enhanced data redaction. You can optionally send an empty referrer and delete any parameters from tracked urls. 

#### Changing Page Path
If you want to collect data from several sources in different paths of the same profile, you can override the page path with a different value. This option also can be used for further data redaction or enrichment - as well as the option to delete all parameters from the path before sending data to Umami.

#### Track Downloads
If you want to add all downloads (incoming *file_download* events) to your link tracking reports, check the last option. 
