## Youtube-Video-Viewer-Python
A python library that uses browser automation to watch videos on youtube automatically
At present, it runs on Windows only.
It uses [datakund](https://pypi.org/project/datakund) internally

Complete Documentation available [here](https://youtube-api.datakund.com/en/latest/)


### Support
For any help / feedback you can message us here
* datakund@gmail.com
* https://t.me/datakund

### Installation

```sh
pip install youtube-video-viewer
```

### Import

```javascript
from youtube-video-viewer import *
```

### Watch Video

To watch video we use ``watch_video`` function
It requires **video_url** & **time** as input parameters

```javascript
youtube.watch_video(time="time_in_seconds",video_url="video_url_here")
```

### DataKund
It uses [datakund](https://pypi.org/project/datakund/) internally to do browser automation
DataKund is an automation library that uses selenium & supports automation of many sites including [Youtube](https://youtube-api.datakund.com/en/latest/), [Amazon](https://amazon-api.datakund.com/en/latest/), [Twitter](https://twitter-api.datakund.com/en/latest/), [LinkedIn](https://linkedin-api.datakund.com/en/latest/) , [Google](https://google-api.datakund.com/en/latest/) etc.
