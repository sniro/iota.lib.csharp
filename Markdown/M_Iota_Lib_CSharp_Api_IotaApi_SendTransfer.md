# IotaApi.SendTransfer Method 
 

Wrapper function that basically does prepareTransfers, as well as attachToTangle and finally, it broadcasts and stores the transactions locally.

**Namespace:**&nbsp;<a href="N_Iota_Lib_CSharp_Api">Iota.Lib.CSharp.Api</a><br />**Assembly:**&nbsp;IotaApi (in IotaApi.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

**C#**<br />
``` C#
public bool[] SendTransfer(
	string seed,
	int depth,
	int minWeightMagnitude,
	Transfer[] transfers,
	Input[] inputs = null,
	string address = null
)
```


#### Parameters
&nbsp;<dl><dt>seed</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />tryte-encoded seed</dd><dt>depth</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/td2s409d" target="_blank">System.Int32</a><br />depth</dd><dt>minWeightMagnitude</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/td2s409d" target="_blank">System.Int32</a><br />\[Missing <param name="minWeightMagnitude"/> documentation for "M:Iota.Lib.CSharp.Api.IotaApi.SendTransfer(System.String,System.Int32,System.Int32,Iota.Lib.CSharp.Api.Model.Transfer[],Iota.Lib.CSharp.Api.Model.Input[],System.String)"\]</dd><dt>transfers</dt><dd>Type: <a href="T_Iota_Lib_CSharp_Api_Model_Transfer">Iota.Lib.CSharp.Api.Model.Transfer</a>[]<br />Array of transfer objects</dd><dt>inputs (Optional)</dt><dd>Type: <a href="T_Iota_Lib_CSharp_Api_Model_Input">Iota.Lib.CSharp.Api.Model.Input</a>[]<br />Option (default null). List of inputs used for funding the transfer</dd><dt>address (Optional)</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />if defined, this address will be used for sending the remainder value (of the inputs) to</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/a28wyd50" target="_blank">Boolean</a>[]<br />an array of the transfer (transaction objects)

## See Also


#### Reference
<a href="T_Iota_Lib_CSharp_Api_IotaApi">IotaApi Class</a><br /><a href="N_Iota_Lib_CSharp_Api">Iota.Lib.CSharp.Api Namespace</a><br />