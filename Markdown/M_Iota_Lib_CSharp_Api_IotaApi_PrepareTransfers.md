# IotaApi.PrepareTransfers Method 
 

Main purpose of this function is to get an array of transfer objects as input, and then prepare the transfer by generating the correct bundle, as well as choosing and signing the inputs if necessary (if it's a value transfer). The output of this function is an array of the raw transaction data (trytes)

**Namespace:**&nbsp;<a href="N_Iota_Lib_CSharp_Api">Iota.Lib.CSharp.Api</a><br />**Assembly:**&nbsp;IotaApi (in IotaApi.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

**C#**<br />
``` C#
public List<string> PrepareTransfers(
	string seed,
	Transfer[] transfers,
	List<Input> inputs = null,
	string remainderAddress = null
)
```


#### Parameters
&nbsp;<dl><dt>seed</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />81-tryte encoded address of recipient</dd><dt>transfers</dt><dd>Type: <a href="T_Iota_Lib_CSharp_Api_Model_Transfer">Iota.Lib.CSharp.Api.Model.Transfer</a>[]<br />\[Missing <param name="transfers"/> documentation for "M:Iota.Lib.CSharp.Api.IotaApi.PrepareTransfers(System.String,Iota.Lib.CSharp.Api.Model.Transfer[],System.Collections.Generic.List{Iota.Lib.CSharp.Api.Model.Input},System.String)"\]</dd><dt>inputs (Optional)</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/6sh2ey19" target="_blank">System.Collections.Generic.List</a>(<a href="T_Iota_Lib_CSharp_Api_Model_Input">Input</a>)<br />\[Missing <param name="inputs"/> documentation for "M:Iota.Lib.CSharp.Api.IotaApi.PrepareTransfers(System.String,Iota.Lib.CSharp.Api.Model.Transfer[],System.Collections.Generic.List{Iota.Lib.CSharp.Api.Model.Input},System.String)"\]</dd><dt>remainderAddress (Optional)</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />Optional (default null). if defined, this address will be used for sending the remainder value (of the inputs) to.</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/6sh2ey19" target="_blank">List</a>(<a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">String</a>)<br />an array that contains the trytes of the new bundle

## See Also


#### Reference
<a href="T_Iota_Lib_CSharp_Api_IotaApi">IotaApi Class</a><br /><a href="N_Iota_Lib_CSharp_Api">Iota.Lib.CSharp.Api Namespace</a><br />