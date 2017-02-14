# IotaApi.GetInputs Method 
 

Gets all possible inputs of a seed and returns them with the total balance. This is either done deterministically (by genearating all addresses until findTransactions is empty and doing getBalances), or by providing a key range to use for searching through.

**Namespace:**&nbsp;<a href="N_Iota_Lib_CSharp_Api">Iota.Lib.CSharp.Api</a><br />**Assembly:**&nbsp;IotaApi (in IotaApi.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

**C#**<br />
``` C#
public Inputs GetInputs(
	string seed,
	int start,
	int end,
	long threshold = 100
)
```


#### Parameters
&nbsp;<dl><dt>seed</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />tryte-encoded seed. It should be noted that this seed is not transferred</dd><dt>start</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/td2s409d" target="_blank">System.Int32</a><br />Starting key index</dd><dt>end</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/td2s409d" target="_blank">System.Int32</a><br />Ending key index</dd><dt>threshold (Optional)</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/6yy583ek" target="_blank">System.Int64</a><br />Minimum threshold of accumulated balances from the inputs that is required</dd></dl>

#### Return Value
Type: <a href="T_Iota_Lib_CSharp_Api_Model_Inputs">Inputs</a><br />\[Missing <returns> documentation for "M:Iota.Lib.CSharp.Api.IotaApi.GetInputs(System.String,System.Int32,System.Int32,System.Int64)"\]

## See Also


#### Reference
<a href="T_Iota_Lib_CSharp_Api_IotaApi">IotaApi Class</a><br /><a href="N_Iota_Lib_CSharp_Api">Iota.Lib.CSharp.Api Namespace</a><br />