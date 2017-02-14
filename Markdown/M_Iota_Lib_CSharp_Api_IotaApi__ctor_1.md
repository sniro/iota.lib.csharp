# IotaApi Constructor (String, Int32, ICurl)
 

Creates an api object that uses the specified connection settings to connect to a node

**Namespace:**&nbsp;<a href="N_Iota_Lib_CSharp_Api">Iota.Lib.CSharp.Api</a><br />**Assembly:**&nbsp;IotaApi (in IotaApi.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

**C#**<br />
``` C#
public IotaApi(
	string host,
	int port,
	ICurl curl
)
```


#### Parameters
&nbsp;<dl><dt>host</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />hostname or API address of a node to interact with</dd><dt>port</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/td2s409d" target="_blank">System.Int32</a><br />tcp/udp port</dd><dt>curl</dt><dd>Type: <a href="T_Iota_Lib_CSharp_Api_Utils_ICurl">Iota.Lib.CSharp.Api.Utils.ICurl</a><br />a custom curl implementation to be used to perform the pow. Use the other constructor in order to use the default curl implementation provided by the library</dd></dl>

## See Also


#### Reference
<a href="T_Iota_Lib_CSharp_Api_IotaApi">IotaApi Class</a><br /><a href="Overload_Iota_Lib_CSharp_Api_IotaApi__ctor">IotaApi Overload</a><br /><a href="N_Iota_Lib_CSharp_Api">Iota.Lib.CSharp.Api Namespace</a><br />