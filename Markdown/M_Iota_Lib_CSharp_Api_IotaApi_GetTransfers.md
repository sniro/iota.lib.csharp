# IotaApi.GetTransfers Method 
 

Gets the transfers which are associated with a seed. The transfers are determined by either calculating deterministically which addresses were already used, or by providing a list of indexes to get the transfers from.

**Namespace:**&nbsp;<a href="N_Iota_Lib_CSharp_Api">Iota.Lib.CSharp.Api</a><br />**Assembly:**&nbsp;IotaApi (in IotaApi.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

**C#**<br />
``` C#
public Bundle[] GetTransfers(
	string seed,
	Nullable<int> start,
	Nullable<int> end,
	bool inclusionStates = false
)
```


#### Parameters
&nbsp;<dl><dt>seed</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />tryte-encoded seed. It should be noted that this seed is not transferred</dd><dt>start</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/b3h38hb0" target="_blank">System.Nullable</a>(<a href="http://msdn2.microsoft.com/en-us/library/td2s409d" target="_blank">Int32</a>)<br />\[Missing <param name="start"/> documentation for "M:Iota.Lib.CSharp.Api.IotaApi.GetTransfers(System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Boolean)"\]</dd><dt>end</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/b3h38hb0" target="_blank">System.Nullable</a>(<a href="http://msdn2.microsoft.com/en-us/library/td2s409d" target="_blank">Int32</a>)<br />\[Missing <param name="end"/> documentation for "M:Iota.Lib.CSharp.Api.IotaApi.GetTransfers(System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Boolean)"\]</dd><dt>inclusionStates (Optional)</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/a28wyd50" target="_blank">System.Boolean</a><br />If True, it gets the inclusion states of the transfers.</dd></dl>

#### Return Value
Type: <a href="T_Iota_Lib_CSharp_Api_Model_Bundle">Bundle</a>[]<br />An Array of Bundle object that represent the transfers

## See Also


#### Reference
<a href="T_Iota_Lib_CSharp_Api_IotaApi">IotaApi Class</a><br /><a href="N_Iota_Lib_CSharp_Api">Iota.Lib.CSharp.Api Namespace</a><br />