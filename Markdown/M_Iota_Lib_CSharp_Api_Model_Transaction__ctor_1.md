# Transaction Constructor (String, ICurl)
 

Initializes a new instance of the <a href="T_Iota_Lib_CSharp_Api_Model_Transaction">Transaction</a> class.

**Namespace:**&nbsp;<a href="N_Iota_Lib_CSharp_Api_Model">Iota.Lib.CSharp.Api.Model</a><br />**Assembly:**&nbsp;IotaApi (in IotaApi.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

**C#**<br />
``` C#
public Transaction(
	string trytes,
	ICurl curl
)
```


#### Parameters
&nbsp;<dl><dt>trytes</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The trytes representing the transaction</dd><dt>curl</dt><dd>Type: <a href="T_Iota_Lib_CSharp_Api_Utils_ICurl">Iota.Lib.CSharp.Api.Utils.ICurl</a><br />The curl implementation.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td><a href="http://msdn2.microsoft.com/en-us/library/3w1b3114" target="_blank">ArgumentException</a></td><td>trytes must non-null or position " + i + "must not be '9'</td></tr></table>

## See Also


#### Reference
<a href="T_Iota_Lib_CSharp_Api_Model_Transaction">Transaction Class</a><br /><a href="Overload_Iota_Lib_CSharp_Api_Model_Transaction__ctor">Transaction Overload</a><br /><a href="N_Iota_Lib_CSharp_Api_Model">Iota.Lib.CSharp.Api.Model Namespace</a><br />