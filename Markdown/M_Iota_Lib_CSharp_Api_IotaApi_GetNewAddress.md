# IotaApi.GetNewAddress Method 
 

Generates a new address from a seed and returns the remainderAddress. This is either done deterministically, or by providing the index of the new remainderAddress

**Namespace:**&nbsp;<a href="N_Iota_Lib_CSharp_Api">Iota.Lib.CSharp.Api</a><br />**Assembly:**&nbsp;IotaApi (in IotaApi.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

**C#**<br />
``` C#
public string[] GetNewAddress(
	string seed,
	int index = 0,
	bool checksum = false,
	int total = 0,
	bool returnAll = false
)
```


#### Parameters
&nbsp;<dl><dt>seed</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />Tryte-encoded seed. It should be noted that this seed is not transferred</dd><dt>index (Optional)</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/td2s409d" target="_blank">System.Int32</a><br />Optional (default null). Key index to start search from. If the index is provided, the generation of the address is not deterministic.</dd><dt>checksum (Optional)</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/a28wyd50" target="_blank">System.Boolean</a><br />Optional (default false). Adds 9-tryte address checksum</dd><dt>total (Optional)</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/td2s409d" target="_blank">System.Int32</a><br />Optional (default 1)Total number of addresses to generate.</dd><dt>returnAll (Optional)</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/a28wyd50" target="_blank">System.Boolean</a><br />If true, it returns all addresses which were deterministically generated (until findTransactions returns null)</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">String</a>[]<br />an array of strings with the specifed number of addresses

## See Also


#### Reference
<a href="T_Iota_Lib_CSharp_Api_IotaApi">IotaApi Class</a><br /><a href="N_Iota_Lib_CSharp_Api">Iota.Lib.CSharp.Api Namespace</a><br />