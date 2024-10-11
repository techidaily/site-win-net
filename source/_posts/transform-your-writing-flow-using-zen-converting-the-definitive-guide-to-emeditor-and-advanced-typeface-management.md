---
title: "Transform Your Writing Flow Using Zen-Converting: The Definitive Guide to EmEditor and Advanced Typeface Management"
date: 2024-10-09T03:14:15.120Z
updated: 2024-10-11T10:08:01.388Z
tags:
  - product
categories:
  - emeditor
thumbnail: https://thmb.techidaily.com/09d90f71aa46b1fd9d4bcc7810bb203ff9683f8d93c042d20e109ab131454cc4.jpg
---

## Transform Your Writing Flow Using Zen-Converting: The Definitive Guide to EmEditor and Advanced Typeface Management

Viewing 4 posts - 1 through 4 (of 4 total)

* Author  
Posts
* December 18, 2009 at 7:35 am [#7972](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/f4134e2e546d7b8d227e6793a447fb97?s=80&d=identicon&r=g)robben](https://www.emeditor.com/forums/users/robben/ "View robben's profile")  
Member  
    
	function objectTag() {  
		var start= document.selection.GetActivePointY(true);  
		document.selection.SelectLine();  
		var selectionStr = document.selection.Text;  
		var selection = selectionStr.replace(/^[stn]+/m, '').replace(/[stn]+$/m, '')  
		var	text = zen_coding.parseIntoTree(selection, zen_coding.getEditorType())  
		if (!text)  
			return ''  
		text = text.toString(true)  
		text = text.replace("|", '$cursor

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>
);  
		text = text.replace(/|/gm, '')  
		var padding = zen_coding.getCurrentLinePadding();  
		text = padding + text.replace(/n/g, "n" + padding);  
		text += "n";  
		document.write(text);  
		var end=document.selection.GetActivePointY(true);  
		var length=end-start+1;  
		while(length--){  
			var tmp=document.GetLine(start);  
			var tnum=tmp.indexOf('$cursor

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>
);  
			if (tnum > -1) {  
					document.selection.SetActivePoint(true,1,start);  
					document.selection.Replace('$cursor

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>
,'',eeFindReplaceCase);  
					break;  

			start++;  

	var zen_settings = {  
		indentation: 't',  
		css: {  
			snippets: {  
				"@i": "@import url(|);",  
				"@m": "@media print {nt|n}",  
				"@f": "@font-face {ntfont-family:|;ntsrc:url(|);n}",  
				"!": "!important",  
				"pos": "position:|;",  
				"pos:s": "position:static;",  
				"pos:a": "position:absolute;",  
				"pos:r": "position:relative;",  
				"pos:f": "position:fixed;",  
				"t": "top:|;",  
				"t:a": "top:auto;",  
				"r": "right:|;",  
				"r:a": "right:auto;",  
				"b": "bottom:|;",  
				"b:a": "bottom:auto;",  
				"l": "left:|;",  
				"l:a": "left:auto;",  
				"z": "z-index:|;",  
				"z:a": "z-index:auto;",  
				"fl": "float:|;",  
				"fl:n": "float:none;",  
				"fl:l": "float:left;",  
				"fl:r": "float:right;",  
				"cl": "clear:|;",  
				"cl:n": "clear:none;",  
				"cl:l": "clear:left;",  
				"cl:r": "clear:right;",  
				"cl:b": "clear:both;",  
				"d": "display:|;",  
				"d:n": "display:none;",  
				"d:b": "display:block;",  
				"d:ib": "display:inline;",  
				"d:li": "display:list-item;",  
				"d:ri": "display:run-in;",  
				"d:cp": "display:compact;",  
				"d:tb": "display:table;",  
				"d:itb": "display:inline-table;",  
				"d:tbcp": "display:table-caption;",  
				"d:tbcl": "display:table-column;",  
				"d:tbclg": "display:table-column-group;",  
				"d:tbhg": "display:table-header-group;",  
				"d:tbfg": "display:table-footer-group;",  
				"d:tbr": "display:table-row;",  
				"d:tbrg": "display:table-row-group;",  
				"d:tbc": "display:table-cell;",  
				"d:rb": "display:ruby;",  
				"d:rbb": "display:ruby-base;",  
				"d:rbbg": "display:ruby-base-group;",  
				"d:rbt": "display:ruby-text;",  
				"d:rbtg": "display:ruby-text-group;",  
				"v": "visibility:|;",  
				"v:v": "visibility:visible;",  
				"v:h": "visibility:hidden;",  
				"v:c": "visibility:collapse;",  
				"ov": "overflow:|;",  
				"ov:v": "overflow:visible;",  
				"ov:h": "overflow:hidden;",  
				"ov:s": "overflow:scroll;",  
				"ov:a": "overflow:auto;",  
				"ovx": "overflow-x:|;",  
				"ovx:v": "overflow-x:visible;",  
				"ovx:h": "overflow-x:hidden;",  
				"ovx:s": "overflow-x:scroll;",  
				"ovx:a": "overflow-x:auto;",  
				"ovy": "overflow-y:|;",  
				"ovy:v": "overflow-y:visible;",  
				"ovy:h": "overflow-y:hidden;",  
				"ovy:s": "overflow-y:scroll;",  
				"ovy:a": "overflow-y:auto;",  
				"ovs": "overflow-style:|;",  
				"ovs:a": "overflow-style:auto;",  
				"ovs:s": "overflow-style:scrollbar;",  
				"ovs:p": "overflow-style:panner;",  
				"ovs:m": "overflow-style:move;",  
				"ovs:mq": "overflow-style:marquee;",  
				"zoo": "zoom:1;",  
				"cp": "clip:|;",  
				"cp:a": "clip:auto;",  
				"cp:r": "clip:rect(|);",  
				"bxz": "box-sizing:|;",  
				"bxz:cb": "box-sizing:content-box;",  
				"bxz:bb": "box-sizing:border-box;",  
				"bxsh": "box-shadow:|;",  
				"bxsh:n": "box-shadow:none;",  
				"bxsh:w": "-webkit-box-shadow:0 0 0 #000;",  
				"bxsh:m": "-moz-box-shadow:0 0 0 0 #000;",  
				"m": "margin:|;",  
				"m:a": "margin:auto;",  
				"m:0": "margin:0;",  
				"m:2": "margin:0 0;",  
				"m:3": "margin:0 0 0;",  
				"m:4": "margin:0 0 0 0;",  
				"mt": "margin-top:|;",  
				"mt:a": "margin-top:auto;",  
				"mr": "margin-right:|;",  
				"mr:a": "margin-right:auto;",  
				"mb": "margin-bottom:|;",  
				"mb:a": "margin-bottom:auto;",  
				"ml": "margin-left:|;",  
				"ml:a": "margin-left:auto;",  
				"p": "padding:|;",  
				"p:0": "padding:0;",  
				"p:2": "padding:0 0;",  
				"p:3": "padding:0 0 0;",  
				"p:4": "padding:0 0 0 0;",  
				"pt": "padding-top:|;",  
				"pr": "padding-right:|;",  
				"pb": "padding-bottom:|;",  
				"pl": "padding-left:|;",  
				"w": "width:|;",  
				"w:a": "width:auto;",  
				"h": "height:|;",  
				"h:a": "height:auto;",  
				"maw": "max-width:|;",  
				"maw:n": "max-width:none;",  
				"mah": "max-height:|;",  
				"mah:n": "max-height:none;",  
				"miw": "min-width:|;",  
				"mih": "min-height:|;",  
				"o": "outline:|;",  
				"o:n": "outline:none;",  
				"oo": "outline-offset:|;",  
				"ow": "outline-width:|;",  
				"os": "outline-style:|;",  
				"oc": "outline-color:#000;",  
				"oc:i": "outline-color:invert;",  
				"bd": "border:|;",  
				"bd+": "border:1px solid #000;",  
				"bd:n": "border:none;",  
				"bdbk": "border-break:|;",  
				"bdbk:c": "border-break:close;",  
				"bdcl": "border-collapse:|;",  
				"bdcl:c": "border-collapse:collapse;",  
				"bdcl:s": "border-collapse:separate;",  
				"bdc": "border-color:#000;",  
				"bdi": "border-image:url(|);",  
				"bdi:n": "border-image:none;",  
				"bdi:w": "-webkit-border-image:url(|) 0 0 0 0 stretch stretch;",  
				"bdi:m": "-moz-border-image:url(|) 0 0 0 0 stretch stretch;",  
				"bdti": "border-top-image:url(|);",  
				"bdti:n": "border-top-image:none;",  
				"bdri": "border-right-image:url(|);",  
				"bdri:n": "border-right-image:none;",  
				"bdbi": "border-bottom-image:url(|);",  
				"bdbi:n": "border-bottom-image:none;",  
				"bdli": "border-left-image:url(|);",  
				"bdli:n": "border-left-image:none;",  
				"bdci": "border-corner-image:url(|);",  
				"bdci:n": "border-corner-image:none;",  
				"bdci:c": "border-corner-image:continue;",  
				"bdtli": "border-top-left-image:url(|);",  
				"bdtli:n": "border-top-left-image:none;",  
				"bdtli:c": "border-top-left-image:continue;",  
				"bdtri": "border-top-right-image:url(|);",  
				"bdtri:n": "border-top-right-image:none;",  
				"bdtri:c": "border-top-right-image:continue;",  
				"bdbri": "border-bottom-right-image:url(|);",  
				"bdbri:n": "border-bottom-right-image:none;",  
				"bdbri:c": "border-bottom-right-image:continue;",  
				"bdbli": "border-bottom-left-image:url(|);",  
				"bdbli:n": "border-bottom-left-image:none;",  
				"bdbli:c": "border-bottom-left-image:continue;",  
				"bdf": "border-fit:|;",  
				"bdf:c": "border-fit:clip;",  
				"bdf:r": "border-fit:repeat;",  
				"bdf:sc": "border-fit:scale;",  
				"bdf:st": "border-fit:stretch;",  
				"bdf:ow": "border-fit:overwrite;",  
				"bdf:of": "border-fit:overflow;",  
				"bdf:sp": "border-fit:space;",  
				"bdl": "border-length:|;",  
				"bdl:a": "border-length:auto;",  
				"bdsp": "border-spacing:|;",  
				"bds": "border-style:|;",  
				"bds:n": "border-style:none;",  
				"bds:h": "border-style:hidden;",  
				"bds:dt": "border-style:dotted;",  
				"bds:ds": "border-style:dashed;",  
				"bds:s": "border-style:solid;",  
				"bds:db": "border-style:double;",  
				"bds:dtds": "border-style:dot-dash;",  
				"bds:dtdtds": "border-style:dot-dot-dash;",  
				"bds:w": "border-style:wave;",  
				"bds:g": "border-style:groove;",  
				"bds:r": "border-style:ridge;",  
				"bds:i": "border-style:inset;",  
				"bds:o": "border-style:outset;",  
				"bdw": "border-width:|;",  
				"bdt": "border-top:|;",  
				"bdt+": "border-top:1px solid #000;",  
				"bdt:n": "border-top:none;",  
				"bdtw": "border-top-width:|;",  
				"bdts": "border-top-style:|;",  
				"bdts:n": "border-top-style:none;",  
				"bdtc": "border-top-color:#000;",  
				"bdr": "border-right:|;",  
				"bdr+": "border-right:1px solid #000;",  
				"bdr:n": "border-right:none;",  
				"bdrw": "border-right-width:|;",  
				"bdrs": "border-right-style:|;",  
				"bdrs:n": "border-right-style:none;",  
				"bdrc": "border-right-color:#000;",  
				"bdb": "border-bottom:|;",  
				"bdb+": "border-bottom:1px solid #000;",  
				"bdb:n": "border-bottom:none;",  
				"bdbw": "border-bottom-width:|;",  
				"bdbs": "border-bottom-style:|;",  
				"bdbs:n": "border-bottom-style:none;",  
				"bdbc": "border-bottom-color:#000;",  
				"bdl": "border-left:|;",  
				"bdl+": "border-left:1px solid #000;",  
				"bdl:n": "border-left:none;",  
				"bdlw": "border-left-width:|;",  
				"bdls": "border-left-style:|;",  
				"bdls:n": "border-left-style:none;",  
				"bdlc": "border-left-color:#000;",  
				"bdrs": "border-radius:|;",  
				"bdtrrs": "border-top-right-radius:|;",  
				"bdtlrs": "border-top-left-radius:|;",  
				"bdbrrs": "border-bottom-right-radius:|;",  
				"bdblrs": "border-bottom-left-radius:|;",  
				"bg": "background:|;",  
				"bg+": "background:#FFF url(|) 0 0 no-repeat;",  
				"bg:n": "background:none;",  
				"bg:ie": "filter:progid:DXImageTransform.Microsoft.AlphaImageLoader(src='|x.png');",  
				"bgc": "background-color:#FFF;",  
				"bgi": "background-image:url(|);",  
				"bgi:n": "background-image:none;",  
				"bgr": "background-repeat:|;",  
				"bgr:n": "background-repeat:no-repeat;",  
				"bgr:x": "background-repeat:repeat-x;",  
				"bgr:y": "background-repeat:repeat-y;",  
				"bga": "background-attachment:|;",  
				"bga:f": "background-attachment:fixed;",  
				"bga:s": "background-attachment:scroll;",  
				"bgp": "background-position:0 0;",  
				"bgpx": "background-position-x:|;",  
				"bgpy": "background-position-y:|;",  
				"bgbk": "background-break:|;",  
				"bgbk:bb": "background-break:bounding-box;",  
				"bgbk:eb": "background-break:each-box;",  
				"bgbk:c": "background-break:continuous;",  
				"bgcp": "background-clip:|;",  
				"bgcp:bb": "background-clip:border-box;",  
				"bgcp:pb": "background-clip:padding-box;",  
				"bgcp:cb": "background-clip:content-box;",  
				"bgcp:nc": "background-clip:no-clip;",  
				"bgo": "background-origin:|;",  
				"bgo:pb": "background-origin:padding-box;",  
				"bgo:bb": "background-origin:border-box;",  
				"bgo:cb": "background-origin:content-box;",  
				"bgz": "background-size:|;",  
				"bgz:a": "background-size:auto;",  
				"bgz:ct": "background-size:contain;",  
				"bgz:cv": "background-size:cover;",  
				"c": "color:#000;",  
				"tbl": "table-layout:|;",  
				"tbl:a": "table-layout:auto;",  
				"tbl:f": "table-layout:fixed;",  
				"cps": "caption-side:|;",  
				"cps:t": "caption-side:top;",  
				"cps:b": "caption-side:bottom;",  
				"ec": "empty-cells:|;",  
				"ec:s": "empty-cells:show;",  
				"ec:h": "empty-cells:hide;",  
				"lis": "list-style:|;",  
				"lis:n": "list-style:none;",  
				"lisp": "list-style-position:|;",  
				"lisp:i": "list-style-position:inside;",  
				"lisp:o": "list-style-position:outside;",  
				"list": "list-style-type:|;",  
				"list:n": "list-style-type:none;",  
				"list:d": "list-style-type:disc;",  
				"list:c": "list-style-type:circle;",  
				"list:s": "list-style-type:square;",  
				"list:dc": "list-style-type:decimal;",  
				"list:dclz": "list-style-type:decimal-leading-zero;",  
				"list:lr": "list-style-type:lower-roman;",  
				"list:ur": "list-style-type:upper-roman;",  
				"lisi": "list-style-image:|;",  
				"lisi:n": "list-style-image:none;",  
				"q": "quotes:|;",  
				"q:n": "quotes:none;",  
				"q:ru": "quotes:'0AB' '0BB' '201E' '201C';",  
				"q:en": "quotes:'201C' '201D' '2018' '2019';",  
				"ct": "content:|;",  
				"ct:n": "content:normal;",  
				"ct:oq": "content:open-quote;",  
				"ct:noq": "content:no-open-quote;",  
				"ct:cq": "content:close-quote;",  
				"ct:ncq": "content:no-close-quote;",  
				"ct:a": "content:attr(|);",  
				"ct:c": "content:counter(|);",  
				"ct:cs": "content:counters(|);",  
				"coi": "counter-increment:|;",  
				"cor": "counter-reset:|;",  
				"va": "vertical-align:|;",  
				"va:sup": "vertical-align:super;",  
				"va:t": "vertical-align:top;",  
				"va:tt": "vertical-align:text-top;",  
				"va:m": "vertical-align:middle;",  
				"va:bl": "vertical-align:baseline;",  
				"va:b": "vertical-align:bottom;",  
				"va:tb": "vertical-align:text-bottom;",  
				"va:sub": "vertical-align:sub;",  
				"ta": "text-align:|;",  
				"ta:l": "text-align:left;",  
				"ta:c": "text-align:center;",  
				"ta:r": "text-align:right;",  
				"tal": "text-align-last:|;",  
				"tal:a": "text-align-last:auto;",  
				"tal:l": "text-align-last:left;",  
				"tal:c": "text-align-last:center;",  
				"tal:r": "text-align-last:right;",  
				"td": "text-decoration:|;",  
				"td:n": "text-decoration:none;",  
				"td:u": "text-decoration:underline;",  
				"td:o": "text-decoration:overline;",  
				"td:l": "text-decoration:line-through;",  
				"te": "text-emphasis:|;",  
				"te:n": "text-emphasis:none;",  
				"te:ac": "text-emphasis:accent;",  
				"te:dt": "text-emphasis:dot;",  
				"te:c": "text-emphasis:circle;",  
				"te:ds": "text-emphasis:disc;",  
				"te:b": "text-emphasis:before;",  
				"te:a": "text-emphasis:after;",  
				"th": "text-height:|;",  
				"th:a": "text-height:auto;",  
				"th:f": "text-height:font-size;",  
				"th:t": "text-height:text-size;",  
				"th:m": "text-height:max-size;",  
				"ti": "text-indent:|;",  
				"ti:-": "text-indent:-9999px;",  
				"tj": "text-justify:|;",  
				"tj:a": "text-justify:auto;",  
				"tj:iw": "text-justify:inter-word;",  
				"tj:ii": "text-justify:inter-ideograph;",  
				"tj:ic": "text-justify:inter-cluster;",  
				"tj:d": "text-justify:distribute;",  
				"tj:k": "text-justify:kashida;",  
				"tj:t": "text-justify:tibetan;",  
				"to": "text-outline:|;",  
				"to+": "text-outline:0 0 #000;",  
				"to:n": "text-outline:none;",  
				"tr": "text-replace:|;",  
				"tr:n": "text-replace:none;",  
				"tt": "text-transform:|;",  
				"tt:n": "text-transform:none;",  
				"tt:c": "text-transform:capitalize;",  
				"tt:u": "text-transform:uppercase;",  
				"tt:l": "text-transform:lowercase;",  
				"tw": "text-wrap:|;",  
				"tw:n": "text-wrap:normal;",  
				"tw:no": "text-wrap:none;",  
				"tw:u": "text-wrap:unrestricted;",  
				"tw:s": "text-wrap:suppress;",  
				"tsh": "text-shadow:|;",  
				"tsh+": "text-shadow:0 0 0 #000;",  
				"tsh:n": "text-shadow:none;",  
				"lh": "line-height:|;",  
				"whs": "white-space:|;",  
				"whs:n": "white-space:normal;",  
				"whs:p": "white-space:pre;",  
				"whs:nw": "white-space:nowrap;",  
				"whs:pw": "white-space:pre-wrap;",  
				"whs:pl": "white-space:pre-line;",  
				"whsc": "white-space-collapse:|;",  
				"whsc:n": "white-space-collapse:normal;",  
				"whsc:k": "white-space-collapse:keep-all;",  
				"whsc:l": "white-space-collapse:loose;",  
				"whsc:bs": "white-space-collapse:break-strict;",  
				"whsc:ba": "white-space-collapse:break-all;",  
				"wob": "word-break:|;",  
				"wob:n": "word-break:normal;",  
				"wob:k": "word-break:keep-all;",  
				"wob:l": "word-break:loose;",  
				"wob:bs": "word-break:break-strict;",  
				"wob:ba": "word-break:break-all;",  
				"wos": "word-spacing:|;",  
				"wow": "word-wrap:|;",  
				"wow:nm": "word-wrap:normal;",  
				"wow:n": "word-wrap:none;",  
				"wow:u": "word-wrap:unrestricted;",  
				"wow:s": "word-wrap:suppress;",  
				"lts": "letter-spacing:|;",  
				"f": "font:|;",  
				"f+": "font:1em Arial,sans-serif;",  
				"fw": "font-weight:|;",  
				"fw:n": "font-weight:normal;",  
				"fw:b": "font-weight:bold;",  
				"fw:br": "font-weight:bolder;",  
				"fw:lr": "font-weight:lighter;",  
				"fs": "font-style:|;",  
				"fs:n": "font-style:normal;",  
				"fs:i": "font-style:italic;",  
				"fs:o": "font-style:oblique;",  
				"fv": "font-variant:|;",  
				"fv:n": "font-variant:normal;",  
				"fv:sc": "font-variant:small-caps;",  
				"fz": "font-size:|;",  
				"fza": "font-size-adjust:|;",  
				"fza:n": "font-size-adjust:none;",  
				"ff": "font-family:|;",  
				"ff:s": "font-family:serif;",  
				"ff:ss": "font-family:sans-serif;",  
				"ff:c": "font-family:cursive;",  
				"ff:f": "font-family:fantasy;",  
				"ff:m": "font-family:monospace;",  
				"fef": "font-effect:|;",  
				"fef:n": "font-effect:none;",  
				"fef:eg": "font-effect:engrave;",  
				"fef:eb": "font-effect:emboss;",  
				"fef:o": "font-effect:outline;",  
				"fem": "font-emphasize:|;",  
				"femp": "font-emphasize-position:|;",  
				"femp:b": "font-emphasize-position:before;",  
				"femp:a": "font-emphasize-position:after;",  
				"fems": "font-emphasize-style:|;",  
				"fems:n": "font-emphasize-style:none;",  
				"fems:ac": "font-emphasize-style:accent;",  
				"fems:dt": "font-emphasize-style:dot;",  
				"fems:c": "font-emphasize-style:circle;",  
				"fems:ds": "font-emphasize-style:disc;",  
				"fsm": "font-smooth:|;",  
				"fsm:a": "font-smooth:auto;",  
				"fsm:n": "font-smooth:never;",  
				"fsm:aw": "font-smooth:always;",  
				"fst": "font-stretch:|;",  
				"fst:n": "font-stretch:normal;",  
				"fst:uc": "font-stretch:ultra-condensed;",  
				"fst:ec": "font-stretch:extra-condensed;",  
				"fst:c": "font-stretch:condensed;",  
				"fst:sc": "font-stretch:semi-condensed;",  
				"fst:se": "font-stretch:semi-expanded;",  
				"fst:e": "font-stretch:expanded;",  
				"fst:ee": "font-stretch:extra-expanded;",  
				"fst:ue": "font-stretch:ultra-expanded;",  
				"op": "opacity:|;",  
				"op:ie": "filter:progid:DXImageTransform.Microsoft.Alpha(Opacity=100);",  
				"op:ms": "-ms-filter:'progid:DXImageTransform.Microsoft.Alpha(Opacity=100)';",  
				"rz": "resize:|;",  
				"rz:n": "resize:none;",  
				"rz:b": "resize:both;",  
				"rz:h": "resize:horizontal;",  
				"rz:v": "resize:vertical;",  
				"cur": "cursor:|;",  
				"cur:a": "cursor:auto;",  
				"cur:d": "cursor:default;",  
				"cur:c": "cursor:crosshair;",  
				"cur:ha": "cursor:hand;",  
				"cur:he": "cursor:help;",  
				"cur:m": "cursor:move;",  
				"cur:p": "cursor:pointer;",  
				"cur:t": "cursor:text;",  
				"pgbb": "page-break-before:|;",  
				"pgbb:au": "page-break-before:auto;",  
				"pgbb:al": "page-break-before:always;",  
				"pgbb:l": "page-break-before:left;",  
				"pgbb:r": "page-break-before:right;",  
				"pgbi": "page-break-inside:|;",  
				"pgbi:au": "page-break-inside:auto;",  
				"pgbi:av": "page-break-inside:avoid;",  
				"pgba": "page-break-after:|;",  
				"pgba:au": "page-break-after:auto;",  
				"pgba:al": "page-break-after:always;",  
				"pgba:l": "page-break-after:left;",  
				"pgba:r": "page-break-after:right;",  
				"orp": "orphans:|;",  
				"wid": "widows:|;"  

		},  
		    
		html: {  
			snippets: {  
				'cc:ie6': '<!--[if lte IE 6]>nt${child}|n<![endif]-->',  
				'cc:ie': '<!--[if IE]>nt${child}|n<![endif]-->',  
				'cc:noie': '<!--[if !IE]><!-->nt${child}|n<!--<![endif]-->',  
				'html:4t': '<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">n' +  
						'<html lang="ru">n' +  
						'<head>n' +  
						'	<title></title>n' +  
						'	<meta http-equiv="Content-Type" content="text/html;charset=UTF-8">n' +  
						'</head>n' +  
						'<body>nt${child}|n</body>n' +  
						'</html>',  
				    
				'html:4s': '<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd">n' +  
						'<html lang="ru">n' +  
						'<head>n' +  
						'	<title></title>n' +  
						'	<meta http-equiv="Content-Type" content="text/html;charset=UTF-8">n' +  
						'</head>n' +  
						'<body>nt${child}|n</body>n' +  
						'</html>',  
				    
				'html:xt': '<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">n' +  
						'<html xmlns="http://www.w3.org/1999/xhtml" xml:lang="ru">n' +  
						'<head>n' +  
						'	<title></title>n' +  
						'	<meta http-equiv="Content-Type" content="text/html;charset=UTF-8" />n' +  
						'</head>n' +  
						'<body>nt${child}|n</body>n' +  
						'</html>',  
				    
				'html:xs': '<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">n' +  
						'<html xmlns="http://www.w3.org/1999/xhtml" xml:lang="ru">n' +  
						'<head>n' +  
						'	<title></title>n' +  
						'	<meta http-equiv="Content-Type" content="text/html;charset=UTF-8" />n' +  
						'</head>n' +  
						'<body>nt${child}|n</body>n' +  
						'</html>',  
				    
				'html:xxs': '<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.1//EN" "http://www.w3.org/TR/xhtml11/DTD/xhtml11.dtd">n' +  
						'<html xmlns="http://www.w3.org/1999/xhtml" xml:lang="ru">n' +  
						'<head>n' +  
						'	<title></title>n' +  
						'	<meta http-equiv="Content-Type" content="text/html;charset=UTF-8" />n' +  
						'</head>n' +  
						'<body>nt${child}|n</body>n' +  
						'</html>',  
				    
				'html:5': '<!DOCTYPE HTML>n' +  
						'<html lang="ru-RU">n' +  
						'<head>n' +  
						'	<title></title>n' +  
						'	<meta charset="UTF-8">n' +  
						'</head>n' +  
						'<body>nt${child}|n</body>n' +  
						'</html>'  
			},  
			default_attributes: {  
				a: {href: ''},  
				'a:link': {href: 'http://|'},  
				'a:mail': {href: 'mailto:|'},  
				abbr: {title: ''},  
				acronym: {title: ''},  
				base: {href: ''},  
				bdo: {dir: ''},  
				'bdo:r': {dir: 'rtl'},  
				'bdo:l': {dir: 'ltr'},  
				'link:css': [{rel: "stylesheet"}, {type: "text/css"}, {href: "|style.css"}, {media: all}],  
				'link:print': [{rel: "stylesheet"}, {type: "text/css"}, {href: "|print.css"}, {media: print}],  
				'link:favicon': [{rel: "shortcut icon"}, {type: "image/x-icon"}, {href: |favicon.ico}],  
				'link:touch': [{rel: "apple-touch-icon"}, {href: |favicon.png}],  
				'link:rss': [{rel: "alternate"}, {type: "application/rss+xml"}, {title: "RSS"}, {href: |rss.xml}],  
				'link:atom': [{rel: "alternate"}, {type: "application/atom+xml"}, {title: "Atom"}, {href: atom.xml}],  
				'meta:utf': [{"http-equiv": "Content-Type"}, {content: text/html;charset=UTF-8}],  
				'meta:win': [{"http-equiv": "Content-Type"}, {content: text/html;charset=Win-1251}],  
				'meta:compat': [{"http-equiv": "X-UA-Compatible"}, {content: IE=7}],  
				style: {type: 'text/css'},  
				script: {type: 'text/javascript'},  
				'script:src': [{type: 'text/javascript'}, {src: }],  
				img: [{src: ''}, {alt: ''}],  
				iframe: [{src: ''}, {frameborder: '0'}],  
				embed: [{src: ''}, {type: ''}],  
				object: [{data: ''}, {type: ''}],  
				param: [{name: ''}, {value: ''}],  
				map: {name: ''},  
				area: [{shape: ''}, {coords: ''}, {href: ''}, {alt: ''}],  
				'area:d': [{shape: 'default'}, {href: ''}, {alt: ''}],  
				'area:c': [{shape: 'circle'}, {coords: ''}, {href: ''}, {alt: ''}],  
				'area:r': [{shape: 'rect'}, {coords: ''}, {href: ''}, {alt: ''}],  
				'area:p': [{shape: 'poly'}, {coords: ''}, {href: ''}, {alt: ''}],  
				link: [{rel: 'stylesheet'}, {href: ''}],  
				form: {action: ''},  
				'form:get': {action: '', method: 'get'},  
				'form:post': {action: '', method: 'post'},  
				label: {'for': ''},  
				input: {type: ''},  
				'input:hidden': [{type: 'hidden'}, {name: ''}],  
				'input:h': [{type: 'hidden'}, {name: ''}],  
				'input:text': [{type: 'text'}, {name: ''}, {id: ''}],  
				'input:t': [{type: 'text'}, {name: ''}, {id: ''}],  
				'input:search': [{type: 'search'}, {name: ''}, {id: ''}],  
				'input:email': [{type: 'email'}, {name: ''}, {id: ''}],  
				'input:url': [{type: 'url'}, {name: ''}, {id: ''}],  
				'input:password': [{type: 'password'}, {name: ''}, {id: ''}],  
				'input:p': [{type: 'password'}, {name: ''}, {id: ''}],  
				'input:datetime': [{type: 'datetime'}, {name: ''}, {id: ''}],  
				'input:date': [{type: 'date'}, {name: ''}, {id: ''}],  
				'input:datetime-local': [{type: 'datetime-local'}, {name: ''}, {id: ''}],  
				'input:month': [{type: 'month'}, {name: ''}, {id: ''}],  
				'input:week': [{type: 'week'}, {name: ''}, {id: ''}],  
				'input:time': [{type: 'time'}, {name: ''}, {id: ''}],  
				'input:number': [{type: 'number'}, {name: ''}, {id: ''}],  
				'input:color': [{type: 'color'}, {name: ''}, {id: ''}],  
				'input:checkbox': [{type: 'checkbox'}, {name: ''}, {id: ''}],  
				'input:c': [{type: 'checkbox'}, {name: ''}, {id: ''}],  
				'input:radio': [{type: 'radio'}, {name: ''}, {id: ''}],  
				'input:r': [{type: 'radio'}, {name: ''}, {id: ''}],  
				'input:range': [{type: 'range'}, {name: ''}, {id: ''}],  
				'input:file': [{type: 'file'}, {name: ''}, {id: ''}],  
				'input:f': [{type: 'file'}, {name: ''}, {id: ''}],  
				'input:submit': [{type: 'submit'}, {value: ''}],  
				'input:s': [{type: 'submit'}, {value: ''}],  
				'input:image': [{type: 'image'}, {src: ''}, {alt: ''}],  
				'input:i': [{type: 'image'}, {src: ''}, {alt: ''}],  
				'input:reset': [{type: 'reset'}, {value: ''}],  
				'input:button': [{type: 'button'}, {value: ''}],  
				'input:b': [{type: 'button'}, {value: ''}],  
				select: [{name: ''}, {id: ''}],  
				option: {value: ''},  
				textarea: [{name: ""}, {id: ""}, {cols: "30"}, {rows: 10}],  
				'menu:context': {type: 'context'},  
				'menu:c': {type: 'context'},  
				'menu:toolbar': {type: 'toolbar'},  
				'menu:t': {type: 'toolbar'},  
				video: {src: ''},  
				audio: {src: ''},  
				'html:xml': [{xmlns: "http://www.w3.org/1999/xhtml"}, {'xml:lang': ru}]  
				    
			},  
			    
			aliases: {  
				'link:*': 'link',  
				'meta:*': 'meta',  
				'area:*': 'area',  
				'bdo:*': 'bdo',  
				'form:*': 'form',  
				'input:*': 'input',  
				'script:*': 'script',  
				'html:*': 'html',  
				'a:*': 'a',  
				'menu:*': 'menu',  
				    
				bq: 'blockquote',  
				acr: 'acronym',  
				fig: 'figure',  
				ifr: 'iframe',  
				emb: 'embed',  
				obj: 'object',  
				src: 'source',  
				cap: 'caption',  
				colg: 'colgroup',  
				fst: 'fieldset',  
				btn: 'button',  
				optg: 'optgroup',  
				opt: 'option',  
				tarea: 'textarea',  
				leg: 'legend',  
				sect: 'section',  
				art: 'article',  
				hdr: 'header',  
				ftr: 'footer',  
				adr: 'address',  
				dlg: 'dialog',  
				str: 'strong',  
				prog: 'progress',  
				fset: 'fieldset',  
				datag: 'datagrid',  
				datal: 'datalist',  
				kg: 'keygen',  
				out: 'output',  
				det: 'details',  
				cmd: 'command'  
			},  
			expandos: {  
				ol: 'ol>li',  
				ul: 'ul>li',  
				dl: 'dl>dt+dd',  
				map: 'map>area',  
				table: 'table>tr>td',  
				colgroup: 'colgroup>col',  
				colg: 'colgroup>col',  
				tr: 'tr>td',  
				select: 'select>option',  
				optgroup: 'optgroup>option',  
				optg: 'optgroup>option'  
			},  
			    
			empty_elements: "area,base,basefont,br,col,frame,hr,img,input,isindex,link,meta,param,embed,keygen,command",  
			    
			block_elements: "address,applet,blockquote,button,center,dd,del,dir,div,dl,dt,fieldset,form,frameset,hr,iframe,ins,isindex,li,link,map,menu,noframes,noscript,object,ol,p,pre,script,table,tbody,td,tfoot,th,thead,tr,ul,h1,h2,h3,h4,h5,h6",  
			    
			inline_elements: "a,abbr,acronym,applet,b,basefont,bdo,big,br,button,cite,code,del,dfn,em,font,i,iframe,img,input,ins,kbd,label,map,object,q,s,samp,script,select,small,span,strike,strong,sub,sup,textarea,tt,u,var"  
		},  
		    
		xsl: {  
			default_attributes: {  
				tmatch: [{match: ''}, {mode: ''}],  
				tname: [{name: ''}],  
				'xsl:when': {test: ''},  
				'var': [{'name': ''}, {'select': ''}],  
				'vari': {'name': ''},  
				'if': {'test': ''},  
				'call': {'name': ''},  
				'attr': {'name': ''},  
				'wp': [{'name': ''}, {'select': ''}],  
				'par': [{'name': ''}, {'select': ''}],  
				'val': {'select': ''},  
				'co': {'select': ''},  
				'each': {'select': ''},  
				'ap': [{'select': ''}, {'mode': ''}]  
				    
			},  
			    
			aliases: {  
				tmatch: 'xsl:template',  
				tname: 'xsl:template',  
				'var': 'xsl:variable',  
				'vari': 'xsl:variable',  
				'if': 'xsl:if',  
				'call': 'xsl:call-template',  
				'wp': 'xsl:with-param',  
				'par': 'xsl:param',  
				'val': 'xsl:value-of',  
				'attr': 'xsl:attribute',  
				'co' : 'xsl:copy-of',  
				'each' : 'xsl:for-each',  
				'ap' : 'xsl:apply-templates'  
			},  
			    
			expandos: {  
				'choose': 'xsl:choose>xsl:when+xsl:otherwise'  

	};  
	function zenExtend(obj, extender) {  
		for (var p in extender) if (extender.hasOwnProperty(p))  
			obj[p] = extender[p];  

	    
	function zenMakeMap(str){  
		var obj = {}, items = str.split(",");  
		for (var i = 0; i < items.length; i++)  
			obj[items[i]] = true;  
		return obj;  

	    
	zen_settings.html.block_elements = zenMakeMap(zen_settings.html.block_elements);  
	zen_settings.html.inline_elements = zenMakeMap(zen_settings.html.inline_elements);  
	zen_settings.html.empty_elements = zenMakeMap(zen_settings.html.empty_elements);  
	    
	zenExtend(zen_settings.xsl.default_attributes, zen_settings.html.default_attributes);  
	zenExtend(zen_settings.xsl.expandos, zen_settings.html.expandos);  
	zenExtend(zen_settings.xsl.aliases, zen_settings.html.aliases);  
	var zen_coding = (function(){  
		var re_tag = /</?[w:-]+(?:s+[w-:]+(?:s*=s*(?:(?:"[^"]*")|(?:'[^']*')|[^>s]+))?)*s*(/?)>$/;  
		function isAllowedChar(ch) {  
			var char_code = ch.charCodeAt(0),  
				special_chars = '#.>+*:$-_!@';  
			return (char_code > 64 && char_code < 91)       // uppercase letter  
					|| (char_code > 96 && char_code < 123)  // lowercase letter  
					|| (char_code > 47 && char_code < 58)   // number  
					|| special_chars.indexOf(ch) != -1;     // special character  

		function getNewline() {  
			return 'n';  

		function padString(text, pad) {  
			var pad_str = '', result = '';  
			if (typeof(pad) == 'number')  
				for (var i = 0; i < pad; i++)  
					pad_str += zen_settings.indentation;  
			else  
				pad_str = pad;  
			var nl = getNewline(),  
				lines = text.split(/r?n/gm);  
				    
			result += lines[0];  
			for (var j = 1; j < lines.length; j++)  
				result += nl + pad_str + lines[j];  
			return result;  

		function getPartition(offset){  
			return 'text/html'  

		function isShippet(abbr, type) {  
			var res = zen_settings[type || 'html'];  
			return res.snippets && zen_settings[type || 'html'].snippets[abbr] ? true : false;  

		function isEndsWithTag(str) {  
			return re_tag.test(str);  

		function Tag(name, count, type) {  
			name = name.toLowerCase();  
			type = type || 'html';  
			this.name = Tag.getRealName(name, type);  
			this.count = count || 1;  
			this.children = [];  
			this.attributes = [];  
			this._res = zen_settings[type];  
			if ('default_attributes' in this._res) {  
				var def_attrs = this._res.default_attributes[name];  
			if (def_attrs) {  
				    
				def_attrs = def_attrs instanceof Array ? def_attrs : [def_attrs];  
				for (var i = 0; i < def_attrs.length; i++) {  
					var attrs = def_attrs[i];  
					for (var attr_name in attrs)  
						this.addAttribute(attr_name, attrs[attr_name]);  

		Tag.getRealName = function(name, type) {  
			var real_name = name,  
				res = zen_settings[type || 'html'],  
				aliases = res.aliases || res.short_names || {};  
			    
			if (aliases && aliases[name])  
				real_name = aliases[name];  
			else if (name.indexOf(':') != -1) {  
				var group_name = name.substring(0, name.indexOf(':')) + ':*';  
				if (aliases[group_name])  
					real_name = aliases[group_name];  

			    
			return real_name;  

		Tag.prototype = {  
			addChild: function(tag) {  
				this.children.push(tag);  
			},  
			addAttribute: function(name, value) {  
				this.attributes.push({name: name, value: value});  
			},  
			isEmpty: function() {  
				return ('empty_elements' in this._res)  
					? this._res.empty_elements[this.name]  
					: false;  
			},  
			isInline: function() {  
				return ('inline_elements' in this._res)  
					? this._res.inline_elements[this.name]  
					: false;  
			},  
			isBlock: function() {  
				return ('block_elements' in this._res)  
					? this._res.block_elements[this.name]  
					: true;  
			},  
			hasBlockChildren: function() {  
				for (var i = 0; i < this.children.length; i++) {  
					if (this.children[i].isBlock())  
						return true;  

				    
				return false;  
			},  
			toString: function(format, indent) {  
				var result = [],  
					attrs = '',  
					content = '',  
					start_tag = '',  
					end_tag = '',  
					cursor = format ? '|' : '',  
					a;  
	    
				indent = indent || false;  
				for (var i = 0; i < this.attributes.length; i++) {  
					a = this.attributes[i];  
					attrs += ' ' + a.name + '="' + (a.value || cursor) + '"';  

				if (!this.isEmpty())  
					for (var j = 0; j < this.children.length; j++) {  
						content += this.children[j].toString(format, true);  
						if (format && this.children[j].isBlock() && j != this.children.length - 1)  
							content += getNewline();  

				    
				if (this.name) {  
					if (this.isEmpty()) {  
						start_tag = '<' + this.name + attrs + ' />';  
					} else {  
						start_tag = '<' + this.name + attrs + '>';  
						end_tag = '</' + this.name + '>';  

				if (format) {  
					if (this.name && this.hasBlockChildren()) {  
						start_tag += getNewline() + zen_settings.indentation;  
						end_tag = getNewline() + end_tag;  

					    
					if (content)  
						content = padString(content, indent ? 1 : 0);  
					else  
						start_tag += cursor;  
						    

				for (var i = 0; i < this.count; i++)  
					result.push(start_tag.replace(/$/g, i + 1) + content + end_tag);  
				    
				return result.join(format && this.isBlock() ? getNewline() : '');  

		};  
		    
		function Snippet(name, count, type) {  
			/** @type {String} */  
			this.name = name;  
			this.count = count || 1;  
			this.children = [];  
			this._res = zen_settings[type || 'html'];  

		Snippet.prototype = {  
			addChild: function(tag) {  
				this.children.push(tag);  
			},  
			    
			addAttribute: function(){  
			},  
			    
			isBlock: function() {  
				return true;  
			},  
			    
			toString: function(format, indent) {  
				indent = indent || false;  
				    
				var content = '',  
					result = [],  
					data = this._res.snippets[this.name],  
					begin = '',  
					end = '',  
					child_padding = '',  
					child_token = '${child}';  
				if (data) {  
					if (format) {  
						var nl = getNewline();  
						data = data.replace(/n/g, nl);  
						var lines = data.split(nl);  
						for (var j = 0; j < lines.length; j++) {  
							if (lines[j].indexOf(child_token) != -1) {  
								child_padding =  (m = lines[j].match(/(^s+)/)) ? m[1] : '';  
								break;  

					    
					var parts = data.split(child_token);  
					begin = parts[0] || '';  
					end = parts[1] || '';  

				    
				for (var i = 0; i < this.children.length; i++) {  
					content += this.children[i].toString(format, true);  
					if (format && this.children[i].isBlock() && i != this.children.length - 1)  
						content += getNewline();  

				if (child_padding)  
					content = padString(content, child_padding);  
				for (var i = 0; i < this.count; i++)  
					result.push(begin.replace(/$/g, i + 1) + content + end);  
				    
				return result.join(format ? getNewline() : '');  

		return {  
			findAbbreviation: function() {  
				//return ts.getSelection() || ''  
			},  
			extractAbbreviation: function(str) {  
				var cur_offset = str.length,  
					start_index = -1;  
				while (true) {  
					cur_offset--;  
					if (cur_offset < 0) {  
						start_index = 0;  
						break;  

					var ch = str.charAt(cur_offset);  
					if (!isAllowedChar(ch) || (ch == '>' && isEndsWithTag(str.substring(0, cur_offset + 1)))) {  
						start_index = cur_offset + 1;  
						break;  

				if (start_index != -1)  
					return str.substring(start_index);  
				else  
					return '';  
			},  
			parseIntoTree: function(abbr, type) {  
				type = type || 'html';  
				var root = new Tag('', 1, type),  
					parent = root,  
					last = null,  
					res = zen_settings[type],  
					re = /([+>])?([a-z][a-z0-9:!-]*)(#[w-$]+)?((?:.[w-$]+)*)(?:*(d+))?/ig;  
				if (!abbr)  
					return null;  
				abbr = abbr.replace(/([a-z][a-z0-9]*)+$/i, function(str, tag_name){  
					if ('expandos' in res)  
						return res.expandos[tag_name] || str;  
					else  
						return str;  
				});  
				    
				abbr = abbr.replace(re, function(str, operator, tag_name, id, class_name, multiplier){  
					multiplier = multiplier ? parseInt(multiplier) : 1;  
					var current = isShippet(tag_name, type) ? new Snippet(tag_name, multiplier, type) : new Tag(tag_name, multiplier, type);  
					if (id)  
						current.addAttribute('id', id.substr(1));  
					if (class_name)  
						current.addAttribute('class', class_name.substr(1).replace(/./g, ' '));  
					if (operator == '>' && last)  
						parent = last;  
						    
					parent.addChild(current);  
					    
					last = current;  
					return '';  
				});  
				return (!abbr) ? root : null;  
			},  
	    
			padString: padString,  
			getNewline: getNewline,  
	    
			findNewEditPoint: function(inc, offset) {  
				return -1  
			},  
	    
			getEditorType: function() {  
				return 'html'  
				/* return !(ts.isXHTML() || ts.isASP() || ts.isASP_VB() || ts.isPHP() || ts.isCFML() || ts.isJSP())  
					? 'css'  
					: 'html'  
				*/  
			},  
	    
			getCurrentLinePadding: function() {  
				//return (ts.getSelection().match(/^(s+)/) || [''])[0]  
				return (document.selection.Text.match(/^(s+)/) || [''])[0]  

	})();  
	objectTag();  
	December 18, 2009 at 2:29 pm [#7974](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/9dac5ab27354edc3ff070db8ce1a1a66?s=80&d=identicon&r=g)ToadLoadin](https://www.emeditor.com/forums/users/ToadLoadin/ "View ToadLoadin's profile")  
Member  
:lol: wow, looks really great, could you tell me how to use it?  
 Just setup a new macro snippet, then paste your macro into it?  
 Or, other setting needed? :-)  
December 18, 2009 at 2:35 pm [#7975](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/f4134e2e546d7b8d227e6793a447fb97?s=80&d=identicon&r=g)robben](https://www.emeditor.com/forums/users/robben/ "View robben's profile")  
Member  
yes,paste your macro snippet,set shortcut :-D  
December 18, 2009 at 2:44 pm [#7976](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/f4134e2e546d7b8d227e6793a447fb97?s=80&d=identicon&r=g)robben](https://www.emeditor.com/forums/users/robben/ "View robben's profile")  
Member  
Demo video with current Zen Coding features  
<http://v.youku.com/v%5Fshow/id%5FXMTM4NDQwNzgw.html>
* Author  
Posts

Viewing 4 posts - 1 through 4 (of 4 total)

* You must be logged in to reply to this topic.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-pixel-power-redesigned-radeon/"><u>[New] In 2024, Pixel Power Redesigned Radeon</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-in-depth-vita-video-editing-analysis-and-step-by-step-guide/"><u>[New] In-Depth Vita Video Editing Analysis & Step-by-Step Guide</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/new-stepping-into-a-new-digital-era-mastering-your-tiktok-handle-change-process-for-2024/"><u>[New] Stepping Into a New Digital Era Mastering Your TikTok Handle Change Process for 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-2024-approved-explore-tiktoks-wonders-the-ultimate-macbook-setup/"><u>[Updated] 2024 Approved Explore TikTok's Wonders The Ultimate MacBook Setup</u></a></li>
<li><a href="https://win-net.techidaily.com/1-superior-viteui-dashboard-template-zero-cost-solution-for-vuejs-3-and-bootstrap-5-developers-by-creative-tim/"><u>1. Superior ViteUI Dashboard Template: Zero Cost Solution for VueJS 3 and Bootstrap 5 Developers by Creative Tim</u></a></li>
<li><a href="https://win-net.techidaily.com/advanced-material-dashboard-pro-with-bootstrap-4-and-django-a-complete-professional-admin-panel/"><u>Advanced Material Dashboard Pro with Bootstrap 4 & Django: A Complete, Professional Admin Panel</u></a></li>
<li><a href="https://win-net.techidaily.com/advanced-material-kit-pro-elite-bootstrap-and-material-design-themes-by-creative-tim/"><u>Advanced Material Kit Pro: Elite Bootstrap and Material Design Themes by Creative Tim</u></a></li>
<li><a href="https://win-net.techidaily.com/effective-techniques-for-isolating-audio-in-mp4-file-format/"><u>Effective Techniques for Isolating Audio in MP4 File Format</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/fast-track-to-efficiency-7-essential-tips-for-a-speedy-computer/"><u>Fast Track to Efficiency: 7 Essential Tips for a Speedy Computer</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-tecno-pop-8-location-without-installing-software-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Tecno Pop 8 Location without Installing Software? | Dr.fone</u></a></li>
<li><a href="https://win-net.techidaily.com/step-by-step-guide-effortlessly-import-blackberry-contacts-onto-your-iphone-65s/"><u>Step-by-Step Guide: Effortlessly Import BlackBerry Contacts Onto Your iPhone 6/5S</u></a></li>
<li><a href="https://win-able.techidaily.com/troubleshooting-resolving-assassins-creed-odyssey-pc-game-crashes-effortlessly/"><u>Troubleshooting: Resolving Assassin's Creed Odyssey PC Game Crashes Effortlessly</u></a></li>
<li><a href="https://win-net.techidaily.com/ultimate-guide-mastering-the-art-of-deleting-playlists-from-your-iphone/"><u>Ultimate Guide: Mastering the Art of Deleting Playlists From Your iPhone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unlocking-free-system-resources-addressing-shell-induced-cpu-overruns-on-windows/"><u>Unlocking Free System Resources: Addressing Shell-Induced CPU Overruns on Windows</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948954/19272" target="_top" id="1948954">
  <img src="//a.impactradius-go.com/display-ad/19272-1948954" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948954/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

