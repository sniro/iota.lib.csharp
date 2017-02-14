# IotaCoreApi.GetBalances Method 
 

Gets the balances.

**Namespace:**&nbsp;<a href="N_Iota_Lib_CSharp_Api">Iota.Lib.CSharp.Api</a><br />**Assembly:**&nbsp;IotaApi (in IotaApi.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

**C#**<br />
``` C#
public GetBalancesResponse GetBalances(
	List<string> addresses,
	long threshold = 100
)
```


#### Parameters
&nbsp;<dl><dt>addresses</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/6sh2ey19" target="_blank">System.Collections.Generic.List</a>(<a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">String</a>)<br />The addresses.</dd><dt>threshold (Optional)</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/6yy583ek" target="_blank">System.Int64</a><br />The threshold.</dd></dl>

#### Return Value
Type: <a href="T_Iota_Lib_CSharp_Api_Core_GetBalancesResponse">GetBalancesResponse</a><br />It returns the confirmed balance which a list of addresses have at the latest confirmed milestone. In addition to the balances, it also returns the milestone as well as the index with which the confirmed balance was determined. The balances is returned as a list in the same order as the addresses were provided as input.

## See Also


#### Reference
<a href="T_Iota_Lib_CSharp_Api_IotaCoreApi">IotaCoreApi Class</a><br /><a href="N_Iota_Lib_CSharp_Api">Iota.Lib.CSharp.Api Namespace</a><br />