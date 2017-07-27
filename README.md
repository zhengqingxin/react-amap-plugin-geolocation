# Geolocation Plugin for [react-amap](https://elemefe.github.io/react-amap/)

Configurable props are
+ enableHighAccuracy
+ timeout
+ maximumAge
+ buttonOffset
+ ...

Visit [AMap doc](http://lbs.amap.com/api/javascript-api/reference/location/#m_AMap.Geolocation) for details about **ALL** prop;


```
import { Map } from 'react-amap';
import Geolocation from 'react-amap-plugin-geolocation';


const pluginProps = {
  enableHighAccuracy:true,
  timeout: 10000,
  showButton: true
}


// render
<Map>
  <Geolocation {...pluginProps} />
</Map>

```