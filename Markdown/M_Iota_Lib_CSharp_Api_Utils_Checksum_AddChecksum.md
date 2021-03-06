# Checksum.AddChecksum Method 
 

Adds the checksum to the specified address

**Namespace:**&nbsp;<a href="N_Iota_Lib_CSharp_Api_Utils">Iota.Lib.CSharp.Api.Utils</a><br />**Assembly:**&nbsp;IotaApi (in IotaApi.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

**C#**<br />
``` C#
public static string AddChecksum(
	this string address
)
```


#### Parameters
&nbsp;<dl><dt>address</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />An address without checksum</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">String</a><br />The address with the appended checksum

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">String</a>. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="http://msdn.microsoft.com/en-us/library/bb384936.aspx">Extension Methods (Visual Basic)</a> or <a href="http://msdn.microsoft.com/en-us/library/bb383977.aspx">Extension Methods (C# Programming Guide)</a>.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td><a href="T_Iota_Lib_CSharp_Api_Exception_InvalidAddressException">InvalidAddressException</a></td><td>is thrown when an invalid address is provided</td></tr></table>

## See Also


#### Reference
<a href="T_Iota_Lib_CSharp_Api_Utils_Checksum">Checksum Class</a><br /><a href="N_Iota_Lib_CSharp_Api_Utils">Iota.Lib.CSharp.Api.Utils Namespace</a><br />