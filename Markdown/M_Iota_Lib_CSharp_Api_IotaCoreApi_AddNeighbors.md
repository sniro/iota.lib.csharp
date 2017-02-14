# IotaCoreApi.AddNeighbors Method 
 

Adds the neighbor(s) to the node. It should be noted that this is only temporary, and the added neighbors will be removed from your set of neighbors after you relaunch IRI.

**Namespace:**&nbsp;<a href="N_Iota_Lib_CSharp_Api">Iota.Lib.CSharp.Api</a><br />**Assembly:**&nbsp;IotaApi (in IotaApi.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

**C#**<br />
``` C#
public AddNeighborsResponse AddNeighbors(
	params string[] uris
)
```


#### Parameters
&nbsp;<dl><dt>uris</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a>[]<br />The uris of the neighbors to add. The URI (Unique Resource Identification) format is "udp://IPADDRESS:PORT"</dd></dl>

#### Return Value
Type: <a href="T_Iota_Lib_CSharp_Api_Core_AddNeighborsResponse">AddNeighborsResponse</a><br />Returns the number of added Neighbors

## See Also


#### Reference
<a href="T_Iota_Lib_CSharp_Api_IotaCoreApi">IotaCoreApi Class</a><br /><a href="N_Iota_Lib_CSharp_Api">Iota.Lib.CSharp.Api Namespace</a><br />