# ima-videojs-ads-player

A javascript library using IMA sdk, Video JS and CSS to render sliding video ads or in-article video ads on a webpage.

![Alt Text](https://cdn.timesapp.app/player/1.gif)
![Alt Text](https://cdn.timesapp.app/player/2.gif)

## Installation

```bash
npm install ima-videojs-ads-player
```

## Usage

```python
require('ima-videojs-ads-player')
#OR
<script src="https://cdn.timesapp.app/player/player.min.js"></script>
# Add this Tag where you want your ad video
#
        <div class='arewethere-video slider' data-view='desktop' data-id='pid-1027' data-width='500'
            data-tag='https://adn.pilotx.tv/vast?pid=1027&pageurl=tools.pilotx.tv&domain=pilotx.tv&w=640&h=360'
            data-height='300' data-icon='https://cdn.timesapp.app/player/logo.jpg'> </div>

class = arewethere-video and any one of (slider | in_article | in_article_fixed)
data-view = desktop, mobile
data-tag  = Ad tag url
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