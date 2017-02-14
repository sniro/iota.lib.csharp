# IGenericIotaCoreApi.RequestAsync(*TRequest*, *TResponse*) Method 
 

Requests the specified request asynchronously

**Namespace:**&nbsp;<a href="N_Iota_Lib_CSharp_Api_Core">Iota.Lib.CSharp.Api.Core</a><br />**Assembly:**&nbsp;IotaApi (in IotaApi.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

**C#**<br />
``` C#
void RequestAsync<TRequest, TResponse>(
	TRequest request,
	Action<TResponse> responseAction
)
where TResponse : new()

```


#### Parameters
&nbsp;<dl><dt>request</dt><dd>Type: *TRequest*<br />The request.</dd><dt>responseAction</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/018hxwa8" target="_blank">System.Action</a>(*TResponse*)<br />The response action.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>TRequest</dt><dd>The type of the request.</dd><dt>TResponse</dt><dd>The type of the response.</dd></dl>

## See Also


#### Reference
<a href="T_Iota_Lib_CSharp_Api_Core_IGenericIotaCoreApi">IGenericIotaCoreApi Interface</a><br /><a href="N_Iota_Lib_CSharp_Api_Core">Iota.Lib.CSharp.Api.Core Namespace</a><br />