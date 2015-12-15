#### Varnish three letter acronyms

Three letter acronyms used inside Varnish Cache.

Use the following command to dig out acronyms.

```shell
$> git clone https://github.com/varnish/Varnish-Cache.git
$> cd Varnish-Cache
$> find * -type f -exec grep -E "^V\w{2,9}_" {} \; | awk '{print substr($0, 0, index($0, "_")-1)}' | sort | uniq
```

#### List

| Acronym  	|  Phrase 	|  Description 	|
|---	|---	|---	|
| V1D			|				|				|
| V1F			|				|				|
| V1L			|				|				|
| V1P			|				|				|
| VARNISH		|				|				|
| VAS			|				|				|
| VAV			|				|				|
| VB64			|				|				|
| VBE			|				|				|
| VBF			|				|				|
| VBO			|				|				|
| VBP			|				|				|
| VBT			|				|				|
| VCA			|				|				|
| VCC			|				|				|
| VCL			|				|				|
| VCLI			|				|				|
| VCLS			|				|				|
| VCS			|				|				|
| VDI			|				|				|
| VDP			|				|				|
| VED			|				|				|
| VEP			|				|				|
| VERS			|				|				|
| VFIL			|				|				|
| VFP			|				|				|
| VGZ			|				|				|
| VIN			|				|				|
| VJ			|				|				|
| VLU			|				|				|
| VMOD			|				|				|
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
| VSB			|				|				|
| VSC			|				|				|
| VSL			|				|				|
| VSLQ			|				|				|
| VSLb			|				|				|
| VSM			|				|				|
| VSS			|				|				|
| VSUB			|				|				|
| VTAILQ		|				|				|
| VTC			|				|				|
| VTCP			|				|				|
| VTIM			|				|				|
| VUT			|				|				|
| VXID			|				|				|
