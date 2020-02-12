# ima-videojs-ads-player

A javascript library using IMA sdk, Video JS and CSS to render sliding video ads or in-article video ads on a webpage.

![Alt Text](https://cdn.timesapp.app/player/1.gif)
![Alt Text](https://cdn.timesapp.app/player/2.gif)

## Installation

```bash
npm install ima-videojs-ads-player --save
```

## Usage

```python
require('ima-videojs-ads-player')
#OR
<script src="https://cdn.timesapp.app/player/player.min.js"></script>
#
# Then add Tag where you want your video Ads
<div class='arewethere-video slider' data-view='desktop/mobile' data-id='id' data-width='500' data-height='300' data-tag='ad_tag_url' > </div>
#
#Example Tag
        <div class='arewethere-video slider' data-view='desktop' data-id='pid-1027' data-width='500'
            data-tag='http://pubads.g.doubleclick.net/gampad/ads?sz=640x480&iu=/124319096/external/ad_rule_samples&ciu_szs=300x250&ad_rule=1&impl=s&gdfp_req=1&env=vp&output=xml_vmap1&unviewed_position_start=1&cust_params=sample_ar%3Dpremidpostpod%26deployment%3Dgmf-js&cmsid=496&vid=short_onecue&correlator=' data-height='300' data-icon='https://cdn.timesapp.app/player/logo.jpg'> </div>

## Tag Attribute Descriptions
class = arewethere-video and any one of (slider | in_article | in_article_fixed)
data-view = desktop, mobile
data-tag  = Ad tag url (vast/vpaid)
data-id =  Video tag ID
data-width Video Width
data-height = Video Height
data-icon  = Video Bottom logo url (Optional)
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)