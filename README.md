#### Varnish three letter acronyms

Three letter acronyms used inside Varnish Cache.

Use the following command to dig out acronyms.

```shell
$> git clone https://github.com/varnish/Varnish-Cache.git
$> cd Varnish-Cache
$> find * -type f -exec grep -E "^V\w{2,9}_" {} \; | awk '{print substr($0, 0, index($0, "_")-1)}' | sort | uniq
```


| Acronym  	|  Phrase 	|  Description 	|
|---	|---	|---	|
| V1D			| Varnish HTTP 1 Deliver				|				|
| V1F			| Varnish HTTP 1 Fetch				|				|
| V1L			| Varnish HTTP 1 Line			|				|
| V1P			| Varnish HTTP 1 Pipe				|				|
| VARNISH		|				|				|
| VAS			| Varnish Assert				|				|
| VAV			| Varnish Arguments Vector				|				|
| VB64			| Varnish Base64				|				|
| VBE			| Varnish Backend			|				|
| VBF			| Varnish Backend Polling				|				|
| VBO			|				|				|
| VBP			|				|				|
| VBT			|				|				|
| VCA			| Varnish Connection Acceptor				|				|
| VCC			| VCL to C Compiler				|				|
| VCL			| Varnish Configuration Language				|				|
| VCLI			| Varnish Command Line Interface				|				|
| VCLS			| Varnish Command Line Serve				|				|
| VCS			| Varnish Cache			|				|
| VCT			| Varnish CType			|				|
| VDD			| Varnish (Core) Developer Day |				|
| VDI			|				|				|
| VDP			|				|				|
| VED			|				|				|
| VEP			|				|				|
| VEV			| Varnish EVent				|				|
| VFIL			| Varnish File				|				|
| VFP			| Varnish Fetch Process			|				|
| VGZ			| Varnish Cache Gzip				|				|
| VGB			| Varnish Governing Board |				|
| VGC			| Varnish Generate Code				|				|
| VIN			| Varnish Instance Naming 				|				|
| VJ			|				|				|
| VLU			| Varnish Line Up				|				|
| VRE			| Varnish Regular-Expression				|				|
| VRT			| Varnish Run Time				|				|
| VRY			| VaRY (HTTP headers)				|				|
| VMOD			| Varnish Module			|				|
| VNUM			|				|				|
| VPF			|				|				|
| VPX			|				|				|
| VRB			|				|				|
| VRE			|				|				|
| VRG			|				|				|
| VRND			|				|				|
| VRT			|				|				|
| VRTPRIV		|				|				|
| VRY			|				|				|
| VSA			|				|				|
| VSB			|	Varnish String Buffer			|				|
| VSC			|	Varnish Statistics Counter			|				|
| VSL			|	Varnish Shared Memory Log			|				|
| VSLQ			|				|				|
| VSLb			|				|				|
| VSM			|				|				|
| VSS			|	Varnish Session Stuff			|				|
| VSUB			|				|				|
| VTAILQ		|				|				|
| VTC			| Varnish Test Code				|				|
| VTLA		| Varnish Three Letter Acronym				|				|
| VTCP			|				|				|
| VTIM			|				|				|
| VUT			|				|				|
| VUG			|	Varnish User Group			|				|
| VXID			|				|				|
| VWx			|	Varnish Waiter 'x'			|				|
| VWE			|	Varnish Waiter Epoll			|				|
| VWK			|	Varnish Waiter Kqueue			|				|
| VWP			|	Varnish Waiter Poll			|				|
| VWS			|	Varnish Waiter Solaris			|				|
