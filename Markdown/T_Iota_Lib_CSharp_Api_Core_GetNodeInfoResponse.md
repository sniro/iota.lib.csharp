# GetNodeInfoResponse Class
 

This class represents the response of <a href="T_Iota_Lib_CSharp_Api_Core_GetNodeInfoRequest">GetNodeInfoRequest</a>


## Inheritance Hierarchy
<a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />&nbsp;&nbsp;<a href="T_Iota_Lib_CSharp_Api_Core_IotaResponse">Iota.Lib.CSharp.Api.Core.IotaResponse</a><br />&nbsp;&nbsp;&nbsp;&nbsp;Iota.Lib.CSharp.Api.Core.GetNodeInfoResponse<br />
**Namespace:**&nbsp;<a href="N_Iota_Lib_CSharp_Api_Core">Iota.Lib.CSharp.Api.Core</a><br />**Assembly:**&nbsp;IotaApi (in IotaApi.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

**C#**<br />
``` C#
public class GetNodeInfoResponse : IotaResponse
```

The GetNodeInfoResponse type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Iota_Lib_CSharp_Api_Core_GetNodeInfoResponse__ctor">GetNodeInfoResponse</a></td><td>
Initializes a new instance of the GetNodeInfoResponse class</td></tr></table>&nbsp;
<a href="#getnodeinforesponse-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Iota_Lib_CSharp_Api_Core_GetNodeInfoResponse_AppName">AppName</a></td><td>
Name of the IOTA software you're currently using (IRI stands for Initial Reference Implementation).</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Iota_Lib_CSharp_Api_Core_GetNodeInfoResponse_AppVersion">AppVersion</a></td><td>
The version of the IOTA software you're currently running.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Iota_Lib_CSharp_Api_Core_IotaResponse_Duration">Duration</a></td><td>
Gets or sets the duration.
 (Inherited from <a href="T_Iota_Lib_CSharp_Api_Core_IotaResponse">IotaResponse</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Iota_Lib_CSharp_Api_Core_GetNodeInfoResponse_JreAvailableProcessors">JreAvailableProcessors</a></td><td>
Available cores on your machine for JRE.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Iota_Lib_CSharp_Api_Core_GetNodeInfoResponse_JreFreeMemory">JreFreeMemory</a></td><td>
The amount of free memory in the Java Virtual Machine.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Iota_Lib_CSharp_Api_Core_GetNodeInfoResponse_JreMaxMemory">JreMaxMemory</a></td><td>
The maximum amount of memory that the Java virtual machine will attempt to use.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Iota_Lib_CSharp_Api_Core_GetNodeInfoResponse_JreTotalMemory">JreTotalMemory</a></td><td>
The total amount of memory in the Java virtual machine.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Iota_Lib_CSharp_Api_Core_GetNodeInfoResponse_JreVersion">JreVersion</a></td><td /></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Iota_Lib_CSharp_Api_Core_GetNodeInfoResponse_LatestMilestone">LatestMilestone</a></td><td>
Latest milestone that was signed off by the coordinator.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Iota_Lib_CSharp_Api_Core_GetNodeInfoResponse_LatestMilestoneIndex">LatestMilestoneIndex</a></td><td>
Index of the latest milestone.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Iota_Lib_CSharp_Api_Core_GetNodeInfoResponse_LatestSolidSubtangleMilestone">LatestSolidSubtangleMilestone</a></td><td>
The latest milestone which is solid and is used for sending transactions. For a milestone to become solid your local node must basically approve the subtangle of coordinator-approved transactions, and have a consistent view of all referenced transactions.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Iota_Lib_CSharp_Api_Core_GetNodeInfoResponse_LatestSolidSubtangleMilestoneIndex">LatestSolidSubtangleMilestoneIndex</a></td><td>
Index of the latest solid subtangle.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Iota_Lib_CSharp_Api_Core_GetNodeInfoResponse_Neighbors">Neighbors</a></td><td>
Number of neighbors you are directly connected with.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Iota_Lib_CSharp_Api_Core_GetNodeInfoResponse_PacketsQueueSize">PacketsQueueSize</a></td><td>
Packets which are currently queued up</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Iota_Lib_CSharp_Api_Core_GetNodeInfoResponse_Time">Time</a></td><td>
Current UNIX timestamp.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Iota_Lib_CSharp_Api_Core_GetNodeInfoResponse_Tips">Tips</a></td><td>
Number of tips in the network.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Iota_Lib_CSharp_Api_Core_GetNodeInfoResponse_TransactionsToRequest">TransactionsToRequest</a></td><td>
Transactions to request during syncing process.</td></tr></table>&nbsp;
<a href="#getnodeinforesponse-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/bsc2ak47" target="_blank">Equals</a></td><td>
Determines whether the specified <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a> is equal to the current <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/4k87zsw7" target="_blank">Finalize</a></td><td>
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/zdee4b3y" target="_blank">GetHashCode</a></td><td>
Serves as a hash function for a particular type.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/dfwy45w9" target="_blank">GetType</a></td><td>
Gets the <a href="http://msdn2.microsoft.com/en-us/library/42892f65" target="_blank">Type</a> of the current instance.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/57ctke0a" target="_blank">MemberwiseClone</a></td><td>
Creates a shallow copy of the current <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Iota_Lib_CSharp_Api_Core_GetNodeInfoResponse_ToString">ToString</a></td><td>
Returns a <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">String</a> that represents this instance.
 (Overrides <a href="http://msdn2.microsoft.com/en-us/library/7bxwbwt2" target="_blank">Object.ToString()</a>.)</td></tr></table>&nbsp;
<a href="#getnodeinforesponse-class">Back to Top</a>

## See Also


#### Reference
<a href="N_Iota_Lib_CSharp_Api_Core">Iota.Lib.CSharp.Api.Core Namespace</a><br /><a href="T_Iota_Lib_CSharp_Api_Core_IotaResponse">Iota.Lib.CSharp.Api.Core.IotaResponse</a><br />