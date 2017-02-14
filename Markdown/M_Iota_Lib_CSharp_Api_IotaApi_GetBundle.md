# IotaApi.GetBundle Method 
 

This function returns the bundle which is associated with a transaction. Input can by any type of transaction (tail and non-tail). If there are conflicting bundles (because of a replay for example) it will return multiple bundles. It also does important validation checking (signatures, sum, order) to ensure that the correct bundle is returned.

**Namespace:**&nbsp;<a href="N_Iota_Lib_CSharp_Api">Iota.Lib.CSharp.Api</a><br />**Assembly:**&nbsp;IotaApi (in IotaApi.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

**C#**<br />
``` C#
public Bundle GetBundle(
	string transaction
)
```


#### Parameters
&nbsp;<dl><dt>transaction</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />the transaction encoded in trytes</dd></dl>

#### Return Value
Type: <a href="T_Iota_Lib_CSharp_Api_Model_Bundle">Bundle</a><br />an array of bundle, if there are multiple arrays it means that there are conflicting bundles.

## See Also


#### Reference
<a href="T_Iota_Lib_CSharp_Api_IotaApi">IotaApi Class</a><br /><a href="N_Iota_Lib_CSharp_Api">Iota.Lib.CSharp.Api Namespace</a><br />