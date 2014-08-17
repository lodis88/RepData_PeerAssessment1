<!DOCTYPE html>
<!-- saved from url=(0014)about:internet -->
<html>
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8"/>
<meta http-equiv="x-ua-compatible" content="IE=9" >

<title>Output: html_document</title>

<style type="text/css">
body, td {
   font-family: sans-serif;
   background-color: white;
   font-size: 12px;
   margin: 8px;
}

tt, code, pre {
   font-family: 'DejaVu Sans Mono', 'Droid Sans Mono', 'Lucida Console', Consolas, Monaco, monospace;
}

h1 { 
   font-size:2.2em; 
}

h2 { 
   font-size:1.8em; 
}

h3 { 
   font-size:1.4em; 
}

h4 { 
   font-size:1.0em; 
}

h5 { 
   font-size:0.9em; 
}

h6 { 
   font-size:0.8em; 
}

a:visited {
   color: rgb(50%, 0%, 50%);
}

pre {	
   margin-top: 0;
   max-width: 95%;
   border: 1px solid #ccc;
   white-space: pre-wrap;
}

pre code {
   display: block; padding: 0.5em;
}

code.r, code.cpp {
   background-color: #F8F8F8;
}

table, td, th {
  border: none;
}

blockquote {
   color:#666666;
   margin:0;
   padding-left: 1em;
   border-left: 0.5em #EEE solid;
}

hr {
   height: 0px;
   border-bottom: none;
   border-top-width: thin;
   border-top-style: dotted;
   border-top-color: #999999;
}

@media print {
   * { 
      background: transparent !important; 
      color: black !important; 
      filter:none !important; 
      -ms-filter: none !important; 
   }

   body { 
      font-size:12pt; 
      max-width:100%; 
   }
       
   a, a:visited { 
      text-decoration: underline; 
   }

   hr { 
      visibility: hidden;
      page-break-before: always;
   }

   pre, blockquote { 
      padding-right: 1em; 
      page-break-inside: avoid; 
   }

   tr, img { 
      page-break-inside: avoid; 
   }

   img { 
      max-width: 100% !important; 
   }

   @page :left { 
      margin: 15mm 20mm 15mm 10mm; 
   }
     
   @page :right { 
      margin: 15mm 10mm 15mm 20mm; 
   }

   p, h2, h3 { 
      orphans: 3; widows: 3; 
   }

   h2, h3 { 
      page-break-after: avoid; 
   }
}

</style>

<!-- Styles for R syntax highlighter -->
<style type="text/css">
   pre .operator,
   pre .paren {
     color: rgb(104, 118, 135)
   }

   pre .literal {
     color: rgb(88, 72, 246)
   }

   pre .number {
     color: rgb(0, 0, 205);
   }

   pre .comment {
     color: rgb(76, 136, 107);
   }

   pre .keyword {
     color: rgb(0, 0, 255);
   }

   pre .identifier {
     color: rgb(0, 0, 0);
   }

   pre .string {
     color: rgb(3, 106, 7);
   }
</style>

<!-- R syntax highlighter -->
<script type="text/javascript">
var hljs=new function(){function m(p){return p.replace(/&/gm,"&amp;").replace(/</gm,"&lt;")}function f(r,q,p){return RegExp(q,"m"+(r.cI?"i":"")+(p?"g":""))}function b(r){for(var p=0;p<r.childNodes.length;p++){var q=r.childNodes[p];if(q.nodeName=="CODE"){return q}if(!(q.nodeType==3&&q.nodeValue.match(/\s+/))){break}}}function h(t,s){var p="";for(var r=0;r<t.childNodes.length;r++){if(t.childNodes[r].nodeType==3){var q=t.childNodes[r].nodeValue;if(s){q=q.replace(/\n/g,"")}p+=q}else{if(t.childNodes[r].nodeName=="BR"){p+="\n"}else{p+=h(t.childNodes[r])}}}if(/MSIE [678]/.test(navigator.userAgent)){p=p.replace(/\r/g,"\n")}return p}function a(s){var r=s.className.split(/\s+/);r=r.concat(s.parentNode.className.split(/\s+/));for(var q=0;q<r.length;q++){var p=r[q].replace(/^language-/,"");if(e[p]){return p}}}function c(q){var p=[];(function(s,t){for(var r=0;r<s.childNodes.length;r++){if(s.childNodes[r].nodeType==3){t+=s.childNodes[r].nodeValue.length}else{if(s.childNodes[r].nodeName=="BR"){t+=1}else{if(s.childNodes[r].nodeType==1){p.push({event:"start",offset:t,node:s.childNodes[r]});t=arguments.callee(s.childNodes[r],t);p.push({event:"stop",offset:t,node:s.childNodes[r]})}}}}return t})(q,0);return p}function k(y,w,x){var q=0;var z="";var s=[];function u(){if(y.length&&w.length){if(y[0].offset!=w[0].offset){return(y[0].offset<w[0].offset)?y:w}else{return w[0].event=="start"?y:w}}else{return y.length?y:w}}function t(D){var A="<"+D.nodeName.toLowerCase();for(var B=0;B<D.attributes.length;B++){var C=D.attributes[B];A+=" "+C.nodeName.toLowerCase();if(C.value!==undefined&&C.value!==false&&C.value!==null){A+='="'+m(C.value)+'"'}}return A+">"}while(y.length||w.length){var v=u().splice(0,1)[0];z+=m(x.substr(q,v.offset-q));q=v.offset;if(v.event=="start"){z+=t(v.node);s.push(v.node)}else{if(v.event=="stop"){var p,r=s.length;do{r--;p=s[r];z+=("</"+p.nodeName.toLowerCase()+">")}while(p!=v.node);s.splice(r,1);while(r<s.length){z+=t(s[r]);r++}}}}return z+m(x.substr(q))}function j(){function q(x,y,v){if(x.compiled){return}var u;var s=[];if(x.k){x.lR=f(y,x.l||hljs.IR,true);for(var w in x.k){if(!x.k.hasOwnProperty(w)){continue}if(x.k[w] instanceof Object){u=x.k[w]}else{u=x.k;w="keyword"}for(var r in u){if(!u.hasOwnProperty(r)){continue}x.k[r]=[w,u[r]];s.push(r)}}}if(!v){if(x.bWK){x.b="\\b("+s.join("|")+")\\s"}x.bR=f(y,x.b?x.b:"\\B|\\b");if(!x.e&&!x.eW){x.e="\\B|\\b"}if(x.e){x.eR=f(y,x.e)}}if(x.i){x.iR=f(y,x.i)}if(x.r===undefined){x.r=1}if(!x.c){x.c=[]}x.compiled=true;for(var t=0;t<x.c.length;t++){if(x.c[t]=="self"){x.c[t]=x}q(x.c[t],y,false)}if(x.starts){q(x.starts,y,false)}}for(var p in e){if(!e.hasOwnProperty(p)){continue}q(e[p].dM,e[p],true)}}function d(B,C){if(!j.called){j();j.called=true}function q(r,M){for(var L=0;L<M.c.length;L++){if((M.c[L].bR.exec(r)||[null])[0]==r){return M.c[L]}}}function v(L,r){if(D[L].e&&D[L].eR.test(r)){return 1}if(D[L].eW){var M=v(L-1,r);return M?M+1:0}return 0}function w(r,L){return L.i&&L.iR.test(r)}function K(N,O){var M=[];for(var L=0;L<N.c.length;L++){M.push(N.c[L].b)}var r=D.length-1;do{if(D[r].e){M.push(D[r].e)}r--}while(D[r+1].eW);if(N.i){M.push(N.i)}return f(O,M.join("|"),true)}function p(M,L){var N=D[D.length-1];if(!N.t){N.t=K(N,E)}N.t.lastIndex=L;var r=N.t.exec(M);return r?[M.substr(L,r.index-L),r[0],false]:[M.substr(L),"",true]}function z(N,r){var L=E.cI?r[0].toLowerCase():r[0];var M=N.k[L];if(M&&M instanceof Array){return M}return false}function F(L,P){L=m(L);if(!P.k){return L}var r="";var O=0;P.lR.lastIndex=0;var M=P.lR.exec(L);while(M){r+=L.substr(O,M.index-O);var N=z(P,M);if(N){x+=N[1];r+='<span class="'+N[0]+'">'+M[0]+"</span>"}else{r+=M[0]}O=P.lR.lastIndex;M=P.lR.exec(L)}return r+L.substr(O,L.length-O)}function J(L,M){if(M.sL&&e[M.sL]){var r=d(M.sL,L);x+=r.keyword_count;return r.value}else{return F(L,M)}}function I(M,r){var L=M.cN?'<span class="'+M.cN+'">':"";if(M.rB){y+=L;M.buffer=""}else{if(M.eB){y+=m(r)+L;M.buffer=""}else{y+=L;M.buffer=r}}D.push(M);A+=M.r}function G(N,M,Q){var R=D[D.length-1];if(Q){y+=J(R.buffer+N,R);return false}var P=q(M,R);if(P){y+=J(R.buffer+N,R);I(P,M);return P.rB}var L=v(D.length-1,M);if(L){var O=R.cN?"</span>":"";if(R.rE){y+=J(R.buffer+N,R)+O}else{if(R.eE){y+=J(R.buffer+N,R)+O+m(M)}else{y+=J(R.buffer+N+M,R)+O}}while(L>1){O=D[D.length-2].cN?"</span>":"";y+=O;L--;D.length--}var r=D[D.length-1];D.length--;D[D.length-1].buffer="";if(r.starts){I(r.starts,"")}return R.rE}if(w(M,R)){throw"Illegal"}}var E=e[B];var D=[E.dM];var A=0;var x=0;var y="";try{var s,u=0;E.dM.buffer="";do{s=p(C,u);var t=G(s[0],s[1],s[2]);u+=s[0].length;if(!t){u+=s[1].length}}while(!s[2]);if(D.length>1){throw"Illegal"}return{r:A,keyword_count:x,value:y}}catch(H){if(H=="Illegal"){return{r:0,keyword_count:0,value:m(C)}}else{throw H}}}function g(t){var p={keyword_count:0,r:0,value:m(t)};var r=p;for(var q in e){if(!e.hasOwnProperty(q)){continue}var s=d(q,t);s.language=q;if(s.keyword_count+s.r>r.keyword_count+r.r){r=s}if(s.keyword_count+s.r>p.keyword_count+p.r){r=p;p=s}}if(r.language){p.second_best=r}return p}function i(r,q,p){if(q){r=r.replace(/^((<[^>]+>|\t)+)/gm,function(t,w,v,u){return w.replace(/\t/g,q)})}if(p){r=r.replace(/\n/g,"<br>")}return r}function n(t,w,r){var x=h(t,r);var v=a(t);var y,s;if(v){y=d(v,x)}else{return}var q=c(t);if(q.length){s=document.createElement("pre");s.innerHTML=y.value;y.value=k(q,c(s),x)}y.value=i(y.value,w,r);var u=t.className;if(!u.match("(\\s|^)(language-)?"+v+"(\\s|$)")){u=u?(u+" "+v):v}if(/MSIE [678]/.test(navigator.userAgent)&&t.tagName=="CODE"&&t.parentNode.tagName=="PRE"){s=t.parentNode;var p=document.createElement("div");p.innerHTML="<pre><code>"+y.value+"</code></pre>";t=p.firstChild.firstChild;p.firstChild.cN=s.cN;s.parentNode.replaceChild(p.firstChild,s)}else{t.innerHTML=y.value}t.className=u;t.result={language:v,kw:y.keyword_count,re:y.r};if(y.second_best){t.second_best={language:y.second_best.language,kw:y.second_best.keyword_count,re:y.second_best.r}}}function o(){if(o.called){return}o.called=true;var r=document.getElementsByTagName("pre");for(var p=0;p<r.length;p++){var q=b(r[p]);if(q){n(q,hljs.tabReplace)}}}function l(){if(window.addEventListener){window.addEventListener("DOMContentLoaded",o,false);window.addEventListener("load",o,false)}else{if(window.attachEvent){window.attachEvent("onload",o)}else{window.onload=o}}}var e={};this.LANGUAGES=e;this.highlight=d;this.highlightAuto=g;this.fixMarkup=i;this.highlightBlock=n;this.initHighlighting=o;this.initHighlightingOnLoad=l;this.IR="[a-zA-Z][a-zA-Z0-9_]*";this.UIR="[a-zA-Z_][a-zA-Z0-9_]*";this.NR="\\b\\d+(\\.\\d+)?";this.CNR="\\b(0[xX][a-fA-F0-9]+|(\\d+(\\.\\d*)?|\\.\\d+)([eE][-+]?\\d+)?)";this.BNR="\\b(0b[01]+)";this.RSR="!|!=|!==|%|%=|&|&&|&=|\\*|\\*=|\\+|\\+=|,|\\.|-|-=|/|/=|:|;|<|<<|<<=|<=|=|==|===|>|>=|>>|>>=|>>>|>>>=|\\?|\\[|\\{|\\(|\\^|\\^=|\\||\\|=|\\|\\||~";this.ER="(?![\\s\\S])";this.BE={b:"\\\\.",r:0};this.ASM={cN:"string",b:"'",e:"'",i:"\\n",c:[this.BE],r:0};this.QSM={cN:"string",b:'"',e:'"',i:"\\n",c:[this.BE],r:0};this.CLCM={cN:"comment",b:"//",e:"$"};this.CBLCLM={cN:"comment",b:"/\\*",e:"\\*/"};this.HCM={cN:"comment",b:"#",e:"$"};this.NM={cN:"number",b:this.NR,r:0};this.CNM={cN:"number",b:this.CNR,r:0};this.BNM={cN:"number",b:this.BNR,r:0};this.inherit=function(r,s){var p={};for(var q in r){p[q]=r[q]}if(s){for(var q in s){p[q]=s[q]}}return p}}();hljs.LANGUAGES.cpp=function(){var a={keyword:{"false":1,"int":1,"float":1,"while":1,"private":1,"char":1,"catch":1,"export":1,virtual:1,operator:2,sizeof:2,dynamic_cast:2,typedef:2,const_cast:2,"const":1,struct:1,"for":1,static_cast:2,union:1,namespace:1,unsigned:1,"long":1,"throw":1,"volatile":2,"static":1,"protected":1,bool:1,template:1,mutable:1,"if":1,"public":1,friend:2,"do":1,"return":1,"goto":1,auto:1,"void":2,"enum":1,"else":1,"break":1,"new":1,extern:1,using:1,"true":1,"class":1,asm:1,"case":1,typeid:1,"short":1,reinterpret_cast:2,"default":1,"double":1,register:1,explicit:1,signed:1,typename:1,"try":1,"this":1,"switch":1,"continue":1,wchar_t:1,inline:1,"delete":1,alignof:1,char16_t:1,char32_t:1,constexpr:1,decltype:1,noexcept:1,nullptr:1,static_assert:1,thread_local:1,restrict:1,_Bool:1,complex:1},built_in:{std:1,string:1,cin:1,cout:1,cerr:1,clog:1,stringstream:1,istringstream:1,ostringstream:1,auto_ptr:1,deque:1,list:1,queue:1,stack:1,vector:1,map:1,set:1,bitset:1,multiset:1,multimap:1,unordered_set:1,unordered_map:1,unordered_multiset:1,unordered_multimap:1,array:1,shared_ptr:1}};return{dM:{k:a,i:"</",c:[hljs.CLCM,hljs.CBLCLM,hljs.QSM,{cN:"string",b:"'\\\\?.",e:"'",i:"."},{cN:"number",b:"\\b(\\d+(\\.\\d*)?|\\.\\d+)(u|U|l|L|ul|UL|f|F)"},hljs.CNM,{cN:"preprocessor",b:"#",e:"$"},{cN:"stl_container",b:"\\b(deque|list|queue|stack|vector|map|set|bitset|multiset|multimap|unordered_map|unordered_set|unordered_multiset|unordered_multimap|array)\\s*<",e:">",k:a,r:10,c:["self"]}]}}}();hljs.LANGUAGES.r={dM:{c:[hljs.HCM,{cN:"number",b:"\\b0[xX][0-9a-fA-F]+[Li]?\\b",e:hljs.IMMEDIATE_RE,r:0},{cN:"number",b:"\\b\\d+(?:[eE][+\\-]?\\d*)?L\\b",e:hljs.IMMEDIATE_RE,r:0},{cN:"number",b:"\\b\\d+\\.(?!\\d)(?:i\\b)?",e:hljs.IMMEDIATE_RE,r:1},{cN:"number",b:"\\b\\d+(?:\\.\\d*)?(?:[eE][+\\-]?\\d*)?i?\\b",e:hljs.IMMEDIATE_RE,r:0},{cN:"number",b:"\\.\\d+(?:[eE][+\\-]?\\d*)?i?\\b",e:hljs.IMMEDIATE_RE,r:1},{cN:"keyword",b:"(?:tryCatch|library|setGeneric|setGroupGeneric)\\b",e:hljs.IMMEDIATE_RE,r:10},{cN:"keyword",b:"\\.\\.\\.",e:hljs.IMMEDIATE_RE,r:10},{cN:"keyword",b:"\\.\\.\\d+(?![\\w.])",e:hljs.IMMEDIATE_RE,r:10},{cN:"keyword",b:"\\b(?:function)",e:hljs.IMMEDIATE_RE,r:2},{cN:"keyword",b:"(?:if|in|break|next|repeat|else|for|return|switch|while|try|stop|warning|require|attach|detach|source|setMethod|setClass)\\b",e:hljs.IMMEDIATE_RE,r:1},{cN:"literal",b:"(?:NA|NA_integer_|NA_real_|NA_character_|NA_complex_)\\b",e:hljs.IMMEDIATE_RE,r:10},{cN:"literal",b:"(?:NULL|TRUE|FALSE|T|F|Inf|NaN)\\b",e:hljs.IMMEDIATE_RE,r:1},{cN:"identifier",b:"[a-zA-Z.][a-zA-Z0-9._]*\\b",e:hljs.IMMEDIATE_RE,r:0},{cN:"operator",b:"<\\-(?!\\s*\\d)",e:hljs.IMMEDIATE_RE,r:2},{cN:"operator",b:"\\->|<\\-",e:hljs.IMMEDIATE_RE,r:1},{cN:"operator",b:"%%|~",e:hljs.IMMEDIATE_RE},{cN:"operator",b:">=|<=|==|!=|\\|\\||&&|=|\\+|\\-|\\*|/|\\^|>|<|!|&|\\||\\$|:",e:hljs.IMMEDIATE_RE,r:0},{cN:"operator",b:"%",e:"%",i:"\\n",r:1},{cN:"identifier",b:"`",e:"`",r:0},{cN:"string",b:'"',e:'"',c:[hljs.BE],r:0},{cN:"string",b:"'",e:"'",c:[hljs.BE],r:0},{cN:"paren",b:"[[({\\])}]",e:hljs.IMMEDIATE_RE,r:0}]}};
hljs.initHighlightingOnLoad();
</script>




</head>

<body>
<hr/>

<p>Marcos Lodis
Input: activity.csv</p>

<h2>Output: html_document</h2>

<h1>Reproducible Research: Peer Assessment 1</h1>

<p>Loading and preprocessing the data</p>

<pre><code class="r">setwd(&quot;C:\\Users\\Marcos\\Desktop\\peer assigment 1&quot;)
data&lt;-read.csv(&quot;activity.csv&quot;,header=T)
</code></pre>

<p>Process the raw data</p>

<pre><code class="r">data$date&lt;-as.Date(data$date)
data.bydate&lt;-subset(data,date==as.Date(&quot;2012-10-01&quot;))[,1]
r.names&lt;-subset(data,date==as.Date(&quot;2012-10-01&quot;))[,3]
for(i in 1:60){
data.temp&lt;-subset(data,date==as.Date(i,origin=&quot;2012-10-01&quot;))[,1]
  data.bydate&lt;-data.frame(data.bydate,data.temp)
}
colnames(data.bydate)&lt;-c(1:61)
row.names(data.bydate)&lt;-r.names
</code></pre>

<p>Histogram of the total number of steps taken each day</p>

<pre><code class="r">data.dailystep&lt;-colSums(data.bydate,na.rm=T)
hist(data.dailystep,breaks=20)
</code></pre>

<p><img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAfgAAAH4CAMAAACR9g9NAAAAkFBMVEX9/v0AAAAAADkAAGUAOTkAOWUAOY8AZo8AZrU5AAA5ADk5AGU5OY85ZrU5j485j9plAABlADllAGVlOQBlOY9lZjllZmVltbVltf2POQCPOTmPOWWPjzmPtY+P27WP2/21ZgC1Zjm1tWW1/rW1/tq1/v3ajzna24/a/rXa/tra/v39tWX924/9/rX9/tr9/v00UiBYAAAAMHRSTlP//////////////////////////////////////////////////////////////wBipdB4AAAACXBIWXMAAAsSAAALEgHS3X78AAAPOUlEQVR4nO2di3riyBFGV/bGsbOTwEx2E5hNArlANub2/m8XtS4YjCgZqWlXV53zzQxQ+lXq4aALGMk/HMAlP3z2AOBzQLxTEO8UxDsF8U5BvFMQ7xTEOwXxTkG8UxDvFMQ7BfFOQbxTEO8UxDsF8U5BvFMQ7xTEOwXxTkG8UxDvFMQ7BfFOyUn8bvq4Ohz288dVfa9lORvRdPtSPCzelvD0Kvc9TYRRnI8kxoASkaf4s/KyGPM8n819Jr6z7/lLox2T0FIreYqv7pXravG42s+Long+HNblzeQQJheP/y7t7OcPv5Tr8qYsl2v0pvh9WV+VodZJna/mrlWGu38NWutZmr7N/IeORLvG/ye8Ejdls8sBzarh/iuUP+UZE8hX/G5aBGn/q5/nZXhQ3lZP+48vQXyY+lsdet0ULY2CJv8mvroX7p/1bR4cXxmnidd2U78uBS8fFl0DmrzN9ZnPXAd5iW/dhad7+9I8mWHLun2p1sCHxfalNLsuKvHP7WyPq00RZihmIRJqx/xxu3ycsZ3lOKXdml8k2r/bl+fwanw3oPJBqJbjmISRa9v65yu+ehSUhOd5U1kuV73qzq7e1C/amYL458pVWz3mj3qPM7azNFOaB12JVvx+Xm5Zng/vBlQRdhmhtK52Q5rIS/zFPr5o1tlr4qvMUfzby0EQ387SrLhvu4eLxPGofv3w95fJ4d2AEB+Njrdzy0Zd16Y+KF5Xx1yX4oVNfTtLNeX4oCtxFH/ylvBtQM12n039eM7Fn6yZ3Qd3wcWm6F7jj/mj+ONBWDtL1bd9UG/R3yWO4ssppeauATUHmRzcjaJjU99szsun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" alt="plot of chunk unnamed-chunk-3"/> </p>

<p>Mean and Median of the total number of steps taken each day</p>

<pre><code class="r">mean(data.dailystep,na.rm=T)
</code></pre>

<pre><code>## [1] 9354
</code></pre>

<pre><code class="r">median(data.dailystep,na.rm=T)
</code></pre>

<pre><code>## [1] 10395
</code></pre>

<p>Average daily activity pattern based on 5-minute interval</p>

<pre><code class="r">data.dailyave&lt;-rowSums(data.bydate,na.rm=T)/61
plot(data.dailyave,type=&quot;l&quot;,xlab=&quot;Interval&quot;,ylab=&quot;Number of Steps&quot;)
</code></pre>

<p><img src="data:image/png;base64,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" alt="plot of chunk unnamed-chunk-5"/> </p>

<pre><code class="r">max(data.dailyave,na.rm=T)
</code></pre>

<pre><code>## [1] 179.1
</code></pre>

<pre><code class="r">which.max(data.dailyave)
</code></pre>

<pre><code>## 835 
## 104
</code></pre>

<pre><code class="r">data.dailyave[104]
</code></pre>

<pre><code>##   835 
## 179.1
</code></pre>

<p>The 104th Interval with index 835,on average across all the days in the dataset, contains the maximum number of steps 179.1.</p>

<p>Calculate and report the total number of missing values in the dataset.
Fill the missing values in the dataset with the mean for that 5-minute interval</p>

<pre><code class="r">count&lt;-0
for(i in 1:288)
  for(j in 1:61){
    if(is.na(data.bydate[i,j])){
      count=count+1
      data.bydate[i,j]=data.dailyave[j]
    }
    }
count
</code></pre>

<pre><code>## [1] 2304
</code></pre>

<p>The total number of missing values in the dataset is 2304.</p>

<p>Histogram, Mean, and Median of the total number of steps taken each day for the new set of data with NA replaced</p>

<pre><code class="r">data.dailystep&lt;-colSums(data.bydate)
mean(data.dailystep)
</code></pre>

<pre><code>## [1] 9375
</code></pre>

<pre><code class="r">median(data.dailystep)
</code></pre>

<pre><code>## [1] 10395
</code></pre>

<pre><code class="r">hist(data.dailystep,breaks=20)
</code></pre>

<p><img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAfgAAAH4CAMAAACR9g9NAAAAkFBMVEX9/v0AAAAAADkAAGUAOTkAOWUAOY8AZo8AZrU5AAA5ADk5AGU5OY85ZrU5j485j9plAABlADllAGVlOQBlOY9lZjllZmVltbVltf2POQCPOTmPOWWPjzmPtY+P27WP2/21ZgC1Zjm1tWW1/rW1/tq1/v3ajzna24/a/rXa/tra/v39tWX924/9/rX9/tr9/v00UiBYAAAAMHRSTlP//////////////////////////////////////////////////////////////wBipdB4AAAACXBIWXMAAAsSAAALEgHS3X78AAAPOUlEQVR4nO2di3riyBFGV/bGsbOTwEx2E5hNArlANub2/m8XtS4YjCgZqWlXV53zzQxQ+lXq4aALGMk/HMAlP3z2AOBzQLxTEO8UxDsF8U5BvFMQ7xTEOwXxTkG8UxDvFMQ7BfFOQbxTEO8UxDsF8U5BvFMQ7xTEOwXxTkG8UxDvFMQ7BfFOyUn8bvq4Ohz288dVfa9lORvRdPtSPCzelvD0Kvc9TYRRnI8kxoASkaf4s/KyGPM8n819Jr6z7/lLox2T0FIreYqv7pXravG42s+Long+HNblzeQQJheP/y7t7OcPv5Tr8qYsl2v0pvh9WV+VodZJna/mrlWGu38NWutZmr7N/IeORLvG/ye8Ejdls8sBzarh/iuUP+UZE8hX/G5aBGn/q5/nZXhQ3lZP+48vQXyY+lsdet0ULY2CJv8mvroX7p/1bR4cXxmnidd2U78uBS8fFl0DmrzN9ZnPXAd5iW/dhad7+9I8mWHLun2p1sCHxfalNLsuKvHP7WyPq00RZihmIRJqx/xxu3ycsZ3lOKXdml8k2r/bl+fwanw3oPJBqJbjmISRa9v65yu+ehSUhOd5U1kuV73qzq7e1C/amYL458pVWz3mj3qPM7azNFOaB12JVvx+Xm5Zng/vBlQRdhmhtK52Q5rIS/zFPr5o1tlr4qvMUfzby0EQ387SrLhvu4eLxPGofv3w95fJ4d2AEB+Njrdzy0Zd16Y+KF5Xx1yX4oVNfTtLNeX4oCtxFH/ylvBtQM12n039eM7Fn6yZ3Qd3wcWm6F7jj/mj+ONBWDtL1bd9UG/R3yWO4ssppeauATUHmRzcjaJjU99szsun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" alt="plot of chunk unnamed-chunk-7"/> 
The mean is large. The median and histogram is the same.
This is because we use daily average in that 5-minutes interval to replace the missing date.</p>

<p>Create a new factor variable in the dataset with two levels - &ldquo;weekday&rdquo; and &ldquo;weekend&rdquo; indicating whether a given date is a weekday or weekend day.</p>

<pre><code class="r">data$week&lt;-&quot;weekday&quot;
for(i in 288*61){
  ##data[i,]$Week=weekdays(data[i,]$date)
}
</code></pre>

<p>5-minute interval (x-axis) and the average number of steps taken, averaged across all weekday days or weekend days (y-axis).</p>

<pre><code class="r">data.weekday&lt;-data.bydate[,1:5]
data.weekend&lt;-data.bydate[,6:7]
for(i in 1:54){
  if(i%%7==6|i%%7==0)
    data.weekend&lt;-data.frame(data.weekend,data.bydate[,i])
  else data.weekday&lt;-data.frame(data.weekday,data.bydate[,i])
}
colnames(data.weekend)&lt;-c(1:16)
colnames(data.weekday)&lt;-c(1:45)
data.weekendave&lt;-rowSums(data.weekend)/16
plot(data.weekendave,type=&quot;l&quot;,xlab=&quot;Interval&quot;,ylab=&quot;Number of Steps&quot;,main=&quot;Weekend&quot;)
</code></pre>

<p><img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAfgAAAH4CAMAAACR9g9NAAAAjVBMVEX9/v0AAAAAADkAAGUAOWUAOY8AZrU5AAA5ADk5AGU5OQA5OTk5OWU5OY85ZrU5j485j9plAABlADllAGVlOQBlZmVlj49ltbVltf2POQCPOTmPOWWPZgCPtY+P27WP29qP2/21ZgC1tWW124+1/rW1/v3ajzna/rXa/tra/v39tWX924/9/rX9/tr9/v0dhvyZAAAAL3RSTlP/////////////////////////////////////////////////////////////AFqlOPcAAAAJcEhZcwAACxIAAAsSAdLdfvwAABJZSURBVHic7Z2JeuO2GUUDu7aatk6lmbSVZprGamMl1oL3f7xyXwEQG4nlv2fmk8QFlyCPSII0Sf3AAUl+CF0BEAaIJwrEEwXiiQLxRIF4okA8USCeKBBPFIgnCsQTBeKJAvFEgXiiQDxRIJ4oEE8UiCcKxBMF4okC8USBeKJAPFEgnigQTxQy4h+np3fOz+zlk98PxcuU++H5Q1FcWCZlyIgvnB8LfazQf2Wv88EQnytXtue33T93R34pPhUvrPgm8O5DKf5xKj81PR6n5/8yVn4bit7sXxCfKrfdy+f16T+HPT8Xa/2Zlex596EUfymFtz1K3QWv7QeIT5RiDf44v/xxei0/lN8CPvpQiP/fbl9/P6oehe99sZl4+bztitX+AvHJcn769fTKL8+/HV4LoRVP792H++HpL+UK3/WoWoPlrr1qEmAfny4XVu7gr0+/7PZC8azaow/EF10QnwG33V+rdfgfxWu1Qa97Nh/qffy+79GJx6Y+cYp1ujBY7LrLlvq5bbC1H0rx1SFd26MTj8Zd6pyr4/f6tfJbuWw+VNKvbTu/aeDVW/jS/N+xqQdZAPFEgXiiQDxRIJ4oEE8UiCcKxBMF4okC8USBeKJAPFEgnigQTxSIJwrEEwXiiQLxRIF4okA8USCeKBBPFIgniot4BmJmRfEOZcHaQDxRIJ4oEE8UiCcKxBMF4okC8USBeKJAPFEgnigQTxTa4hOo4lpAPFEgnigQTxSIJwrEEwXiiQLxRIF4okA8USCeKBBPFIgnCsQTBeKJAvFEgXiiQDxRIJ4opMUv3SSeMxBPFIgnCsQTBeKJAvFEgXiiQDxRIJ4oEE8UiCcKxBMF4okC8USBeKJAPFGcxd921dPPnz9MoyMA4qUsin+cjtX79eXTMDoCWAJ1XAtX8fevH6N3/egIgHgpWONzxXkffz8kvI9PoI5rQbtVn0Ad1wLiieKjcVdu7ee7+AQWKsRL0RFfNehvP5lGRwDES9ERf3v7HB3Oaf6kXQRAvJRl8YenX7+Xa/wbDueSwr1x9zixV37F4VxioFVPFIgnCsQTBeKJ4t6qb47d5q27+BcqxEtZXuMfp71ddARAvBSNTf39y7tVdEhY+xZxHVeG5j4e4iGeKkTF13WDeCkQnysQTxSIJwrEE4Wo+LpyEC8F4nMF4okC8USBeMegVIF4x6BUgXjHoFSBeMegVIF4x6BUgXjHoFSBeMegVIF4x6BUgXinnIjncQGId8qJeB4XgHinnIjncQGId8qJeB4XgHjDguPOiOdxAYg3LDjujHgeF4B4w4LjzojncQGINyw47ox4HheAeMOC486I53EBiDcsOO6MeB4XgHjDguPOiOdxAYg3Kgfx7tEhYXXtIF4KxI/LQbx7dEBq6a1+k4IQ7x4dEIiHeMOC4/FTviED4o0KQrx7dEAgHuJNCzJFZ1JAvFlBiHeODgjEQ7xpQYh3jg4IxEO8aTmId44OCMRDvGk5v+IDLiKINysH8c7RAYF4iDctB/HO0QHxJ95xJiF+WyzFN8VGPRzFh1tGEG9cbNSDDQeaVwTiN8WH+D6j7zavCMRvihfxDOLtogMyWFtNKuldfMgzfxBvXKztYBBvFR0QiId4iBcD8fNibQfE20UHBOIhHuLFQPy8WNsB8XbRAYF4iId4MRA/L9Z2QLxddEA8iGcc4i2jAxKHeAbxW7OCeIu/s0H81rDmBeLlQPykHMQ7R4fDl/hRN8TrRocjFvEs5DKCeLNyEO8cHQ6I57riLy+fF8aOXqODwdpXiJdTi79/eS/+33788BkdjLF4g1oqxZvPbgriv34U6zzEc2ri+YU9vV/z3NTbi+cExK8RHQy/4lnbDfGa0cGA+Grq6sGN+MeJMfbqNzoYUYhvpQdbSFriH6d98XoRmr/tWMnzvOEH8eqsBMQXrfrudcLjVDf5ri+fhtGh6ExBvIK2Vf/KJWt8+20QfCsgXp2VgPj7gTHJBh1rfNudo3gVzZcinX08xLcVUJHh4RzEtxVQ0R/Ovfz+5d1rdCj8iueriJdm+Vumuodzt7dPwW6cJ3g4B/E6Sd3hXCEeh3Ocmvh6jb+I1njB4Rxr8VZJr4zFmyxKeuLrU7bCLX3qazzEi8n+cC6YeJaCeMUpW/voUHgW373mJ747byfc1ltHhwLidZKGa7zn6FBAvE5S9mfuLMUPitqKH5aW1NFggDE64u+H1/I8jaD9pvz7DcSrslIQf95XR23iCzHqizQsokPhT/zwo4N4QcE4xJd7+PLSasme/i47hw/xqqxExJdn7TK5rj4B8fKTnhtv6o/V9vxseLVlGuL1qzn8ntAQXzTgXj7LFp7X6FBAvE5S/odzW4tvAyB+a6IQzzibfBgNlYv3tlAhHuJFtK36FaJDEVp8E5OE+N+yPFc/d6hR0FV8d4q+u0rTWLyf5ap1OCc9K+sSHQqIH0xJSs5/nYtDvPmmfkPxq0SHIjbxPGbx8mvu7KNDEV48S0Z8c5t0ZlfgWImfHwqYim/kJSE+z2vuIF5Bvmv84K43o4IexNf/UhCf4z4+jPjByEmIXyM6FBA/m6qAvMQP2+Uy8fJaQ7yf6ABA/HRKUiB+OmRV8Swy8bmcso1F/NjfVDyLR/zjm+HDMHSiAwDxs5rIGD31Kvm/zmmIV/zBWyK+S9WZ38TErxIdAIif1UQGxE9KxyDey4LVE5/JU68SEa9oL2wsXvXUK+voAKwnnnEj8crDuYjEK556ZR8dgODiRbJF4qVZQdb49P86B/HCqYrI669zIz1BxUt6Rid+jegAjNtUg/1tP4ai1luI592lWZIAiLcB4heq0pPXb9IkL74asm3jjudw6RXEL1SlJ6+LLRfFKzayAcTPx95afPn4I9mvUFlHB2Bl8csznJZ4xRPNXKIDELt4xjXEW/y0oXZVeoi16nXFs2n/XMVfs1jjJ1c8RSteOJVuhC3FSx9l5xK9PRLx0yUvL969khGfxzV3EL9UlZ72lyZljy11iN6etcUvz7Fa/CAkGvE57+MhXgD28cPi3SsZ8djH863Es+nHyajYx5sTXLx4eMTiM7mufmXxy3OcnPhVorcH4hfr0pGZ+OHmGOJVZLaph/iFunQM13jTFh7EixOkfWMVn/yFGEmIH3yMRfyVxKZeXm2C4pt9/NFr9PZMxHPxJ4gvyblVz2ef5lInxYXjrCZ+Pn4zho8lC/FxiR9lBhafzTV3q4tfmmW1eDbpF1x8wyX/ffx64lVbhLjF3w+G63uc4qVt+f7D5uJFhaMRf2Hmf59LTjxbUTxTDBWLFwneWrzF6r4cvT0QP5+ojEr81WJ1X47engXxDOJ7cmvVBxOv8hWr+JWitwfi5xOVAfGzsWbjQLxZ9PaoxbOFxh3Ee4reniXxAqmT0jwC8arJGADxEC8iO/Ec4rUyIH4yFsQ7R28OG7xyr+K7X4RWiOfyCyggfl1WFD/PFIVDfBggXhAlIz/xgs7xNwLiSyB+Or5SvEAVxAcnoHjGIT4cEC+IkpGx+OmA1cUvTB/i1yJ98UtVNAHiIxXPBGkQb0Xy4hWTMQfiLcSzyQCIN4neHIgXhwmB+GlxiG+47WRX4EJ8M3D40MKF5HFmzOIfp/qOOsHvj0I8z1h8+3wUwXNS8hRfvkM8wTXeTDzjuYpXPAotLfFsaTSp+GGzzVb8VHMC4q2jNycr8c4LdwXxrMWqQuvhJn44HOLrRl25tRf8CiXEj8WrKpak+KpBf/vJNHpr5NWB+Dk64m9vnykcziUlXnhDfVziD0+/fi/X+LfYD+cSFD8pF5X46ifGX4WPO01UvGTEuMS7t5xXaNVrRm9N6uIZxNuhqM54sScg3sMvSkM8T0M8g3hLQoivg5fFz9vwEO8NiJ9VTQHEz/qGEc/GriFenwDiG3ka4mepC+Ldly7Ec9/ie2X1y+JvSkD8qsQufuJ1LJ7Ntu4Qr4tKPHMTP/4I8Q5lVyAx8fOJQrwdm4jvhg7FL7XBIX5VthM/We0hPiyhxM8b5PNoHfHCEeyBeA7xAiiKF4/pJH6hZmw+EsR7w0C8aFRt8YPL5SA+BvyJnw5eUTwbdEK8HSmK5xDvjlL88t88mXywUHyvalm8YCSI9wbEm5SnLF62oL2LF40E8d6AeJPyhMVLT5HqiB/+gR3iw6IvnkcgfhIN8fa4iVe1/XyIl5zWHa74EG9HMPF6S2JZ/HSI2/KFeC4WP+izdH4H4o2iN0ZVG4ifkb54NnkXjgPxU8iIn+3QFeJlk+Ac4jWiN0JLvKAlF4f4pqhomOPNNBDPVeK79j3Ee4veiHb5hBRvUk9hNsSb4yS+va1BvUMdie/LQnxQIF4yPfVgiNeQCPFG0RuRinjJ2BBvi554LhDfaod4v9Fr0wp3FS+6FFI4pWFZiA9Hex0NxBtMriNl8XUFIN5kch0QbyW+s29UX3lfiDeaPBu8bdW4q3vYiFdlQ7zR5LcSP89jS1PUjxq8Cge5BUuB+FGI7qQ9i1ftBZyC5aQrnnGIXwyWQ1N806Nrp5nuUD2Kb7+EskFOuQrIiBcVHoo3nbZxGVUWxJtNnfVv9uIlYyxN2xsQbz71oXhlZSB+RmLi2ehjMPE+gXjDSTqKb5d3cPHzludwiFOsiqTFD1ZciDcsTEO8IGciPiDycwgQL5rkWLxhXfqFDfHeo9cgR/Hyk0cQL5okxC+kqgenJr6fZj7isanXmKRIvKJdLM2JSrwMiO8nCfGeCmci3rQqEE9efMxAfD9JiPdUGOIjBuL7SUK8p8IQHzFs9GZXWEYe4o1rkpZ4q7rmKp41L6zrMMpJSrxVZSFemAPxFpGa0WswEW8tMA3x3Uza1DZz8ZZ1SEa83RnpuqyStMQPFgEt8aLqLsxBhuKHvwoC8fKySiIUr4hl9bKAeC7uZTA4dfG200jCO8QPBrXPEnUUb1luYxiD+HZQuygSUedGL14wvxCfMRDfDyInXrZToya+eYd4iM8YSuJVR1qDE7Y0xPdzKhCvXgTpiZfkjg5qEjkO94BU/NJ3P37xbNoJ8QNSFK8pRyBetA8fi9eLzoDO73SWaYqnAwHx3QxWvwsJ8TXpiO/7au6IJ8dojfjR92Fwxo4a+YofzplKPJ2D9xHJiB9eHGUqfvB7L90zZiE+d/HdTwb0/9svA4N4LmoLLRRUsiz+tit/i5k9f+hFjyrarrWqWgzFDzq6zT7v/5EUz6bCu02genG4in+cjtX79eVTJ7qrTrv61s6ktWg37MNPfLh9Z10AndO0YgZrOmPKs/iq3i2L4u9fP0bvvHJaM5lS0697bz7We2wJ7RPA6wbd6BvSpjSDBt99mnQLnQ3XrsGynYyuTvO9xoNYcN7H3w9G+3gQCZsfx4M4gHiiQDxRIJ4oEE8UiCcKxBMF4okC8USBeKJAPFHWFA9iZj3xk69BBAmI0Abis41QA/HZRqiB+Gwj1EB8thFqID7bCDUQn22EGn/iQVJAPFEgnigQTxSIJwrEEwXiiQLxRIF4okA8UTyJvx/Y/DZqfS6suh3XPuX240dXCcuUKsKlIuWjQ45utWginBeHBn7ElzfRX17ty5+PbinXcjk1xS1TqgiXity/vPPbn99datFEOC8OHfyILx+XUa0xdjy+vTulnJ9+KYo1xe1S6giXilxLR+ejSy2aCNfFoYUf8be3z+rrakn17IWjS0q5gJritillhGtF+sm7RLgvDg38iC+fk+JQx3LzVnzNHVJKa01x25Tqu+NWkcdp71qLMsJ9cWgQxRpfcT6GX+PdKnI/7LljLaoIt1poEsU+vqLbPdoUvrnu40fi7SJuu7JN5lSLOsKpFrr4atXvXRqg5Ubt8f3DIaVcQE1x25R2b2FbkUaaSy2aCPfFoUE0x/FP7y4pHo/jbStyqW5fObrUoo1wXhwa4MwdUSCeKBBPFIgnCsQTBeKJAvFEgXiiQDxRIJ4oEE8UiCcKxBMF4okC8USBeKJAPFEgnigQTxSIJwpR8f1ly/ILmNe7tDkGIB7iKVFIvb39m7Hj/cCeP6oXfvvbz+XlzI9v7/XdyhCfIaX4XXWjW6n3XN25cNtV96ne3n4v71YuRoD4/Gi81m/lDWr3r1WPy778z3nbnS8Q/+NHdVvy03t94+Uf5c3p5/KJFBCfIWPxXz+afsUO/pe3z/vhiE19pozEl/v4Zm/PL2zf3ikP8RnSi3+cqlb903vdii8fSlDetPinn48QDzIE4okC8USBeKJAPFEgnigQTxSIJwrEEwXiiQLxRIF4okA8USCeKBBPFIgnCsQTBeKJ8n96sL5jTKdOkwAAAABJRU5ErkJggg==" alt="plot of chunk unnamed-chunk-9"/> </p>

<pre><code class="r">data.weekdayave&lt;-rowSums(data.weekday)/45
plot(data.weekdayave,type=&quot;l&quot;,xlab=&quot;Interval&quot;,ylab=&quot;Number of Steps&quot;,main=&quot;weekday&quot;)
</code></pre>

<p><img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAfgAAAH4CAMAAACR9g9NAAAAjVBMVEX9/v0AAAAAADkAAGUAOTkAOWUAOY8AZrU5AAA5ADk5AGU5OQA5OWU5OY85ZmU5ZrU5j485j9plAABlADllAGVlOQBlZjllZmVltbVltf2POQCPOTmPOWWPZgCPtY+P29qP2/21ZgC1tWW124+1/rW1/v3ajzna/rXa/tra/v39tWX924/9/rX9/tr9/v0Elsp8AAAAL3RSTlP/////////////////////////////////////////////////////////////AFqlOPcAAAAJcEhZcwAACxIAAAsSAdLdfvwAABGbSURBVHic7Z0Ne+q2GYannC2hZ8s66OlW0q6FraELEP//nzfLX7KxLMuWZMt6nru9DgTsVy+60Zex4U8ZgeRPaydA1oHiQaF4UCgeFIoHheJBoXhQKB4UigeF4kGheFAoHhSKB4XiQaF4UCgeFIoHheJBoXhQKB4UigeF4kGheFAoHhSKB4XiK+6HL++tP54/VsxlCSi+guKT5fMtV3sR+1LrRQhxlA9Xd6T4z7f8Xv6P+Elucc2feDoVe13zvRIDSHyu+JidxUuh8Swkuc76jhR/qbznPH/cD+VtsdfTae3kfYMk/rbb3w//yv0+nW67vEnLxtzcycX/d7eXGxX9QtnVy3fDbfdStPrEQBJ/P7zcvvv1u9P5y/u1aNZ5T97cuR+e/iq7/GveJVRjvGzzsv9//uPwsnbu3kESn52//OfL74efDi+ZTryQmpX4206Uj1yeft0lN8Rjib8+/fP54/z33TErenhJc6cc4/eqq2/+yN8B6Q3xWOLzVr3PpcoB+1xN4Zo7Unw1sy8fKPuCfNv8kQQXd1Dii+XatdR4Lr03d4p1vJzvS/P/OJRvib2c0hcrgeSAEj+TS7ngTwuKHyXFxRzFj3MRKTZ4ikeF4kGheFAoHhSKB4XiQaF4UCgeFIoHheJBoXhQKB4UigeF4kGheFAoHhSKB4XiQaF4UCgeFBfxgsRMQPEO+5LQUDwoFA8KxYNC8aBQPCgUDwrFg0LxoFA8KBQPCsWDgig+2sSWhOJBoXhQKB4UigeF4kGheFAoHhRI8dFmtiAUDwqgeBFtZktC8aBQPCgUDwrFg0LxoFA8KBQPCsWDQvGgUDwoFA8KxYNC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" alt="plot of chunk unnamed-chunk-9"/> </p>

</body>

</html>

