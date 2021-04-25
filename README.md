# Check Your IP Address
## Disclaimer : We are using [IP.SB Api](https://ip.sb/api) to perform query. Please don't abuse it!

## Purpose
Simply to get your IP Address details including but not limited to :
1. IP Address
2. Region
3. Time Zone
4. ASN
5. Country
6. Country Code
7. ISP

## Source 
We are using [IP.SB Api](https://ip.sb/api) to perform query of each IP Address.
An example usage :
``` 
<p><script type="application/javascript">
function getgeoip(json){
    document.write("", json.ip);
    document.write(", ", json.isp);
    document.write(", ", json.asn);
    document.write(", ", json.region);
	document.write(", ", json.timezone);
	document.write(", ", json.country);
	document.write(", ", json.country_code);
}
</script>

<script type="application/javascript" src="https://api.ip.sb/geoip?callback=getgeoip"></script></p>
```
**Please don't abuse this API!**

## Privacy
We won't log user's details , but we aren't guarantee other platforms such as [IP.SB](https://ip.sb) will log user's details.
For more information , please visit [IP.SB](https://ip.sb).
