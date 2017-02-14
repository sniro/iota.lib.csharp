# IotaApi Methods
 

The <a href="T_Iota_Lib_CSharp_Api_IotaApi">IotaApi</a> type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Iota_Lib_CSharp_Api_IotaCoreApi_AddNeighbors">AddNeighbors</a></td><td>
Adds the neighbor(s) to the node. It should be noted that this is only temporary, and the added neighbors will be removed from your set of neighbors after you relaunch IRI.
 (Inherited from <a href="T_Iota_Lib_CSharp_Api_IotaCoreApi">IotaCoreApi</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Iota_Lib_CSharp_Api_IotaCoreApi_AttachToTangle">AttachToTangle</a></td><td>
Attaches the specified transactions (trytes) to the Tangle by doing Proof of Work. You need to supply branchTransaction as well as trunkTransaction (basically the tips which you're going to validate and reference with this transaction) - both of which you'll get through the getTransactionsToApprove API call.
 (Inherited from <a href="T_Iota_Lib_CSharp_Api_IotaCoreApi">IotaCoreApi</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Iota_Lib_CSharp_Api_IotaApi_BroadcastAndStore">BroadcastAndStore</a></td><td>
Wrapper function that broadcasts and stores the specified trytes</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Iota_Lib_CSharp_Api_IotaCoreApi_BroadcastTransactions">BroadcastTransactions</a></td><td>
Broadcasts the transactions.
 (Inherited from <a href="T_Iota_Lib_CSharp_Api_IotaCoreApi">IotaCoreApi</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Iota_Lib_CSharp_Api_IotaApi_BundlesFromAddresses">BundlesFromAddresses</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/bsc2ak47" target="_blank">Equals</a></td><td>
Determines whether the specified <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a> is equal to the current <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/4k87zsw7" target="_blank">Finalize</a></td><td>
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Iota_Lib_CSharp_Api_IotaApi_FindTransactionObjects">FindTransactionObjects</a></td><td>
Finds the transaction objects.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Iota_Lib_CSharp_Api_IotaApi_FindTransactionObjectsByBundle">FindTransactionObjectsByBundle</a></td><td>
Finds the transaction objects by bundle.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Iota_Lib_CSharp_Api_IotaCoreApi_FindTransactions">FindTransactions</a></td><td>
Finds the transactions using the specified arguments as search criteria
 (Inherited from <a href="T_Iota_Lib_CSharp_Api_IotaCoreApi">IotaCoreApi</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Iota_Lib_CSharp_Api_IotaApi_FindTransactionsByAddresses">FindTransactionsByAddresses</a></td><td>
Finds the transactions by addresses.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Iota_Lib_CSharp_Api_IotaApi_FindTransactionsByApprovees">FindTransactionsByApprovees</a></td><td>
Finds the transactions by approvees.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Iota_Lib_CSharp_Api_IotaApi_FindTransactionsByBundles">FindTransactionsByBundles</a></td><td>
Finds the transactions by bundles.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Iota_Lib_CSharp_Api_IotaApi_FindTransactionsByDigests">FindTransactionsByDigests</a></td><td>
Finds the transactions by digests.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Iota_Lib_CSharp_Api_IotaCoreApi_GetBalances">GetBalances</a></td><td>
Gets the balances.
 (Inherited from <a href="T_Iota_Lib_CSharp_Api_IotaCoreApi">IotaCoreApi</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Iota_Lib_CSharp_Api_IotaApi_GetBundle">GetBundle</a></td><td>
This function returns the bundle which is associated with a transaction. Input can by any type of transaction (tail and non-tail). If there are conflicting bundles (because of a replay for example) it will return multiple bundles. It also does important validation checking (signatures, sum, order) to ensure that the correct bundle is returned.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/zdee4b3y" target="_blank">GetHashCode</a></td><td>
Serves as a hash function for a particular type.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Iota_Lib_CSharp_Api_IotaCoreApi_GetInclusionStates">GetInclusionStates</a></td><td>
Gets the inclusion states.
 (Inherited from <a href="T_Iota_Lib_CSharp_Api_IotaCoreApi">IotaCoreApi</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Iota_Lib_CSharp_Api_IotaApi_GetInputs">GetInputs</a></td><td>
Gets all possible inputs of a seed and returns them with the total balance. This is either done deterministically (by genearating all addresses until findTransactions is empty and doing getBalances), or by providing a key range to use for searching through.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Iota_Lib_CSharp_Api_IotaApi_GetLatestInclusion">GetLatestInclusion</a></td><td>
Gets the latest inclusion.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Iota_Lib_CSharp_Api_IotaCoreApi_GetNeighbors">GetNeighbors</a></td><td>
Gets the neighbors the node is connected to
 (Inherited from <a href="T_Iota_Lib_CSharp_Api_IotaCoreApi">IotaCoreApi</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Iota_Lib_CSharp_Api_IotaApi_GetNewAddress">GetNewAddress</a></td><td>
Generates a new address from a seed and returns the remainderAddress. This is either done deterministically, or by providing the index of the new remainderAddress</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Iota_Lib_CSharp_Api_IotaCoreApi_GetNodeInfo">GetNodeInfo</a></td><td>
Gets the node information.
 (Inherited from <a href="T_Iota_Lib_CSharp_Api_IotaCoreApi">IotaCoreApi</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Iota_Lib_CSharp_Api_IotaCoreApi_GetTips">GetTips</a></td><td>
Gets the tips.
 (Inherited from <a href="T_Iota_Lib_CSharp_Api_IotaCoreApi">IotaCoreApi</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Iota_Lib_CSharp_Api_IotaApi_GetTransactionsObjects">GetTransactionsObjects</a></td><td>
Gets the transactions objects.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Iota_Lib_CSharp_Api_IotaCoreApi_GetTransactionsToApprove">GetTransactionsToApprove</a></td><td>
Gets the transactions to approve.
 (Inherited from <a href="T_Iota_Lib_CSharp_Api_IotaCoreApi">IotaCoreApi</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Iota_Lib_CSharp_Api_IotaApi_GetTransfers">GetTransfers</a></td><td>
Gets the transfers which are associated with a seed. The transfers are determined by either calculating deterministically which addresses were already used, or by providing a list of indexes to get the transfers from.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Iota_Lib_CSharp_Api_IotaCoreApi_GetTrytes">GetTrytes</a></td><td>
Gets the raw transaction data (trytes) of a specific transaction. These trytes can then be easily converted into the actual transaction object using the constructor of Transaction
 (Inherited from <a href="T_Iota_Lib_CSharp_Api_IotaCoreApi">IotaCoreApi</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/dfwy45w9" target="_blank">GetType</a></td><td>
Gets the <a href="http://msdn2.microsoft.com/en-us/library/42892f65" target="_blank">Type</a> of the current instance.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Iota_Lib_CSharp_Api_IotaCoreApi_InterruptAttachingToTangle">InterruptAttachingToTangle</a></td><td>
Interrupts and completely aborts the attachToTangle process.
 (Inherited from <a href="T_Iota_Lib_CSharp_Api_IotaCoreApi">IotaCoreApi</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/57ctke0a" target="_blank">MemberwiseClone</a></td><td>
Creates a shallow copy of the current <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Iota_Lib_CSharp_Api_IotaApi_PrepareTransfers">PrepareTransfers</a></td><td>
Main purpose of this function is to get an array of transfer objects as input, and then prepare the transfer by generating the correct bundle, as well as choosing and signing the inputs if necessary (if it's a value transfer). The output of this function is an array of the raw transaction data (trytes)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Iota_Lib_CSharp_Api_IotaCoreApi_RemoveNeighbors">RemoveNeighbors</a></td><td>
Removes the neighbor(s) from the node.
 (Inherited from <a href="T_Iota_Lib_CSharp_Api_IotaCoreApi">IotaCoreApi</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Iota_Lib_CSharp_Api_IotaApi_ReplayBundle">ReplayBundle</a></td><td>
Replays the bundle.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Iota_Lib_CSharp_Api_IotaApi_SendTransfer">SendTransfer</a></td><td>
Wrapper function that basically does prepareTransfers, as well as attachToTangle and finally, it broadcasts and stores the transactions locally.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Iota_Lib_CSharp_Api_IotaApi_SendTrytes">SendTrytes</a></td><td>
Sends the trytes.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Iota_Lib_CSharp_Api_IotaCoreApi_StoreTransactions">StoreTransactions</a></td><td>
Stores the specified transactions in trytes into the local storage. The trytes to be used for this call are returned by attachToTangle.
 (Inherited from <a href="T_Iota_Lib_CSharp_Api_IotaCoreApi">IotaCoreApi</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/7bxwbwt2" target="_blank">ToString</a></td><td>
Returns a string that represents the current object.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr></table>&nbsp;
<a href="#iotaapi-methods">Back to Top</a>

## See Also


#### Reference
<a href="T_Iota_Lib_CSharp_Api_IotaApi">IotaApi Class</a><br /><a href="N_Iota_Lib_CSharp_Api">Iota.Lib.CSharp.Api Namespace</a><br />