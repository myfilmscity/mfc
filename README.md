(function (){ var p="",w=" ",ba=" *",ca=" * ",da=" , ",ea=" at ",fa=' color="',ga=' color="{borderColor}" /></g_vml_:shape>',ha=' coordorigin="0 0" coordsize="',ia=' endcap="flat"',ja=' joinstyle="miter"',y=" l ",z=" m ",na=' miterlimit="',oa=' path="',pa=' strokecolor="',qa=' stroked="false"',ra=' stroked="true" strokeweight="',sa=' strokeweight="{borderWidth}" strokecolor="{borderColor}"',ta=' weight="',ua=' weight="{borderWidth}px"',B='"',va='" />',wa='" /></g_vml_:shape>',xa='" filled="false" ',ya='" filled="true" ',
za='" opacity="',Aa='" position = "',Ba='" stroked="true"',Ca='" type="tile" src="',Da='"/>',Ea='"><g_vml_:fill color="',Fa='"><g_vml_:stroke opacity="',Ga='"><g_vml_:stroke opacity="1" joinstyle="miter"',Ha="#",Ia="%s",Ja="'",Ka="(",La="(?:\\s|$)",Ma="(?:^|\\s)",Na="(\\d*)(\\D*)",C=")",Oa="*",Pa="+",D=",",E="-",Qa=".",Ra="0",Sa="0 -0.5",Ta="0 0",Ua="0% 0%",Va="0px",Wa="10%",Xa="526",Ya="9",F=":",Za=": ",$a=":0;width:",ab=":contains",bb=";",cb="</g_vml_:shape>",db='<g_vml_:shape fillcolor="',eb='<g_vml_:shape fillcolor="0" filled="false" ',
fb="=",gb=">",hb="An object listener must have handleEvent method.",ib="Assertion failed",jb="BackCompat",kb="DIV",lb="Listener can not be null.",mb="Node cannot be null or undefined.",nb="OBJECT",ob="[",pb="[object Array]",rb="[object Function]",sb="[object Window]",tb="[object XMLDocument]",ub="\\",vb="]",wb="_bottom",xb="_left",yb="_right",zb="_top",Ab="_uid",Bb="_zipIdx",Cb="a",Db="absolute",Eb="application/xml",Fb="array",Gb="backgroundColor",Hb="backgroundImageUrl",Ib="backgroundPosition",Jb=
"beforeEnd",Kb="borderColor_bottom",Lb="borderColor_left",Mb="borderColor_right",Nb="borderColor_top",Ob="borderRadius_bl",Pb="borderRadius_br",Qb="borderRadius_tl",Rb="borderRadius_tr",Sb="borderStyle_bottom",Tb="borderStyle_left",Ub="borderStyle_right",Vb="borderStyle_top",Wb="borderWidth_bottom",Xb="borderWidth_left",Yb="borderWidth_right",Zb="borderWidth_top",$b="bottom",ac="call",bc="childNodes",cc="children",dc="class",ec="className",fc="complete",gc="default",hc="even",ic="event",jc="float",
kc="for",lc="function",mc="g",nc="header-inner",oc="height:",pc="hidden",qc="hover-retrofitter-",rc="inline",Ac="keypress",Bc="left",Cc="medium",Dc="mouseout",Ec="mouseover",Fc="n",Gc="nextElementSibling",Hc="nextSibling",H="none",Ic="null",Jc="number",Kc="object",Lc="odd",Mc="on",Nc="onresize",Oc="opacity",Pc="previousElementSibling",Qc="previousSibling",I="px",Rc='px"',Sc="px;",Tc='px;"',Uc="relative",Vc="retrofitter-",Wc="rgb",Xc="rgba(",Yc="right",Zc="rtl",$c="shadowBlurRadius",ad="shadowColor",
bd="shadowHOffs",cd="shadowVOffs",dd="solid",ed="splice",fd="string",gd="style",hd='style="position:absolute;top:0;',J="transparent",id="transparent ",jd="url(",kd="var ",ld="visible",md="window",K="{borderColor}",L="{borderWidth}",nd="|=",od="~",M,O=this,pd=function(a,b,d){a=a.split(Qa);d=d||O;a[0]in d||!d.execScript||d.execScript(kd+a[0]);for(var c;a.length&&(c=a.shift());)a.length||void 0===b?d=d[c]?d[c]:d[c]={}:d[c]=b},qd=function(a){var b=typeof a;if(b==Kc)if(a){if(a instanceof Array)return Fb;
if(a instanceof Object)return b;var d=Object.prototype.toString.call(a);if(d==sb)return Kc;if(d==pb||typeof a.length==Jc&&"undefined"!=typeof a.splice&&"undefined"!=typeof a.propertyIsEnumerable&&!a.propertyIsEnumerable(ed))return Fb;if(d==rb||"undefined"!=typeof a.call&&"undefined"!=typeof a.propertyIsEnumerable&&!a.propertyIsEnumerable(ac))return lc}else return Ic;else if(b==lc&&"undefined"==typeof a.call)return Kc;return b},rd=function(a){return typeof a==fd},P=function(a){return a[sd]||(a[sd]=
++td)},sd="closure_uid_"+(1E9*Math.random()>>>0),td=0,ud=function(a,b){function d(){}d.prototype=b.prototype;a.pa=b.prototype;a.prototype=new d;a.prototype.constructor=a;a.qa=function(a,e,d){for(var g=Array(arguments.length-2),h=2;h<arguments.length;h++)g[h-2]=arguments[h];return b.prototype[e].apply(a,g)}};var vd=function(a,b){for(var d=a.split(Ia),c=p,e=Array.prototype.slice.call(arguments,1);e.length&&1<d.length;)c+=d.shift()+e.shift();return c+d.join(Ia)},Q=String.prototype.trim?function(a){return a.trim()}:function(a){return a.replace(/^[\s\xa0]+|[\s\xa0]+$/g,p)},wd=function(a,b){return a<b?-1:a>b?1:0};var xd,yd,zd,Ad,Bd,Cd=function(a){this.M=a;this.B=!1},Dd=/background-color/i,Ed=/^background-image/i,Fd=/background/i,Gd=/goog-ms-box-shadow/i,Hd=/goog-ms-border-radius/i,Id=/goog-ms-border-bottom-left-radius/i,Jd=/goog-ms-border-bottom-right-radius/i,Kd=/goog-ms-border-top-left-radius/i,Ld=/goog-ms-border-top-right-radius/i,Md=/opacity/i,Nd=/^border:/i,Od=/^border-style:/i,Pd=/^border-color:/i,Qd=/^border-left:/i,Rd=/^border-right:/i,Sd=/^border-top:/i,Td=/^border-bottom:/i,Ud=/^border-left-style:/i,
Vd=/^border-right-style:/i,Wd=/^border-top-style:/i,Xd=/^border-bottom-style:/i,Yd=/^border-left-color:/i,Zd=/^border-right-color:/i,$d=/^border-top-color:/i,ae=/^border-bottom-color:/i,be=/^border-width:/i,ce=/:hover/i,de=/^#?([a-f]|[A-F]|[0-9]){3}(([a-f]|[A-F]|[0-9]){3})?$/,ee=/^\-?[0-9]+(\.[0-9]+)?px$/,fe=/^\-?[0-9]+(\.[0-9]+)?$/,ge=/[^\s]+/g,he=/none|dotted|dashed|solid|double|groove|ridge|inset|outset/i,ie=/^margin:|margin-top:|margin-bottom:|margin-left:|margin-right:/i,je=/top|bottom|left|right|center/i,
ke=[Gd,Id,Jd,Kd,Ld,Hd],le=[Gd,Id,Jd,Kd,Ld,Hd];M=Cd.prototype;M.U=function(){for(var a=0;a<ke.length;a++)if(ke[a].test(this.M))return!0;return!1};M.ma=function(){for(var a=0;a<le.length;a++)if(le[a].test(this.M))return!0;return!1};M.b=function(a){if(!a||!a.indexOf)return a;-1!=a.indexOf(F)&&(a=a.split(F)[1]);if(Q(a)==Cc)return null;-1!=a.indexOf(I)&&(a=a.substr(0,a.length-2));return parseFloat(a)};
M.parse=function(){for(var a={},b=this.M.split(bb),d=0;d<b.length;d++){var c=Q(b[d]);Kd.test(c)?a.borderRadius_tl=this.b(c):Id.test(c)?a.borderRadius_bl=this.b(c):Jd.test(c)?a.borderRadius_br=this.b(c):Ld.test(c)&&(a.borderRadius_tr=this.b(c));if(Hd.test(c)){var e=Q(c.split(F)[1]),e=this.ka(e),f;for(f in e)a[f]=e[f]}else if(Md.test(c))e=c.split(F)[1],a.opacity=parseFloat(e);else if(Gd.test(c))c=c.split(F)[1].match(ge),a.shadowHOffs=this.b(c[0]),a.shadowVOffs=this.b(c[1]),a.shadowBlurRadius=this.b(c[2]),
a.shadowColor=c.slice(3,c.length).join(w);else if(be.test(c))e=Q(c.split(F)[1]),c=e.split(w),1==c.length&&(e=this.b(c[0]),a.borderWidth_left=e,a.borderWidth_right=e,a.borderWidth_top=e,a.borderWidth_bottom=e);else if(Qd.test(c))for(c in e=Q(c.split(F)[1]),e=this.l(e),e)a[c+xb]=e[c];else if(Rd.test(c))for(c in e=Q(c.split(F)[1]),e=this.l(e),e)a[c+yb]=e[c];else if(Sd.test(c))for(c in e=Q(c.split(F)[1]),e=this.l(e),e)a[c+zb]=e[c];else if(Td.test(c))for(c in e=Q(c.split(F)[1]),e=this.l(e),e)a[c+wb]=e[c];
else if(Dd.test(c))e=Q(c.split(F)[1]),a.backgroundColor=e;else if(Ed.test(c))e=Q(c.substr(c.indexOf(F)+1)),a.backgroundImageUrl=e.substring(4,e.lastIndexOf(C));else if(Fd.test(c))for(f in e=c.substring(11,c.length),e=this.ja(e),e)a[f]=e[f];else if(Pd.test(c))e=Q(c.split(F)[1]),c=e.split(w),4==c.length&&-1==e.indexOf(Xc)?(a.borderColor_top=c[0],a.borderColor_right=c[1],a.borderColor_bottom=c[2],a.borderColor_left=c[3]):(a.borderColor_top=e,a.borderColor_right=e,a.borderColor_bottom=e,a.borderColor_left=
e);else if(Yd.test(c))e=Q(c.split(F)[1]),a.borderColor_left=e;else if(Zd.test(c))e=Q(c.split(F)[1]),a.borderColor_right=e;else if($d.test(c))e=Q(c.split(F)[1]),a.borderColor_top=e;else if(ae.test(c))e=Q(c.split(F)[1]),a.borderColor_bottom=e;else if(Nd.test(c))for(f in e=Q(c.split(F)[1]),e=this.l(e),e)a[f+zb]=e[f],a[f+xb]=e[f],a[f+wb]=e[f],a[f+yb]=e[f];else ie.test(c)?this.B=!0:Od.test(c)?(e=Q(c.split(F)[1]),a.borderStyle_top=e,a.borderStyle_left=e,a.borderStyle_bottom=e,a.borderStyle_right=e):Wd.test(c)?
(e=Q(c.split(F)[1]),a.borderStyle_top=e):Ud.test(c)?(e=Q(c.split(F)[1]),a.borderStyle_left=e):Xd.test(c)?(e=Q(c.split(F)[1]),a.borderStyle_bottom=e):Vd.test(c)&&(e=Q(c.split(F)[1]),a.borderStyle_right=e)}return a};
M.ka=function(a){var b=a.split(w);a={};1==b.length?(b=this.b(b[0]),a.borderRadius_tl=b,a.borderRadius_bl=b,a.borderRadius_br=b,a.borderRadius_tr=b):4==b.length&&(a.borderRadius_tl=this.b(b[0]),a.borderRadius_tr=this.b(b[1]),a.borderRadius_br=this.b(b[2]),a.borderRadius_bl=this.b(b[3]));return a};
M.ja=function(a){for(var b=a.split(w),d={},c=0;c<b.length;c++){var e=Q(b[c]);e==J?d.backgroundColor=e:de.test(e)?d.backgroundColor=e:0==e.indexOf(Xc)?(e=a.indexOf(Xc),d.backgroundColor=a.substr(e,a.indexOf(C,e)-e+1)):0==e.indexOf(jd)?d.backgroundImageUrl=e.substring(4,e.lastIndexOf(C)):je.test(e)&&(d.backgroundPosition=e)}return d};
M.l=function(a){for(var b=a.split(w),d={},c=0;c<b.length;c++){var e=Q(b[c]);e==J?d.borderColor=e:de.test(e)?d.borderColor=e:0==e.indexOf(Xc)?(e=a.indexOf(Xc),d.borderColor=a.substring(e,a.indexOf(C,e)+1)):de.test(b[c])?d.borderColor=b[c]:fe.test(b[c])?d.borderWidth=parseFloat(b[c]):ee.test(b[c])?d.borderWidth=this.b(b[c]):he.test(b[c])?d.borderStyle=b[c]:/[a-zA-Z]+/.test(b[c])&&(d.borderColor=b[c])}return d};var me=function(a){if(Error.captureStackTrace)Error.captureStackTrace(this,me);else{var b=Error().stack;b&&(this.stack=b)}a&&(this.message=String(a))};ud(me,Error);me.prototype.name="CustomError";var ne;var oe=function(a,b){b.unshift(a);me.call(this,vd.apply(null,b));b.shift()};ud(oe,me);oe.prototype.name="AssertionError";var pe=function(a,b,d){if(!a){var c=Array.prototype.slice.call(arguments,2),e=ib;if(b)var e=e+(Za+b),f=c;throw new oe(p+e,f||[]);}return a};var qe=function(a){qe[w](a);return a};qe[w]=function(){};var re=Array.prototype,se=re.indexOf?function(a,b,d){pe(null!=a.length);return re.indexOf.call(a,b,d)}:function(a,b,d){d=null==d?0:0>d?Math.max(0,a.length+d):d;if(rd(a))return rd(b)&&1==b.length?a.indexOf(b,d):-1;for(;d<a.length;d++)if(d in a&&a[d]===b)return d;return-1},te=re.forEach?function(a,b,d){pe(null!=a.length);re.forEach.call(a,b,d)}:function(a,b,d){for(var c=a.length,e=rd(a)?a.split(p):a,f=0;f<c;f++)f in e&&b.call(d,e[f],f,a)};var R;a:{var ue=O.navigator;if(ue){var ve=ue.userAgent;if(ve){R=ve;break a}}R=p};var we=-1!=R.indexOf("Opera")||-1!=R.indexOf("OPR"),S=-1!=R.indexOf("Trident")||-1!=R.indexOf("MSIE"),xe=-1!=R.indexOf("Edge"),ye=-1!=R.indexOf("Gecko")&&!(-1!=R.toLowerCase().indexOf("webkit")&&-1==R.indexOf("Edge"))&&!(-1!=R.indexOf("Trident")||-1!=R.indexOf("MSIE"))&&-1==R.indexOf("Edge"),ze=-1!=R.toLowerCase().indexOf("webkit")&&-1==R.indexOf("Edge"),Ae=function(){var a=R;if(ye)return/rv\:([^\);]+)(\)|;)/.exec(a);if(xe)return/Edge\/([\d\.]+)/.exec(a);if(S)return/\b(?:MSIE|rv)[: ]([^\);]+)(\)|;)/.exec(a);
if(ze)return/WebKit\/(\S+)/.exec(a)},Be=function(){var a=O.document;return a?a.documentMode:void 0},Ce=function(){if(we&&O.opera){var a;var b=O.opera.version;try{a=b()}catch(d){a=b}return a}a=p;(b=Ae())&&(a=b?b[1]:p);return S&&(b=Be(),b>parseFloat(a))?String(b):a}(),De={},T=function(a){var b;if(!(b=De[a])){b=0;for(var d=Q(String(Ce)).split(Qa),c=Q(String(a)).split(Qa),e=Math.max(d.length,c.length),f=0;0==b&&f<e;f++){var g=d[f]||p,h=c[f]||p,m=RegExp(Na,mc),l=RegExp(Na,mc);do{var q=m.exec(g)||[p,p,
p],k=l.exec(h)||[p,p,p];if(0==q[0].length&&0==k[0].length)break;b=wd(0==q[1].length?0:parseInt(q[1],10),0==k[1].length?0:parseInt(k[1],10))||wd(0==q[2].length,0==k[2].length)||wd(q[2],k[2])}while(0==b)}b=De[a]=0<=b}return b},Ee=O.document,Fe=Ee&&S?Be()||("CSS1Compat"==Ee.compatMode?parseInt(Ce,10):5):void 0;var Ge=!S||9<=Fe,He=S&&!T(Ya);!ze||T("528");ye&&T("1.9b")||S&&T("8")||we&&T("9.5")||ze&&T("528");ye&&!T("8")||S&&T(Ya);var Ie=function(a,b){this.type=a;this.currentTarget=this.target=b;this.defaultPrevented=this.Y=!1};Ie.prototype.preventDefault=function(){this.defaultPrevented=!0};var Je=function(a,b){Ie.call(this,a?a.type:p);this.relatedTarget=this.currentTarget=this.target=null;this.charCode=this.keyCode=this.button=this.screenY=this.screenX=this.clientY=this.clientX=this.offsetY=this.offsetX=0;this.metaKey=this.shiftKey=this.altKey=this.ctrlKey=!1;this.R=this.state=null;a&&this.ha(a,b)};ud(Je,Ie);
Je.prototype.ha=function(a,b){var d=this.type=a.type,c=a.changedTouches?a.changedTouches[0]:null;this.target=a.target||a.srcElement;this.currentTarget=b;var e=a.relatedTarget;if(e){if(ye){var f;a:{try{qe(e.nodeName);f=!0;break a}catch(g){}f=!1}f||(e=null)}}else d==Ec?e=a.fromElement:d==Dc&&(e=a.toElement);this.relatedTarget=e;null===c?(this.offsetX=ze||void 0!==a.offsetX?a.offsetX:a.layerX,this.offsetY=ze||void 0!==a.offsetY?a.offsetY:a.layerY,this.clientX=void 0!==a.clientX?a.clientX:a.pageX,this.clientY=
void 0!==a.clientY?a.clientY:a.pageY,this.screenX=a.screenX||0,this.screenY=a.screenY||0):(this.clientX=void 0!==c.clientX?c.clientX:c.pageX,this.clientY=void 0!==c.clientY?c.clientY:c.pageY,this.screenX=c.screenX||0,this.screenY=c.screenY||0);this.button=a.button;this.keyCode=a.keyCode||0;this.charCode=a.charCode||(d==Ac?a.keyCode:0);this.ctrlKey=a.ctrlKey;this.altKey=a.altKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.state=a.state;this.R=a;a.defaultPrevented&&this.preventDefault()};
Je.prototype.preventDefault=function(){Je.pa.preventDefault.call(this);var a=this.R;if(a.preventDefault)a.preventDefault();else if(a.returnValue=!1,He)try{if(a.ctrlKey||112<=a.keyCode&&123>=a.keyCode)a.keyCode=-1}catch(b){}};var Ke="closure_listenable_"+(1E6*Math.random()|0),Le=0;var Me=function(a,b,d,c,e,f){this.listener=a;this.proxy=b;this.src=d;this.type=c;this.H=!!e;this.J=f;this.key=++Le;this.m=this.G=!1};Me.prototype.X=function(){this.m=!0;this.J=this.src=this.proxy=this.listener=null};var Ne=function(a){this.src=a;this.h={};this.N=0};Ne.prototype.add=function(a,b,d,c,e){var f=a.toString();a=this.h[f];a||(a=this.h[f]=[],this.N++);var g;a:{for(g=0;g<a.length;++g){var h=a[g];if(!h.m&&h.listener==b&&h.H==!!c&&h.J==e)break a}g=-1}-1<g?(b=a[g],d||(b.G=!1)):(b=new Me(b,null,this.src,f,!!c,e),b.G=d,a.push(b));return b};
Ne.prototype.la=function(a){var b=a.type;if(!(b in this.h))return!1;var d=this.h[b],c=se(d,a),e;if(e=0<=c)pe(null!=d.length),re.splice.call(d,c,1);e&&(a.X(),0==this.h[b].length&&(delete this.h[b],this.N--));return e};var Oe="closure_lm_"+(1E6*Math.random()|0),Pe={},Qe=0,Re=function(a,b,d,c,e){if(qd(b)==Fb){for(var f=0;f<b.length;f++)Re(a,b[f],d,c,e);return null}d=Se(d);if(a&&a[Ke])a=a.va(b,d,c,e);else{if(!b)throw Error("Invalid event type");var f=!!c,g=Te(a);g||(a[Oe]=g=new Ne(a));d=g.add(b,d,!1,c,e);if(!d.proxy){c=Ue();d.proxy=c;c.src=a;c.listener=d;if(a.addEventListener)a.addEventListener(b.toString(),c,f);else if(a.attachEvent)a.attachEvent(Ve(b.toString()),c);else throw Error("addEventListener and attachEvent are unavailable.");
Qe++}a=d}return a},Ue=function(){var a=We,b=Ge?function(d){return a.call(b.src,b.listener,d)}:function(d){d=a.call(b.src,b.listener,d);if(!d)return d};return b},Ve=function(a){return a in Pe?Pe[a]:Pe[a]=Mc+a},Ye=function(a,b,d,c){var e=!0;if(a=Te(a))if(b=a.h[b.toString()])for(b=b.concat(),a=0;a<b.length;a++){var f=b[a];f&&f.H==d&&!f.m&&(f=Xe(f,c),e=e&&!1!==f)}return e},Xe=function(a,b){var d=a.listener,c=a.J||a.src;if(a.G&&typeof a!=Jc&&a&&!a.m){var e=a.src;if(e&&e[Ke])e.xa(a);else{var f=a.type,g=
a.proxy;e.removeEventListener?e.removeEventListener(f,g,a.H):e.detachEvent&&e.detachEvent(Ve(f),g);Qe--;(f=Te(e))?(f.la(a),0==f.N&&(f.src=null,e[Oe]=null)):a.X()}}return d.call(c,b)},We=function(a,b){if(a.m)return!0;if(!Ge){var d;if(!(d=b))a:{d=[md,ic];for(var c=O,e;e=d.shift();)if(null!=c[e])c=c[e];else{d=null;break a}d=c}e=d;d=new Je(e,this);c=!0;if(!(0>e.keyCode||void 0!=e.returnValue)){a:{var f=!1;if(0==e.keyCode)try{e.keyCode=-1;break a}catch(m){f=!0}if(f||void 0==e.returnValue)e.returnValue=
!0}e=[];for(f=d.currentTarget;f;f=f.parentNode)e.push(f);for(var f=a.type,g=e.length-1;!d.Y&&0<=g;g--){d.currentTarget=e[g];var h=Ye(e[g],f,!0,d),c=c&&h}for(g=0;!d.Y&&g<e.length;g++)d.currentTarget=e[g],h=Ye(e[g],f,!1,d),c=c&&h}return c}return Xe(a,new Je(b,this))},Te=function(a){a=a[Oe];return a instanceof Ne?a:null},Ze="__closure_events_fn_"+(1E9*Math.random()>>>0),Se=function(a){pe(a,lb);if(qd(a)==lc)return a;pe(a.handleEvent,hb);a[Ze]||(a[Ze]=function(b){return a.handleEvent(b)});return a[Ze]};!ye&&!S||S&&9<=Fe||ye&&T("1.9.1");S&&T(Ya);var $e=function(a){pe(a,mb);return 9==a.nodeType?a:a.ownerDocument||a.document},af=function(a){this.P=a||O.document||document};af.prototype.ga=function(a){return rd(a)?this.P.getElementById(a):a};af.prototype.createElement=function(a){return this.P.createElement(a)};af.prototype.appendChild=function(a,b){a.appendChild(b)};var bf=function(a){return function(){return a}}(!0);/*
 Portions of this code are from the Dojo Toolkit, received by
 The Closure Library Authors under the BSD license. All other code is
 Copyright 2005-2009 The Closure Library Authors. All Rights Reserved.

The "New" BSD License:

Copyright (c) 2005-2009, The Dojo Foundation
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

 Redistributions of source code must retain the above copyright notice, this
    list of conditions and the following disclaimer.
 Redistributions in binary form must reproduce the above copyright notice,
    this list of conditions and the following disclaimer in the documentation
    and/or other materials provided with the distribution.
 Neither the name of the Dojo Foundation nor the names of its contributors
    may be used to endorse or promote products derived from this software
    without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND
ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED
WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED.  IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE
FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER
CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY,
OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
*/
var cf=function(){function a(a,b){var c=b||[];a&&c.push(a);return c}var b=ze&&document.compatMode==jb,d=S&&!T(Ya),c=document.firstChild.children?cc:bc,e=!1,f=function(a){a=0<=">~+".indexOf(a.slice(-1))?a+ca:a+w;for(var b=function(b,c){return Q(a.slice(b,c))},c=[],d=-1,f=-1,g=-1,h=-1,k=-1,l=-1,m=-1,r=p,q=p,t,n=0,v=a.length,x=null,u=null,A=function(){0<=l&&(x.id=b(l,n).replace(/\\/g,p),l=-1);if(0<=m){var a=m==n?null:b(m,n);0>">~+".indexOf(a)?x.tag=a:x.D=a;m=-1}0<=k&&(x.f.push(b(k+1,n).replace(/\\/g,
p)),k=-1)};r=q,q=a.charAt(n),n<v;n++)r!=ub&&(x||(t=n,x={query:null,i:[],o:[],f:[],tag:null,D:null,id:null,getTag:function(){return e?this.ia:this.tag}},m=n),0<=d?q==vb?(u.attr?u.K=b(g||d+1,n):u.attr=b(d+1,n),!(d=u.K)||d.charAt(0)!=B&&d.charAt(0)!=Ja||(u.K=d.slice(1,-1)),x.o.push(u),u=null,d=g=-1):q==fb&&(g=0<="|~^$*".indexOf(r)?r:p,u.type=g+q,u.attr=b(d+1,n-g.length),g=n+1):0<=f?q==C&&(0<=h&&(u.value=b(f+1,n)),h=f=-1):q==Ha?(A(),l=n+1):q==Qa?(A(),k=n):q==F?(A(),h=n):q==ob?(A(),d=n,u={}):q==Ka?(0<=
h&&(u={name:b(h+1,n),value:null},x.i.push(u)),f=n):q==w&&r!=q&&(A(),0<=h&&x.i.push({name:b(h+1,n)}),x.W=x.i.length||x.o.length||x.f.length,x.wa=x.query=b(t,n),x.ia=x.tag=x.D?null:x.tag||Oa,x.tag&&(x.tag=x.tag.toUpperCase()),c.length&&c[c.length-1].D&&(x.V=c.pop(),x.query=x.V.query+w+x.query),c.push(x),x=null));return c},g=function(a,b){return a?b?function(){return a.apply(window,arguments)&&b.apply(window,arguments)}:a:b},h=function(a){return 1==a.nodeType},m=function(a,b){return a?b==dc?a.className||
p:b==kc?a.htmlFor||p:b==gd?a.style.cssText||p:(e?a.getAttribute(b):a.getAttribute(b,2))||p:p},l={"*=":function(a,b){return function(c){return 0<=m(c,a).indexOf(b)}},"^=":function(a,b){return function(c){return 0==m(c,a).indexOf(b)}},"$=":function(a,b){return function(c){c=w+m(c,a);return c.lastIndexOf(b)==c.length-b.length}},"~=":function(a,b){var c=w+b+w;return function(b){return 0<=(w+m(b,a)+w).indexOf(c)}},"|=":function(a,b){b=w+b;return function(c){c=w+m(c,a);return c==b||0==c.indexOf(b+E)}},
"=":function(a,b){return function(c){return m(c,a)==b}}},q="undefined"==typeof document.firstChild.nextElementSibling,k=q?Hc:Gc,n=q?Qc:Pc,r=q?h:bf,v=function(a){for(;a=a[n];)if(r(a))return!1;return!0},u=function(a){for(;a=a[k];)if(r(a))return!1;return!0},A=function(a){var b=a.parentNode,e=0,d=b[c],f=a._i||-1,g=b._l||-1;if(!d)return-1;d=d.length;if(g==d&&0<=f&&0<=g)return f;b._l=d;f=-1;for(b=b.firstElementChild||b.firstChild;b;b=b[k])r(b)&&(b._i=++e,a===b&&(f=e));return f},Y=function(a){return!(A(a)%
2)},Z=function(a){return A(a)%2},G={checked:function(){return function(a){return a.checked||a.attributes.checked}},"first-child":function(){return v},"last-child":function(){return u},"only-child":function(){return function(a){return v(a)&&u(a)?!0:!1}},empty:function(){return function(a){var b=a.childNodes;for(a=a.childNodes.length-1;0<=a;a--){var c=b[a].nodeType;if(1===c||3==c)return!1}return!0}},contains:function(a,b){var c=b.charAt(0);if(c==B||c==Ja)b=b.slice(1,-1);return function(a){return 0<=
a.innerHTML.indexOf(b)}},not:function(a,b){var c=f(b)[0],d={j:1};c.tag!=Oa&&(d.tag=1);c.f.length||(d.f=1);var e=t(c,d);return function(a){return!e(a)}},"nth-child":function(a,b){if(b==Lc)return Z;if(b==hc)return Y;if(-1!=b.indexOf(Fc)){var c=b.split(Fc,2),d=c[0]?c[0]==E?-1:parseInt(c[0],10):1,e=c[1]?parseInt(c[1],10):0,f=0,g=-1;0<d?0>e?e=e%d&&d+e%d:0<e&&(e>=d&&(f=e-e%d),e%=d):0>d&&(d*=-1,0<e&&(g=e,e%=d));if(0<d)return function(a){a=A(a);return a>=f&&(0>g||a<=g)&&a%d==e};b=e}var h=parseInt(b,10);return function(a){return A(a)==
h}}},ka=d?function(a){var b=a.toLowerCase();b==dc&&(a=ec);return function(c){return e?c.getAttribute(a):c[a]||c[b]}}:function(a){return function(b){return b&&b.getAttribute&&b.hasAttribute(a)}},t=function(a,b){if(!a)return bf;b=b||{};var c=null;b.j||(c=g(c,h));b.tag||a.tag!=Oa&&(c=g(c,function(b){return b&&b.tagName==a.getTag()}));b.f||te(a.f,function(a,b){var d=new RegExp(Ma+a+La);c=g(c,function(a){return d.test(a.className)});c.count=b});b.i||te(a.i,function(a){var b=a.name;G[b]&&(c=g(c,G[b](b,
a.value)))});b.o||te(a.o,function(a){var b,d=a.attr;a.type&&l[a.type]?b=l[a.type](d,a.K):d.length&&(b=ka(d));b&&(c=g(c,b))});b.id||a.id&&(c=g(c,function(b){return!!b&&b.id==a.id}));c||gc in b||(c=bf);return c},la=function(a){return function(b,c,d){for(;b=b[k];)if(!q||h(b)){d&&!qb(b,d)||!a(b)||c.push(b);break}return c}},N=function(a){return function(b,c,d){for(b=b[k];b;){if(r(b)){if(d&&!qb(b,d))break;a(b)&&c.push(b)}b=b[k]}return c}},wf=function(a){a=a||bf;return function(b,d,e){for(var f=0,g=b[c];b=
g[f++];)r(b)&&(!e||qb(b,e))&&a(b,f)&&d.push(b);return d}},xf=function(a,b){for(var c=a.parentNode;c&&c!=b;)c=c.parentNode;return!!c},sc={},tc=function(c){var d=sc[c.query];if(d)return d;var e=c.V,e=e?e.D:p,f=t(c,{j:1}),g=Oa==c.tag,h=document.getElementsByClassName;if(e)h={j:1},g&&(h.tag=1),f=t(c,h),Pa==e?d=la(f):od==e?d=N(f):gb==e&&(d=wf(f));else if(c.id)f=!c.W&&g?bf:t(c,{j:1,id:1}),d=function(b,d){var e=(b?new af($e(b)):ne||(ne=new af)).ga(c.id);if(e&&f(e)&&(9==b.nodeType||xf(e,b)))return a(e,d)};
else if(h&&/\{\s*\[native code\]\s*\}/.test(String(h))&&c.f.length&&!b)var f=t(c,{j:1,f:1,id:1}),k=c.f.join(w),d=function(b,c){for(var d=a(0,c),e,g=0,h=b.getElementsByClassName(k);e=h[g++];)f(e,b)&&d.push(e);return d};else g||c.W?(f=t(c,{j:1,tag:1,id:1}),d=function(b,d){for(var e=a(0,d),g,h=0,k=b.getElementsByTagName(c.getTag());g=k[h++];)f(g,b)&&e.push(g);return e}):d=function(b,d){for(var e=a(0,d),f,g=0,h=b.getElementsByTagName(c.getTag());f=h[g++];)e.push(f);return e};return sc[c.query]=d},uc=
{},vc={},wc=function(b){var c=f(Q(b));if(1==c.length){var d=tc(c[0]);return function(a){if(a=d(a,[]))a.C=!0;return a}}return function(b){b=a(b);for(var d,e,f=c.length,g,h,k=0;k<f;k++){h=[];d=c[k];e=b.length-1;0<e&&(g={},h.C=!0);e=tc(d);for(var l=0;d=b[l];l++)e(d,h,g);if(!h.length)break;b=h}return h}},xc=!!document.querySelectorAll&&(!ze||T(Xa)),yc=function(a,c){if(xc){var e=vc[a];if(e&&!c)return e}if(e=uc[a])return e;var e=a.charAt(0),f=-1==a.indexOf(w);0<=a.indexOf(Ha)&&f&&(c=!0);if(!xc||c||-1!=
">~+".indexOf(e)||d&&-1!=a.indexOf(F)||b&&0<=a.indexOf(Qa)||-1!=a.indexOf(ab)||-1!=a.indexOf(nd)){var g=a.split(/\s*,\s*/);return uc[a]=2>g.length?wc(a):function(a){for(var b=0,c=[],d;d=g[b++];)c=c.concat(wc(d)(a));return c}}var h=0<=">~+".indexOf(a.charAt(a.length-1))?a+ba:a;return vc[a]=function(b){try{if(9!=b.nodeType&&!f)throw Error(p);var c=b.querySelectorAll(h);d?c.ca=!0:c.C=!0;return c}catch(e){return yc(a,!0)(b)}}},aa=0,yf=d?function(a){return e?a.getAttribute(Ab)||a.setAttribute(Ab,++aa)||
aa:a.uniqueID}:function(a){return a._uid||(a._uid=++aa)},qb=function(a,b){if(!b)return 1;var c=yf(a);return b[c]?0:b[c]=1},ma=Bb,zf=function(a){if(a&&a.C)return a;var b=[];if(!a||!a.length)return b;a[0]&&b.push(a[0]);if(2>a.length)return b;aa++;if(d&&e){var c=aa+p;a[0].setAttribute(ma,c);for(var f=1,g;g=a[f];f++)a[f].getAttribute(ma)!=c&&b.push(g),g.setAttribute(ma,c)}else if(d&&a.ca)try{for(f=1;g=a[f];f++)h(g)&&b.push(g)}catch(k){}else for(a[0]&&(a[0][ma]=aa),f=1;g=a[f];f++)a[f][ma]!=aa&&b.push(g),
g[ma]=aa;return b},zc=function(a,b){if(!a)return[];if(a.constructor==Array)return a;if(!rd(a))return[a];if(rd(b)&&(b=rd(b)?document.getElementById(b):b,!b))return[];b=b||document;var c=b.ownerDocument||b.documentElement;e=b.contentType&&b.contentType==Eb||we&&(b.doctype||c.toString()==tb)||!!c&&(d?c.xml:b.xmlVersion||c.xmlVersion);return(c=yc(a)(b))&&c.C?c:zf(c)};zc.i=G;return zc}();pd("goog.dom.query",cf,void 0);pd("goog.dom.query.pseudos",cf.i,void 0);var U=function(){this.reset()};U.prototype.reset=function(){this.Z={};this.required=!1;this.props={}};U.prototype.O=function(a,b,d){var c=this.Z[a];if(null==c||this.da(d,c))this.props[a]=b,this.Z[a]=d};for(var df=/#[a-z,A-Z,0-9-]+/g,ef=/\[[a-z,A-Z,0-9-=\s]+\]/g,ff=/:[a-z,A-Z,0-9-]+/g,gf=/\.[a-z,A-Z,0-9-]+/g,hf=[],jf=0;16>jf;jf++)for(var kf=0;16>kf;kf++)hf[16*jf+kf]=jf.toString(16)+kf.toString(16);M=U.prototype;
M.da=function(a,b){var d=this.T(a),c=this.T(b);return d.F>c.F||d.s>c.s||d.g>c.g||d.d>c.d?!0:!1};M.T=function(a){var b={F:0,s:0,g:0,d:0};if(null==a)return b.F=1,b;b.s+=(a.match(df)||[]).length;a=a.replace(df,p);b.g+=(a.match(ef)||[]).length;a=a.replace(ef,p);b.g+=(a.match(gf)||[]).length;a=a.replace(gf,p);b.g+=(a.match(ff)||[]).length;a=a.replace(ff,p);b.d+=(a.match(/[^\s]+/g)||[]).length;return b};M.a=function(a,b){return this.props[a]?this.props[a]:this.parent?this.parent.a(a)||b:b};
M.ba=function(){var a=this.a(Rb,0),b=this.a(Pb,0),d=this.a(Ob,0),c=this.a(Qb,0);this.required=0<this.a($c,0)||0<a||0<b||0<d||0<c};
M.L=function(){if(0!=this.required||this.parent&&0!=this.parent.required){var a=this.a(bd,0),b=this.a(cd,0),d=this.a($c,0),c=this.fa();c.innerHTML=p;var e=this.a(Zb,0),f=this.a(Wb,0),g=this.a(Xb,0),h=this.a(Yb,0),m=Math.round(c.A+g+h-1),l=Math.round(c.v+e+f-1),q=this.a(Rb,0),k=this.a(Pb,0),n=this.a(Ob,0),r=this.a(Qb,0),v=r+(g+e)/2,u=n+(g+f)/2,A=k+(h+f)/2,Y=q+(h+e)/2,Z=this.a(ad,J),G=[];Q(Z)!=J&&0<d&&(G=G.concat(this.ea(0+c.u,0+c.w,m,l,v,u,A,Y,a,b,d,Z)));a=this.a(Gb,J);b=this.a(Hb,null);d=this.a(Oc,
1);m=this.a(Ib,Ua);a!=id&&(G=G.concat(this.S(c.u+g/2,c.w+e/2,c.A+g/2+h/2,c.v+e/2+f/2,r,n,k,q,e,g,f,h,a,d,null)));b&&(G=G.concat(this.S(c.u+g/2,c.w+e/2,c.A+g/2+h/2,c.v+e/2+f/2,r,n,k,q,e,g,f,h,J,d,b,m)));a=this.a(Nb,J);b=this.a(Kb,J);d=this.a(Lb,J);m=this.a(Mb,J);l=this.a(Vb,H);v=this.a(Sb,H);u=this.a(Tb,H);A=this.a(Ub,H);(a+b+d+m).replace(/transparent/g,p)!=p&&(G=G.concat(this.na(c.u+g/2,c.w+e/2,c.A+g/2+h/2,c.v+e/2+f/2,r,n,k,q,e,g,f,h,a,d,b,m,l,u,v,A)));this.c.insertAdjacentHTML(Jb,G.join(p));this.parent?
(this.element.backingCanvas.style.visibility=pc,this.element.backingHoverCanvas.style.visibility=ld):(this.element.backingCanvas.style.visibility=ld,this.element.backingHoverCanvas&&(this.element.backingHoverCanvas.style.visibility=pc));this.element.style.border=p;this.element.style.background=p}};
M.ea=function(a,b,d,c,e,f,g,h,m,l,q,k){var n=.5;a-=this.a(Xb,0)/2;b-=this.a(Zb,0)/2;d+=this.a(Xb,0)/2+this.a(Yb,0)/2;c+=this.a(Zb,0)/2+this.a(Wb,0)/2;for(var r=[],v=0;v<q;v++){e+=.5;f+=.5;g+=.5;h+=.5;var n=.8*n,u;0==k.indexOf(Xc)?(u=k.lastIndexOf(D),u=k.substr(0,u+1)+n*k.substr(u+1,k.indexOf(C)-u-1)+C):u=Xc+this.aa(k)+D+n+C;r=r.concat(this.oa(a+m-v,b+l-v,d+2*v,c+2*v,e,f,g,h,2,u))}return r};
var lf=function(a){a=a.srcElement;for(var b=a.firstChild;null!=b;b=b.nextSibling)b.style.width=a.offsetWidth+I,b.style.height=a.offsetHeight+I};
U.prototype.fa=function(){var a=this.a(cd,0),b=this.a(bd,0),d=this.a($c,0),c=this.a(Zb,0),e=this.a(Wb,0),f=this.a(Xb,0),g=this.a(Yb,0),h=this.parent?this.element.backingHoverCanvas:this.element.backingCanvas,m=!1;null==h&&(m=!0);var l=this.element.style.cssText;mf[P(this.element)]=l;var q=this.element.offsetWidth,k=this.element.offsetHeight,n=this.element.currentStyle.paddingLeft||Va,r=this.element.currentStyle.paddingRight||Va,v=this.element.currentStyle.paddingBottom||Va,r=parseInt(r.substr(0,r.length-
2)),n=parseInt(n.substr(0,n.length-2)),v=parseInt(v.substr(0,v.length-2));if(m){h=document.createElement(kb);h.attachEvent(Nc,lf);var l=document.createElement(kb),u=this.element.currentStyle.styleFloat;this.B&&(l.style.marginLeft=this.element.currentStyle.marginLeft||Ra,l.style.marginRight=this.element.currentStyle.marginRight||Ra,l.style.marginTop=this.element.currentStyle.marginTop||Ra,l.style.marginBottom=this.element.currentStyle.marginBottom||Ra);l.style.paddingLeft=n;l.style.paddingRight=r;
l.style.paddingTop=r;l.style.paddingBottom=v;l.style.borderStyle=dd;l.style.borderColor=J;l.style.borderLeftWidth=f;l.style.borderRightWidth=g;l.style.borderTopWidth=c;l.style.borderBottomWidth=e;e=document.createElement(kb);e.style.position=Uc;e.style.marginLeft=E+n;e.style.marginRight=E+r;e.style.marginTop=E+r;e.style.marginBottom=E+v;e.style.top=E+c;e.style.left=E+f;this.element.parentElement.replaceChild(l,this.element);l.appendChild(e);e.appendChild(h);e.appendChild(this.element);l.style.styleFloat=
u;if(u==Bc||u==Yc)l.style.display=rc,this.element.style.styleFloat=H;l.style.position=this.element.currentStyle.position;this.parent?this.element.backingHoverCanvas=h:this.element.backingCanvas=h}this.c=h;h.v=k;h.A=q;h.u=d-b;h.w=d-a;h.style.position=Db;h.style.top=a-d+I;h.style.bottom=a-d+I;h.style.left=b-d+I;h.style.right=b-d+I;h.style.zIndex=-1E4+this.I();this.element.style.position=Uc;this.element.style.top=c+I;this.element.style.left=f+I;l=this.element.parentElement.parentElement;if(a=this.element.currentStyle[jc])l.style.styleFloat=
a;m&&(l.style.width=this.element.currentStyle.width,l.style.minWidth=this.element.currentStyle.minWidth,l.style.maxWidth=this.element.currentStyle.maxWidth,l.style.height=this.element.currentStyle.height,this.element.style.margin=0);return h};U.prototype.I=function(){if(!this.element)return-Number.MAX_VALUE;if(!this.depth){var a=this.element;for(this.depth=0;a!=document.body&&null!=a;)this.depth++,a=a.parentNode}return this.depth};
U.prototype.S=function(a,b,d,c,e,f,g,h,m,l,q,k,n,r,v,u){d=a+d;l=b+c;c=[db,n,ya,hd,xd,$a,this.c.offsetWidth,Sc,oc,this.c.offsetHeight+Tc,ha,10*(this.c.offsetWidth-1),w,10*(this.c.offsetHeight-1),B,qa,oa];m=[];m=m.concat([z]).concat(V(a,b+e));m=m.concat([y]).concat(V(a,l-2*f));m=m.concat(W(a+f,l-f,f,Math.PI,Math.PI/2));m=m.concat([y]).concat(V(d-2*g,l));m=m.concat(W(d-g,l-g,g,Math.PI/2,0));m=m.concat([y]).concat(V(d,b+h));m=m.concat(W(d-h,b+h,h,0,-.5*Math.PI));m=m.concat([y]).concat(V(a+e,b));m=m.concat(W(a+
e,b+e,e,-.5*Math.PI,Math.PI-.05));return n!=J||v&&v!=H?(a=[],a=v?a.concat([Ea,n,Ca,v,za,r,Aa,u==$b?Sa:Ta,Da]):a.concat([Ea,n,za,r,va]),c.concat(m.concat(a).concat([cb])).join(p)):[]};
U.prototype.na=function(a,b,d,c,e,f,g,h,m,l,q,k,n,r,v,u,A,Y,Z,G){d=a+d;c=b+c;var ka=[eb,hd,xd,$a,this.c.offsetWidth,Sc,oc,this.c.offsetHeight,Tc,ha,10*(this.c.offsetWidth-1),w,10*(this.c.offsetHeight-1),Ba,sa,oa],t=[],la=[Ga,na,10,B,ia,ua,ga],N=[];r!=J&&Y!=H&&(t=[],t=t.concat([z]).concat(V(a,b+e-m/2)),t=t.concat([y]).concat(V(a,c-f+q/2)),t=t.concat(W(a+f,c-f,f,Math.PI,Math.PI/2-.25)),N=N.concat([ka.join(p).replace(L,l).replace(K,r),t.join(p),la.join(p).replace(L,l).replace(K,r)]));v!=J&&Z!=H&&(t=
[],t=t.concat([z]).concat(V(a+f,c)),t=t.concat([y]).concat(V(d-g+k/2,c)),t=t.concat(W(d-g,c-g,g,Math.PI/2,0)),N=N.concat([ka.join(p).replace(L,q).replace(K,v),t.join(p),la.join(p).replace(L,q).replace(K,v)]));u!=J&&G!=H&&(t=[],t=t.concat([z]).concat(V(d,c-g)),t=t.concat([y]).concat(V(d,b+h-m/2)),t=t.concat(W(d-h,b+h,h,0,-.5*Math.PI)),N=N.concat([ka.join(p).replace(L,k).replace(K,u)+t.join(p)+la.join(p).replace(L,k).replace(K,u)]));n!=J&&A!=H&&(t=[],t=t.concat([z]).concat(V(d-h,b)),t=t.concat([y]).concat(V(a+
e,b)),t=t.concat(W(a+e,b+e,e,-.5*Math.PI+.25,Math.PI-.25)),N=N.concat([ka.join(p).replace(L,m).replace(K,n)+t.join(p)+la.join(p).replace(L,m).replace(K,n)]));return N};var nf=[[1,0,0],[0,1,0],[0,0,1]];function of(a,b){return{x:10*(a*nf[0][0]+b*nf[1][0]+nf[2][0])-5,y:10*(a*nf[0][1]+b*nf[1][1]+nf[2][1])-5}}
function W(a,b,d,c,e){d*=10;var f=of(a,b);c=of(a+Math.cos(c)*d-5,b+Math.sin(c)*d-5);a=of(a+Math.cos(e)*d-5,b+Math.sin(e)*d-5);return[ea,Math.round(f.x-d),D,Math.round(f.y-d),w,Math.round(f.x+d),D,Math.round(f.y+d),w,Math.round(c.x),D,Math.round(c.y),w,Math.round(a.x),D,Math.round(a.y)]}function V(a,b){var d=of(a,b);return[Math.round(d.x),D,Math.round(d.y)]}
U.prototype.oa=function(a,b,d,c,e,f,g,h,m,l){d=a+d;c=b+c;var q,k,n=1;l=String(l);if(l.substring(0,3)==Wc){k=l.indexOf(Ka,3);q=l.substring(k+1,l.indexOf(C,k+1)).split(D);k=Ha;for(var r=0;3>r;r++)k+=hf[Number(q[r])];4==q.length&&l.substr(3,1)==Cb&&(n=q[3])}else k=l;q=[k,n];l=q[0];n=[db,l,xa,hd,xd,$a,this.c.offsetWidth,Sc,oc,this.c.offsetHeight,Tc,ha,10*(this.c.offsetWidth-1),w,10*(this.c.offsetHeight-1),B,ra,m,B,pa,l,B,oa];k=[];l=[Fa,q[1],B,ja,na,10,B,ia,ta,m,Rc,fa,l,wa];k=[];k=k.concat([z]).concat(V(a,
b+e-m/2));k=k.concat([y]).concat(V(a,c-f+m/2));k=k.concat(W(a+f,c-f,f,Math.PI,Math.PI/2));k=k.concat([z]).concat(V(a+f,c));k=k.concat([y]).concat(V(d-g+m/2,c));k=k.concat(W(d-g,c-g,g,Math.PI/2,0));k=k.concat([z]).concat(V(d,c-g));k=k.concat([y]).concat(V(d,b+h-m/2));k=k.concat(W(d-h,b+h,h,0,-.5*Math.PI));k=k.concat([z]).concat(V(d-h,b));k=k.concat([y]).concat(V(a+e,b));k=k.concat(W(a+e,b+e,e,-.5*Math.PI,Math.PI-.05));return n.concat(k).concat(l)};
U.prototype.aa=function(a){a=a.charAt(0)==Ha?a.substring(1,a.length):a;if(3==a.length){var b=a.charAt(0),d=a.charAt(1);a=a.charAt(2);a=b+b+d+d+a+a}return[parseInt(a.substring(0,2),16),parseInt(a.substring(2,4),16),parseInt(a.substring(4,6),16)]};var X={},pf={},qf={},mf={},sf=function(){if(S&&T(7)){for(var a in X){var b=X[a];if(b){b.reset();var d=b.c;if(d){d.innerHTML=p;var c=b.element.parentElement,d=c.parentElement,e=d.parentElement,b=c.removeChild(b.element);e.replaceChild(b,d);b.style.cssText=mf[P(b)];b.backingCanvas=null}}}X={};rf()}},tf=5,uf=null,vf=function(){yd&&(sf(),yd=!1);uf&&window.clearTimeout(uf);0<tf--&&(uf=window.setTimeout(vf,1E3))},rf=function(){try{var a=document.styleSheets;xd=document.dir.toLowerCase()==Zc?Yc:Bc;for(var b=
{},d=0;d<a.length;d++){var c=a[d];try{for(var e=0;e<c.rules.length;e++){var f=c.rules[e],g=new Cd(f.style.cssText),h=Af(f.selectorText);if(g.U()&&!ce.test(h))for(var m=g.parse(),l=cf(h),q=0;q<l.length;q++){var k=l[q];Bf(k,b,g,m,h);(new Cd(k.style.cssText.toLowerCase())).parse()}if(g.U()&&ce.test(h))for(var n=h.replace(ce,p),l=cf(n),q=0;q<l.length;q++){var k=l[q],r=pf[P(k)];r||(r=new U,Cf(k,r),r.element=k,r.id=qc+d,function(a){Re(a,Ec,function(){pf[P(a)].L()},!0);Re(a,Dc,function(){X[P(a)].L()},!0)}(k));
var m=g.parse(),v;for(v in m)r.O(v,m[v],h);var u=X[P(k)];u&&(r.parent=u)}}}catch(Z){}}var A=document.getElementById(nc);if(A){var Y=qf[P(A)];null==Y?(g=new Cd(A.style.cssText.toLowerCase()),m=g.parse(),Bf(A,b,g,m),Df(A,m)):Bf(A,b,g,Y)}Ef(b)}catch(Z){}},Ff=function(){var a=new Cd(p),b=zd[Ad],d=X[P(b)];b.currentStyle.borderStyle!=H&&(d.props.ua=a.b(b.currentStyle.borderTopWidth)||0,d.props.ra=a.b(b.currentStyle.borderBottomWidth)||0,d.props.sa=a.b(b.currentStyle.borderLeftWidth)||0,d.props.ta=a.b(b.currentStyle.borderRightWidth)||
0);d.L();if(0==Ad){Bd=!1;a=document.activeElement;b=document.getElementsByTagName(nb);for(d=0;d<b.length;d++)b[d].setActive();a&&a.setActive()}0<Ad--&&setTimeout(Ff,1)},Ef=function(a){if(!Bd){Bd=!0;zd=[];for(var b in a)zd.push(a[b]);zd=zd.sort(function(a,b){var e=X[P(a)];return X[P(b)].I()-e.I()});Ad=zd.length-1;0<=Ad&&Ff()}},Bf=function(a,b,d,c,e){var f=X[P(a)];if(null==f){var g=Vc+b.length,f=new U;f.element=a;f.id=g;g=f;X[P(a)]=g}b[P(a)]=a;d.B&&(f.B=!0);d.ma()&&(f.required=!0);for(var h in c)f.O(h,
c[h],e);f.props.backgroundColor=f.props.backgroundColor||a.currentStyle.backgroundColor;if(a=pf[P(a)])a.parent=f;f.ba()},Df=function(a,b){qf[P(a)]=b},Cf=function(a,b){pf[P(a)]=b},Gf=/\.(?:(?:(?:tabs|footer|header)-(?:out|inn)er|date-header|Header)(?:\W|$)|(?:column-(?:left|right)-(?:out|inn)er|(?:content|main|post)-outer|widget|Blog)$)|#blog-pager$|.date-outer(|:\w*)$/,Af=function(a){a=a.split(D);for(var b=[],d=0;d<a.length;d++){var c=Q(a[d]);Gf.test(c)&&b.push(c)}return b.join(da)};
S&&T(7)&&!window.retrofitted&&(window.retrofitted=!0,document.namespaces.g_vml_||document.namespaces.add("g_vml_","urn:schemas-microsoft-com:vml","#default#VML"),document.createStyleSheet().cssText="g_vml_\\:fill, g_vml_\\:stroke, g_vml_\\:shape {behavior:url(#default#VML);}",document.attachEvent&&document.attachEvent("onreadystatechange",function(){document.readyState==fc&&(document.body.currentStyle.zoom!=Wa&&rf(),window.setTimeout(vf,1E3))}));pd("BLOG_CssPropertyParser",Cd,void 0);pd("BLOG_Retrofitter",U,void 0);pd("BLOG_IERetrofit",rf,void 0);pd("BLOG_ResetIERetrofit",sf,void 0); })()
