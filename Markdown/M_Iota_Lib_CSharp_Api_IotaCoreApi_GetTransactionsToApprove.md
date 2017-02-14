# IotaCoreApi.GetTransactionsToApprove Method 
 

Gets the transactions to approve.

**Namespace:**&nbsp;<a href="N_Iota_Lib_CSharp_Api">Iota.Lib.CSharp.Api</a><br />**Assembly:**&nbsp;IotaApi (in IotaApi.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

**C#**<br />
``` C#
public GetTransactionsToApproveResponse GetTransactionsToApprove(
	int depth
)
```


#### Parameters
&nbsp;<dl><dt>depth</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/td2s409d" target="_blank">System.Int32</a><br />The depth is the number of bundles to go back to determine the transactions for approval. The higher your depth value, the more "babysitting" you do for the network (as you have to confirm more transactions).</dd></dl>

#### Return Value
Type: <a href="T_Iota_Lib_CSharp_Api_Core_GetTransactionsToApproveResponse">GetTransactionsToApproveResponse</a><br />trunkTransaction and branchTransaction (result of the Tip selection)

## See Also


#### Reference
<a href="T_Iota_Lib_CSharp_Api_IotaCoreApi">IotaCoreApi Class</a><br /><a href="N_Iota_Lib_CSharp_Api">Iota.Lib.CSharp.Api Namespace</a><br />