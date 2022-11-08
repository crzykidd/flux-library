# flux-library
  
I am working on some energy graphs using data from iotawatt pushed into Influxdb2, and displayed with Grafana.   This is a short library of flux snipits etc that I found helpful.

## Easy wins
### Dealing with Timezomes
First getting the data to display by your timezone is easy with this little snipit:

// Setup your timezone info so that the day resets for you correctly.
import "timezone" 
option location = timezone.location(name: "America/Los_Angeles")

```
// Setup your timezone info so that the day resets for you correctly.
import "timezone" 
option location = timezone.location(name: "America/Los_Angeles")
```