# IotaCoreApi Class
 

This class provides access to the Iota core API


## Inheritance Hierarchy
<a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />&nbsp;&nbsp;Iota.Lib.CSharp.Api.IotaCoreApi<br />&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_Iota_Lib_CSharp_Api_IotaApi">Iota.Lib.CSharp.Api.IotaApi</a><br />
**Namespace:**&nbsp;<a href="N_Iota_Lib_CSharp_Api">Iota.Lib.CSharp.Api</a><br />**Assembly:**&nbsp;IotaApi (in IotaApi.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

**C#**<br />
``` C#
public class IotaCoreApi
```

The IotaCoreApi type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Iota_Lib_CSharp_Api_IotaCoreApi__ctor">IotaCoreApi</a></td><td>
Creates a core api object that uses the specified connection settings to connect to a node</td></tr></table>&nbsp;
<a href="#iotacoreapi-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Iota_Lib_CSharp_Api_IotaCoreApi_AddNeighbors">AddNeighbors</a></td><td>
Adds the neighbor(s) to the node. It should be noted that this is only temporary, and the added neighbors will be removed from your set of neighbors after you relaunch IRI.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Iota_Lib_CSharp_Api_IotaCoreApi_AttachToTangle">AttachToTangle</a></td><td>
Attaches the specified transactions (trytes) to the Tangle by doing Proof of Work. You need to supply branchTransaction as well as trunkTransaction (basically the tips which you're going to validate and reference with this transaction) - both of which you'll get through the getTransactionsToApprove API call.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Iota_Lib_CSharp_Api_IotaCoreApi_BroadcastTransactions">BroadcastTransactions</a></td><td>
Broadcasts the transactions.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/bsc2ak47" target="_blank">Equals</a></td><td>
Determines whether the specified <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a> is equal to the current <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/4k87zsw7" target="_blank">Finalize</a></td><td>
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Iota_Lib_CSharp_Api_IotaCoreApi_FindTransactions">FindTransactions</a></td><td>
Finds the transactions using the specified arguments as search criteria</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Iota_Lib_CSharp_Api_IotaCoreApi_GetBalances">GetBalances</a></td><td>
Gets the balances.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/zdee4b3y" target="_blank">GetHashCode</a></td><td>
Serves as a hash function for a particular type.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Iota_Lib_CSharp_Api_IotaCoreApi_GetInclusionStates">GetInclusionStates</a></td><td>
Gets the inclusion states.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Iota_Lib_CSharp_Api_IotaCoreApi_GetNeighbors">GetNeighbors</a></td><td>
Gets the neighbors the node is connected to</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Iota_Lib_CSharp_Api_IotaCoreApi_GetNodeInfo">GetNodeInfo</a></td><td>
Gets the node information.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Iota_Lib_CSharp_Api_IotaCoreApi_GetTips">GetTips</a></td><td>
Gets the tips.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Iota_Lib_CSharp_Api_IotaCoreApi_GetTransactionsToApprove">GetTransactionsToApprove</a></td><td>
Gets the transactions to approve.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Iota_Lib_CSharp_Api_IotaCoreApi_GetTrytes">GetTrytes</a></td><td>
Gets the raw transaction data (trytes) of a specific transaction. These trytes can then be easily converted into the actual transaction object using the constructor of Transaction</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/dfwy45w9" target="_blank">GetType</a></td><td>
Gets the <a href="http://msdn2.microsoft.com/en-us/library/42892f65" target="_blank">Type</a> of the current instance.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Iota_Lib_CSharp_Api_IotaCoreApi_InterruptAttachingToTangle">InterruptAttachingToTangle</a></td><td>
Interrupts and completely aborts the attachToTangle process.</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/57ctke0a" target="_blank">MemberwiseClone</a></td><td>
Creates a shallow copy of the current <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Iota_Lib_CSharp_Api_IotaCoreApi_RemoveNeighbors">RemoveNeighbors</a></td><td>
Removes the neighbor(s) from the node.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Iota_Lib_CSharp_Api_IotaCoreApi_StoreTransactions">StoreTransactions</a></td><td>
Stores the specified transactions in trytes into the local storage. The trytes to be used for this call are returned by attachToTangle.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/7bxwbwt2" target="_blank">ToString</a></td><td>
Returns a string that represents the current object.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr></table>&nbsp;
<a href="#iotacoreapi-class">Back to Top</a>

## See Also


#### Reference
<a href="N_Iota_Lib_CSharp_Api">Iota.Lib.CSharp.Api Namespace</a><br />