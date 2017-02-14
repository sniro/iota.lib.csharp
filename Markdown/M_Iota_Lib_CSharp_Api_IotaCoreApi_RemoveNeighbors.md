# IotaCoreApi.RemoveNeighbors Method 
 

Removes the neighbor(s) from the node.

**Namespace:**&nbsp;<a href="N_Iota_Lib_CSharp_Api">Iota.Lib.CSharp.Api</a><br />**Assembly:**&nbsp;IotaApi (in IotaApi.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

**C#**<br />
``` C#
public RemoveNeighborsResponse RemoveNeighbors(
	params string[] uris
)
```


#### Parameters
&nbsp;<dl><dt>uris</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a>[]<br />The uris of the neighbors to add. The URI (Unique Resource Identification) format is "udp://IPADDRESS:PORT"</dd></dl>

#### Return Value
Type: <a href="T_Iota_Lib_CSharp_Api_Core_RemoveNeighborsResponse">RemoveNeighborsResponse</a><br />Returns the number of remvoved neighbors

## See Also


#### Reference
<a href="T_Iota_Lib_CSharp_Api_IotaCoreApi">IotaCoreApi Class</a><br /><a href="N_Iota_Lib_CSharp_Api">Iota.Lib.CSharp.Api Namespace</a><br />