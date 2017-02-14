# Bundle Class
 

This class represents a Bundle, a set of transactions


## Inheritance Hierarchy
<a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />&nbsp;&nbsp;Iota.Lib.CSharp.Api.Model.Bundle<br />
**Namespace:**&nbsp;<a href="N_Iota_Lib_CSharp_Api_Model">Iota.Lib.CSharp.Api.Model</a><br />**Assembly:**&nbsp;IotaApi (in IotaApi.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

**C#**<br />
``` C#
public class Bundle : IComparable, IComparable<Bundle>
```

The Bundle type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Iota_Lib_CSharp_Api_Model_Bundle__ctor">Bundle()</a></td><td>
Initializes a new instance of the Bundle class without transactions.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Iota_Lib_CSharp_Api_Model_Bundle__ctor_1">Bundle(List(Transaction), Int32)</a></td><td>
Initializes a new instance of the Bundle class.</td></tr></table>&nbsp;
<a href="#bundle-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Iota_Lib_CSharp_Api_Model_Bundle_Item">Item</a></td><td>
Gets the <a href="T_Iota_Lib_CSharp_Api_Model_Transaction">Transaction</a> at the specified index.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Iota_Lib_CSharp_Api_Model_Bundle_Length">Length</a></td><td>
Gets or sets the length of the bundle</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Iota_Lib_CSharp_Api_Model_Bundle_Transactions">Transactions</a></td><td>
Gets or sets the transactions.</td></tr></table>&nbsp;
<a href="#bundle-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Iota_Lib_CSharp_Api_Model_Bundle_addEntry">addEntry</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Iota_Lib_CSharp_Api_Model_Bundle_addTrytes">addTrytes</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Iota_Lib_CSharp_Api_Model_Bundle_CompareTo_1">CompareTo(Object)</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Iota_Lib_CSharp_Api_Model_Bundle_CompareTo">CompareTo(Bundle)</a></td><td>
Compares the current object with another object of the same type.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/bsc2ak47" target="_blank">Equals</a></td><td>
Determines whether the specified <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a> is equal to the current <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Iota_Lib_CSharp_Api_Model_Bundle_finalize">finalize()</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Iota_Lib_CSharp_Api_Model_Bundle_finalize_1">finalize(ICurl)</a></td><td /></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/4k87zsw7" target="_blank">Finalize</a></td><td>
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/zdee4b3y" target="_blank">GetHashCode</a></td><td>
Serves as a hash function for a particular type.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/dfwy45w9" target="_blank">GetType</a></td><td>
Gets the <a href="http://msdn2.microsoft.com/en-us/library/42892f65" target="_blank">Type</a> of the current instance.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/57ctke0a" target="_blank">MemberwiseClone</a></td><td>
Creates a shallow copy of the current <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Iota_Lib_CSharp_Api_Model_Bundle_normalizedBundle">normalizedBundle</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/7bxwbwt2" target="_blank">ToString</a></td><td>
Returns a string that represents the current object.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr></table>&nbsp;
<a href="#bundle-class">Back to Top</a>

## See Also


#### Reference
<a href="N_Iota_Lib_CSharp_Api_Model">Iota.Lib.CSharp.Api.Model Namespace</a><br />