# IotaCoreApi.AttachToTangle Method 
 

Attaches the specified transactions (trytes) to the Tangle by doing Proof of Work. You need to supply branchTransaction as well as trunkTransaction (basically the tips which you're going to validate and reference with this transaction) - both of which you'll get through the getTransactionsToApprove API call.

**Namespace:**&nbsp;<a href="N_Iota_Lib_CSharp_Api">Iota.Lib.CSharp.Api</a><br />**Assembly:**&nbsp;IotaApi (in IotaApi.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

**C#**<br />
``` C#
public AttachToTangleResponse AttachToTangle(
	string trunkTransaction,
	string branchTransaction,
	string[] trytes,
	int minWeightMagnitude = 18
)
```


#### Parameters
&nbsp;<dl><dt>trunkTransaction</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />Trunk transaction to approve.</dd><dt>branchTransaction</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />Branch transaction to approve.</dd><dt>trytes</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a>[]<br />List of trytes (raw transaction data) to attach to the tangle.</dd><dt>minWeightMagnitude (Optional)</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/td2s409d" target="_blank">System.Int32</a><br />Proof of Work intensity. Minimum value is 18</dd></dl>

#### Return Value
Type: <a href="T_Iota_Lib_CSharp_Api_Core_AttachToTangleResponse">AttachToTangleResponse</a><br />The returned value contains a different set of tryte values which you can input into broadcastTransactions and storeTransactions. The returned tryte value, the last 243 trytes basically consist of the: trunkTransaction + branchTransaction + nonce. These are valid trytes which are then accepted by the network.

## See Also


#### Reference
<a href="T_Iota_Lib_CSharp_Api_IotaCoreApi">IotaCoreApi Class</a><br /><a href="N_Iota_Lib_CSharp_Api">Iota.Lib.CSharp.Api Namespace</a><br />