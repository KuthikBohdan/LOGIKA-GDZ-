<!DOCTYPE html>
<!-- saved from url=(0069)https://learn.logikaschool.com/lesson?lesson=14857&level=2&task=34109 -->
<html lang="uk-UA" data-react-helmet="lang"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8"><meta name="viewport" content="width=device-width,initial-scale=1,shrink-to-fit=no"><meta name="theme-color" content="#000000"><meta name="google" content="notranslate"><title></title><script type="text/javascript" src="./lesson_files/NRJS-74e61500c43a8461791"></script><script src="./lesson_files/nr-spa-1215.min.js.завантаження"></script><script>window.dataLayer = window.dataLayer || [];
    function gtag(){dataLayer.push(arguments);}
    gtag('js', new Date());</script><script>if(window.location.pathname.indexOf('/academy') !== -1){(function(w,d,s,l,i){w[l]=w[l]||[];w[l].push({'gtm.start': new Date().getTime(),event:'gtm.js'});var f=d.getElementsByTagName(s)[0],j=d.createElement(s),dl=l!='dataLayer'?'&l='+l:'';j.async=true;j.src='https://www.googletagmanager.com/gtm.js?id='+i+dl;f.parentNode.insertBefore(j,f);})(window,document,'script','dataLayer', 'GTM-K7488WV');}</script><script>window.dataLayer = window.dataLayer || [];
    window.addEventListener('submit', (event) => {
      dataLayer.push({'event': 'form_submit'});
    }, true);</script><script>if(window.location.pathname.indexOf('/programmer-life') !== -1) {
        (function(m, e, t, r, i, k, a) {
          m[i] = m[i] || function() {
            (m[i].a = m[i].a || []).push(arguments)
          };
          m[i].l = 1 * new Date();
          k = e.createElement(t), a = e.getElementsByTagName(t)[0], k.async = 1, k.src = r, a.parentNode.insertBefore(k, a)
        })
        (window, document, "script", "https://mc.yandex.ru/metrika/tag.js", "ym");

        ym(88424143, "init", {
          clickmap: true,
          trackLinks: true,
          accurateTrackBounce: true,
          webvisor: true
        });
      }</script><noscript><div><img src="https://mc.yandex.ru/watch/88424143" style="position:absolute; left:-9999px;" alt=""/></div></noscript><script>;window.NREUM||(NREUM={});NREUM.init={privacy:{cookies_enabled:true},ajax:{deny_list:["bam.nr-data.net"]}};
      window.NREUM||(NREUM={}),__nr_require=function(t,e,n){function r(n){if(!e[n]){var o=e[n]={exports:{}};t[n][0].call(o.exports,function(e){var o=t[n][1][e];return r(o||e)},o,o.exports)}return e[n].exports}if("function"==typeof __nr_require)return __nr_require;for(var o=0;o<n.length;o++)r(n[o]);return r}({1:[function(t,e,n){function r(t){try{s.console&&console.log(t)}catch(e){}}var o,i=t("ee"),a=t(32),s={};try{o=localStorage.getItem("__nr_flags").split(","),console&&"function"==typeof console.log&&(s.console=!0,o.indexOf("dev")!==-1&&(s.dev=!0),o.indexOf("nr_dev")!==-1&&(s.nrDev=!0))}catch(c){}s.nrDev&&i.on("internal-error",function(t){r(t.stack)}),s.dev&&i.on("fn-err",function(t,e,n){r(n.stack)}),s.dev&&(r("NR AGENT IN DEVELOPMENT MODE"),r("flags: "+a(s,function(t,e){return t}).join(", ")))},{}],2:[function(t,e,n){function r(t,e,n,r,s){try{l?l-=1:o(s||new UncaughtException(t,e,n),!0)}catch(f){try{i("ierr",[f,c.now(),!0])}catch(d){}}return"function"==typeof u&&u.apply(this,a(arguments))}function UncaughtException(t,e,n){this.message=t||"Uncaught error with no additional information",this.sourceURL=e,this.line=n}function o(t,e){var n=e?null:c.now();i("err",[t,n])}var i=t("handle"),a=t(33),s=t("ee"),c=t("loader"),f=t("gos"),u=window.onerror,d=!1,p="nr@seenError";if(!c.disabled){var l=0;c.features.err=!0,t(1),window.onerror=r;try{throw new Error}catch(h){"stack"in h&&(t(14),t(13),"addEventListener"in window&&t(7),c.xhrWrappable&&t(15),d=!0)}s.on("fn-start",function(t,e,n){d&&(l+=1)}),s.on("fn-err",function(t,e,n){d&&!n[p]&&(f(n,p,function(){return!0}),this.thrown=!0,o(n))}),s.on("fn-end",function(){d&&!this.thrown&&l>0&&(l-=1)}),s.on("internal-error",function(t){i("ierr",[t,c.now(),!0])})}},{}],3:[function(t,e,n){var r=t("loader");r.disabled||(r.features.ins=!0)},{}],4:[function(t,e,n){function r(){U++,L=g.hash,this[u]=y.now()}function o(){U--,g.hash!==L&&i(0,!0);var t=y.now();this[h]=~~this[h]+t-this[u],this[d]=t}function i(t,e){E.emit("newURL",[""+g,e])}function a(t,e){t.on(e,function(){this[e]=y.now()})}var s="-start",c="-end",f="-body",u="fn"+s,d="fn"+c,p="cb"+s,l="cb"+c,h="jsTime",m="fetch",v="addEventListener",w=window,g=w.location,y=t("loader");if(w[v]&&y.xhrWrappable&&!y.disabled){var x=t(11),b=t(12),E=t(9),R=t(7),O=t(14),T=t(8),S=t(15),P=t(10),M=t("ee"),C=M.get("tracer"),N=t(23);t(17),y.features.spa=!0;var L,U=0;M.on(u,r),b.on(p,r),P.on(p,r),M.on(d,o),b.on(l,o),P.on(l,o),M.buffer([u,d,"xhr-resolved"]),R.buffer([u]),O.buffer(["setTimeout"+c,"clearTimeout"+s,u]),S.buffer([u,"new-xhr","send-xhr"+s]),T.buffer([m+s,m+"-done",m+f+s,m+f+c]),E.buffer(["newURL"]),x.buffer([u]),b.buffer(["propagate",p,l,"executor-err","resolve"+s]),C.buffer([u,"no-"+u]),P.buffer(["new-jsonp","cb-start","jsonp-error","jsonp-end"]),a(T,m+s),a(T,m+"-done"),a(P,"new-jsonp"),a(P,"jsonp-end"),a(P,"cb-start"),E.on("pushState-end",i),E.on("replaceState-end",i),w[v]("hashchange",i,N(!0)),w[v]("load",i,N(!0)),w[v]("popstate",function(){i(0,U>1)},N(!0))}},{}],5:[function(t,e,n){function r(){var t=new PerformanceObserver(function(t,e){var n=t.getEntries();s(v,[n])});try{t.observe({entryTypes:["resource"]})}catch(e){}}function o(t){if(s(v,[window.performance.getEntriesByType(w)]),window.performance["c"+p])try{window.performance[h](m,o,!1)}catch(t){}else try{window.performance[h]("webkit"+m,o,!1)}catch(t){}}function i(t){}if(window.performance&&window.performance.timing&&window.performance.getEntriesByType){var a=t("ee"),s=t("handle"),c=t(14),f=t(13),u=t(6),d=t(23),p="learResourceTimings",l="addEventListener",h="removeEventListener",m="resourcetimingbufferfull",v="bstResource",w="resource",g="-start",y="-end",x="fn"+g,b="fn"+y,E="bstTimer",R="pushState",O=t("loader");if(!O.disabled){O.features.stn=!0,t(9),"addEventListener"in window&&t(7);var T=NREUM.o.EV;a.on(x,function(t,e){var n=t[0];n instanceof T&&(this.bstStart=O.now())}),a.on(b,function(t,e){var n=t[0];n instanceof T&&s("bst",[n,e,this.bstStart,O.now()])}),c.on(x,function(t,e,n){this.bstStart=O.now(),this.bstType=n}),c.on(b,function(t,e){s(E,[e,this.bstStart,O.now(),this.bstType])}),f.on(x,function(){this.bstStart=O.now()}),f.on(b,function(t,e){s(E,[e,this.bstStart,O.now(),"requestAnimationFrame"])}),a.on(R+g,function(t){this.time=O.now(),this.startPath=location.pathname+location.hash}),a.on(R+y,function(t){s("bstHist",[location.pathname+location.hash,this.startPath,this.time])}),u()?(s(v,[window.performance.getEntriesByType("resource")]),r()):l in window.performance&&(window.performance["c"+p]?window.performance[l](m,o,d(!1)):window.performance[l]("webkit"+m,o,d(!1))),document[l]("scroll",i,d(!1)),document[l]("keypress",i,d(!1)),document[l]("click",i,d(!1))}}},{}],6:[function(t,e,n){e.exports=function(){return"PerformanceObserver"in window&&"function"==typeof window.PerformanceObserver}},{}],7:[function(t,e,n){function r(t){for(var e=t;e&&!e.hasOwnProperty(u);)e=Object.getPrototypeOf(e);e&&o(e)}function o(t){s.inPlace(t,[u,d],"-",i)}function i(t,e){return t[1]}var a=t("ee").get("events"),s=t("wrap-function")(a,!0),c=t("gos"),f=XMLHttpRequest,u="addEventListener",d="removeEventListener";e.exports=a,"getPrototypeOf"in Object?(r(document),r(window),r(f.prototype)):f.prototype.hasOwnProperty(u)&&(o(window),o(f.prototype)),a.on(u+"-start",function(t,e){var n=t[1];if(null!==n&&("function"==typeof n||"object"==typeof n)){var r=c(n,"nr@wrapped",function(){function t(){if("function"==typeof n.handleEvent)return n.handleEvent.apply(n,arguments)}var e={object:t,"function":n}[typeof n];return e?s(e,"fn-",null,e.name||"anonymous"):n});this.wrapped=t[1]=r}}),a.on(d+"-start",function(t){t[1]=this.wrapped||t[1]})},{}],8:[function(t,e,n){function r(t,e,n){var r=t[e];"function"==typeof r&&(t[e]=function(){var t=i(arguments),e={};o.emit(n+"before-start",[t],e);var a;e[m]&&e[m].dt&&(a=e[m].dt);var s=r.apply(this,t);return o.emit(n+"start",[t,a],s),s.then(function(t){return o.emit(n+"end",[null,t],s),t},function(t){throw o.emit(n+"end",[t],s),t})})}var o=t("ee").get("fetch"),i=t(33),a=t(32);e.exports=o;var s=window,c="fetch-",f=c+"body-",u=["arrayBuffer","blob","json","text","formData"],d=s.Request,p=s.Response,l=s.fetch,h="prototype",m="nr@context";d&&p&&l&&(a(u,function(t,e){r(d[h],e,f),r(p[h],e,f)}),r(s,"fetch",c),o.on(c+"end",function(t,e){var n=this;if(e){var r=e.headers.get("content-length");null!==r&&(n.rxSize=r),o.emit(c+"done",[null,e],n)}else o.emit(c+"done",[t],n)}))},{}],9:[function(t,e,n){var r=t("ee").get("history"),o=t("wrap-function")(r);e.exports=r;var i=window.history&&window.history.constructor&&window.history.constructor.prototype,a=window.history;i&&i.pushState&&i.replaceState&&(a=i),o.inPlace(a,["pushState","replaceState"],"-")},{}],10:[function(t,e,n){function r(t){function e(){f.emit("jsonp-end",[],l),t.removeEventListener("load",e,c(!1)),t.removeEventListener("error",n,c(!1))}function n(){f.emit("jsonp-error",[],l),f.emit("jsonp-end",[],l),t.removeEventListener("load",e,c(!1)),t.removeEventListener("error",n,c(!1))}var r=t&&"string"==typeof t.nodeName&&"script"===t.nodeName.toLowerCase();if(r){var o="function"==typeof t.addEventListener;if(o){var a=i(t.src);if(a){var d=s(a),p="function"==typeof d.parent[d.key];if(p){var l={};u.inPlace(d.parent,[d.key],"cb-",l),t.addEventListener("load",e,c(!1)),t.addEventListener("error",n,c(!1)),f.emit("new-jsonp",[t.src],l)}}}}}function o(){return"addEventListener"in window}function i(t){var e=t.match(d);return e?e[1]:null}function a(t,e){var n=t.match(l),r=n[1],o=n[3];return o?a(o,e[r]):e[r]}function s(t){var e=t.match(p);return e&&e.length>=3?{key:e[2],parent:a(e[1],window)}:{key:t,parent:window}}var c=t(23),f=t("ee").get("jsonp"),u=t("wrap-function")(f);if(e.exports=f,o()){var d=/[?&](?:callback|cb)=([^&#]+)/,p=/(.*)\.([^.]+)/,l=/^(\w+)(\.|$)(.*)$/,h=["appendChild","insertBefore","replaceChild"];Node&&Node.prototype&&Node.prototype.appendChild?u.inPlace(Node.prototype,h,"dom-"):(u.inPlace(HTMLElement.prototype,h,"dom-"),u.inPlace(HTMLHeadElement.prototype,h,"dom-"),u.inPlace(HTMLBodyElement.prototype,h,"dom-")),f.on("dom-start",function(t){r(t[0])})}},{}],11:[function(t,e,n){var r=t("ee").get("mutation"),o=t("wrap-function")(r),i=NREUM.o.MO;e.exports=r,i&&(window.MutationObserver=function(t){return this instanceof i?new i(o(t,"fn-")):i.apply(this,arguments)},MutationObserver.prototype=i.prototype)},{}],12:[function(t,e,n){function r(t){var e=i.context(),n=s(t,"executor-",e,null,!1),r=new f(n);return i.context(r).getCtx=function(){return e},r}var o=t("wrap-function"),i=t("ee").get("promise"),a=t("ee").getOrSetContext,s=o(i),c=t(32),f=NREUM.o.PR;e.exports=i,f&&(window.Promise=r,["all","race"].forEach(function(t){var e=f[t];f[t]=function(n){function r(t){return function(){i.emit("propagate",[null,!o],a,!1,!1),o=o||!t}}var o=!1;c(n,function(e,n){Promise.resolve(n).then(r("all"===t),r(!1))});var a=e.apply(f,arguments),s=f.resolve(a);return s}}),["resolve","reject"].forEach(function(t){var e=f[t];f[t]=function(t){var n=e.apply(f,arguments);return t!==n&&i.emit("propagate",[t,!0],n,!1,!1),n}}),f.prototype["catch"]=function(t){return this.then(null,t)},f.prototype=Object.create(f.prototype,{constructor:{value:r}}),c(Object.getOwnPropertyNames(f),function(t,e){try{r[e]=f[e]}catch(n){}}),o.wrapInPlace(f.prototype,"then",function(t){return function(){var e=this,n=o.argsToArray.apply(this,arguments),r=a(e);r.promise=e,n[0]=s(n[0],"cb-",r,null,!1),n[1]=s(n[1],"cb-",r,null,!1);var c=t.apply(this,n);return r.nextPromise=c,i.emit("propagate",[e,!0],c,!1,!1),c}}),i.on("executor-start",function(t){t[0]=s(t[0],"resolve-",this,null,!1),t[1]=s(t[1],"resolve-",this,null,!1)}),i.on("executor-err",function(t,e,n){t[1](n)}),i.on("cb-end",function(t,e,n){i.emit("propagate",[n,!0],this.nextPromise,!1,!1)}),i.on("propagate",function(t,e,n){this.getCtx&&!e||(this.getCtx=function(){if(t instanceof Promise)var e=i.context(t);return e&&e.getCtx?e.getCtx():this})}),r.toString=function(){return""+f})},{}],13:[function(t,e,n){var r=t("ee").get("raf"),o=t("wrap-function")(r),i="equestAnimationFrame";e.exports=r,o.inPlace(window,["r"+i,"mozR"+i,"webkitR"+i,"msR"+i],"raf-"),r.on("raf-start",function(t){t[0]=o(t[0],"fn-")})},{}],14:[function(t,e,n){function r(t,e,n){t[0]=a(t[0],"fn-",null,n)}function o(t,e,n){this.method=n,this.timerDuration=isNaN(t[1])?0:+t[1],t[0]=a(t[0],"fn-",this,n)}var i=t("ee").get("timer"),a=t("wrap-function")(i),s="setTimeout",c="setInterval",f="clearTimeout",u="-start",d="-";e.exports=i,a.inPlace(window,[s,"setImmediate"],s+d),a.inPlace(window,[c],c+d),a.inPlace(window,[f,"clearImmediate"],f+d),i.on(c+u,r),i.on(s+u,o)},{}],15:[function(t,e,n){function r(t,e){d.inPlace(e,["onreadystatechange"],"fn-",s)}function o(){var t=this,e=u.context(t);t.readyState>3&&!e.resolved&&(e.resolved=!0,u.emit("xhr-resolved",[],t)),d.inPlace(t,y,"fn-",s)}function i(t){x.push(t),m&&(E?E.then(a):w?w(a):(R=-R,O.data=R))}function a(){for(var t=0;t<x.length;t++)r([],x[t]);x.length&&(x=[])}function s(t,e){return e}function c(t,e){for(var n in t)e[n]=t[n];return e}t(7);var f=t("ee"),u=f.get("xhr"),d=t("wrap-function")(u),p=t(23),l=NREUM.o,h=l.XHR,m=l.MO,v=l.PR,w=l.SI,g="readystatechange",y=["onload","onerror","onabort","onloadstart","onloadend","onprogress","ontimeout"],x=[];e.exports=u;var b=window.XMLHttpRequest=function(t){var e=new h(t);try{u.emit("new-xhr",[e],e),e.addEventListener(g,o,p(!1))}catch(n){try{u.emit("internal-error",[n])}catch(r){}}return e};if(c(h,b),b.prototype=h.prototype,d.inPlace(b.prototype,["open","send"],"-xhr-",s),u.on("send-xhr-start",function(t,e){r(t,e),i(e)}),u.on("open-xhr-start",r),m){var E=v&&v.resolve();if(!w&&!v){var R=1,O=document.createTextNode(R);new m(a).observe(O,{characterData:!0})}}else f.on("fn-end",function(t){t[0]&&t[0].type===g||a()})},{}],16:[function(t,e,n){function r(t){if(!s(t))return null;var e=window.NREUM;if(!e.loader_config)return null;var n=(e.loader_config.accountID||"").toString()||null,r=(e.loader_config.agentID||"").toString()||null,f=(e.loader_config.trustKey||"").toString()||null;if(!n||!r)return null;var h=l.generateSpanId(),m=l.generateTraceId(),v=Date.now(),w={spanId:h,traceId:m,timestamp:v};return(t.sameOrigin||c(t)&&p())&&(w.traceContextParentHeader=o(h,m),w.traceContextStateHeader=i(h,v,n,r,f)),(t.sameOrigin&&!u()||!t.sameOrigin&&c(t)&&d())&&(w.newrelicHeader=a(h,m,v,n,r,f)),w}function o(t,e){return"00-"+e+"-"+t+"-01"}function i(t,e,n,r,o){var i=0,a="",s=1,c="",f="";return o+"@nr="+i+"-"+s+"-"+n+"-"+r+"-"+t+"-"+a+"-"+c+"-"+f+"-"+e}function a(t,e,n,r,o,i){var a="btoa"in window&&"function"==typeof window.btoa;if(!a)return null;var s={v:[0,1],d:{ty:"Browser",ac:r,ap:o,id:t,tr:e,ti:n}};return i&&r!==i&&(s.d.tk=i),btoa(JSON.stringify(s))}function s(t){return f()&&c(t)}function c(t){var e=!1,n={};if("init"in NREUM&&"distributed_tracing"in NREUM.init&&(n=NREUM.init.distributed_tracing),t.sameOrigin)e=!0;else if(n.allowed_origins instanceof Array)for(var r=0;r<n.allowed_origins.length;r++){var o=h(n.allowed_origins[r]);if(t.hostname===o.hostname&&t.protocol===o.protocol&&t.port===o.port){e=!0;break}}return e}function f(){return"init"in NREUM&&"distributed_tracing"in NREUM.init&&!!NREUM.init.distributed_tracing.enabled}function u(){return"init"in NREUM&&"distributed_tracing"in NREUM.init&&!!NREUM.init.distributed_tracing.exclude_newrelic_header}function d(){return"init"in NREUM&&"distributed_tracing"in NREUM.init&&NREUM.init.distributed_tracing.cors_use_newrelic_header!==!1}function p(){return"init"in NREUM&&"distributed_tracing"in NREUM.init&&!!NREUM.init.distributed_tracing.cors_use_tracecontext_headers}var l=t(29),h=t(18);e.exports={generateTracePayload:r,shouldGenerateTrace:s}},{}],17:[function(t,e,n){function r(t){var e=this.params,n=this.metrics;if(!this.ended){this.ended=!0;for(var r=0;r<p;r++)t.removeEventListener(d[r],this.listener,!1);return e.protocol&&"data"===e.protocol?void g("Ajax/DataUrl/Excluded"):void(e.aborted||(n.duration=a.now()-this.startTime,this.loadCaptureCalled||4!==t.readyState?null==e.status&&(e.status=0):i(this,t),n.cbTime=this.cbTime,s("xhr",[e,n,this.startTime,this.endTime,"xhr"],this)))}}function o(t,e){var n=c(e),r=t.params;r.hostname=n.hostname,r.port=n.port,r.protocol=n.protocol,r.host=n.hostname+":"+n.port,r.pathname=n.pathname,t.parsedOrigin=n,t.sameOrigin=n.sameOrigin}function i(t,e){t.params.status=e.status;var n=v(e,t.lastSize);if(n&&(t.metrics.rxSize=n),t.sameOrigin){var r=e.getResponseHeader("X-NewRelic-App-Data");r&&(t.params.cat=r.split(", ").pop())}t.loadCaptureCalled=!0}var a=t("loader");if(a.xhrWrappable&&!a.disabled){var s=t("handle"),c=t(18),f=t(16).generateTracePayload,u=t("ee"),d=["load","error","abort","timeout"],p=d.length,l=t("id"),h=t(24),m=t(22),v=t(19),w=t(23),g=t(25).recordSupportability,y=NREUM.o.REQ,x=window.XMLHttpRequest;a.features.xhr=!0,t(15),t(8),u.on("new-xhr",function(t){var e=this;e.totalCbs=0,e.called=0,e.cbTime=0,e.end=r,e.ended=!1,e.xhrGuids={},e.lastSize=null,e.loadCaptureCalled=!1,e.params=this.params||{},e.metrics=this.metrics||{},t.addEventListener("load",function(n){i(e,t)},w(!1)),h&&(h>34||h<10)||t.addEventListener("progress",function(t){e.lastSize=t.loaded},w(!1))}),u.on("open-xhr-start",function(t){this.params={method:t[0]},o(this,t[1]),this.metrics={}}),u.on("open-xhr-end",function(t,e){"loader_config"in NREUM&&"xpid"in NREUM.loader_config&&this.sameOrigin&&e.setRequestHeader("X-NewRelic-ID",NREUM.loader_config.xpid);var n=f(this.parsedOrigin);if(n){var r=!1;n.newrelicHeader&&(e.setRequestHeader("newrelic",n.newrelicHeader),r=!0),n.traceContextParentHeader&&(e.setRequestHeader("traceparent",n.traceContextParentHeader),n.traceContextStateHeader&&e.setRequestHeader("tracestate",n.traceContextStateHeader),r=!0),r&&(this.dt=n)}}),u.on("send-xhr-start",function(t,e){var n=this.metrics,r=t[0],o=this;if(n&&r){var i=m(r);i&&(n.txSize=i)}this.startTime=a.now(),this.listener=function(t){try{"abort"!==t.type||o.loadCaptureCalled||(o.params.aborted=!0),("load"!==t.type||o.called===o.totalCbs&&(o.onloadCalled||"function"!=typeof e.onload))&&o.end(e)}catch(n){try{u.emit("internal-error",[n])}catch(r){}}};for(var s=0;s<p;s++)e.addEventListener(d[s],this.listener,w(!1))}),u.on("xhr-cb-time",function(t,e,n){this.cbTime+=t,e?this.onloadCalled=!0:this.called+=1,this.called!==this.totalCbs||!this.onloadCalled&&"function"==typeof n.onload||this.end(n)}),u.on("xhr-load-added",function(t,e){var n=""+l(t)+!!e;this.xhrGuids&&!this.xhrGuids[n]&&(this.xhrGuids[n]=!0,this.totalCbs+=1)}),u.on("xhr-load-removed",function(t,e){var n=""+l(t)+!!e;this.xhrGuids&&this.xhrGuids[n]&&(delete this.xhrGuids[n],this.totalCbs-=1)}),u.on("xhr-resolved",function(){this.endTime=a.now()}),u.on("addEventListener-end",function(t,e){e instanceof x&&"load"===t[0]&&u.emit("xhr-load-added",[t[1],t[2]],e)}),u.on("removeEventListener-end",function(t,e){e instanceof x&&"load"===t[0]&&u.emit("xhr-load-removed",[t[1],t[2]],e)}),u.on("fn-start",function(t,e,n){e instanceof x&&("onload"===n&&(this.onload=!0),("load"===(t[0]&&t[0].type)||this.onload)&&(this.xhrCbStart=a.now()))}),u.on("fn-end",function(t,e){this.xhrCbStart&&u.emit("xhr-cb-time",[a.now()-this.xhrCbStart,this.onload,e],e)}),u.on("fetch-before-start",function(t){function e(t,e){var n=!1;return e.newrelicHeader&&(t.set("newrelic",e.newrelicHeader),n=!0),e.traceContextParentHeader&&(t.set("traceparent",e.traceContextParentHeader),e.traceContextStateHeader&&t.set("tracestate",e.traceContextStateHeader),n=!0),n}var n,r=t[1]||{};"string"==typeof t[0]?n=t[0]:t[0]&&t[0].url?n=t[0].url:window.URL&&t[0]&&t[0]instanceof URL&&(n=t[0].href),n&&(this.parsedOrigin=c(n),this.sameOrigin=this.parsedOrigin.sameOrigin);var o=f(this.parsedOrigin);if(o&&(o.newrelicHeader||o.traceContextParentHeader))if("string"==typeof t[0]||window.URL&&t[0]&&t[0]instanceof URL){var i={};for(var a in r)i[a]=r[a];i.headers=new Headers(r.headers||{}),e(i.headers,o)&&(this.dt=o),t.length>1?t[1]=i:t.push(i)}else t[0]&&t[0].headers&&e(t[0].headers,o)&&(this.dt=o)}),u.on("fetch-start",function(t,e){this.params={},this.metrics={},this.startTime=a.now(),this.dt=e,t.length>=1&&(this.target=t[0]),t.length>=2&&(this.opts=t[1]);var n,r=this.opts||{},i=this.target;if("string"==typeof i?n=i:"object"==typeof i&&i instanceof y?n=i.url:window.URL&&"object"==typeof i&&i instanceof URL&&(n=i.href),o(this,n),"data"!==this.params.protocol){var s=(""+(i&&i instanceof y&&i.method||r.method||"GET")).toUpperCase();this.params.method=s,this.txSize=m(r.body)||0}}),u.on("fetch-done",function(t,e){if(this.endTime=a.now(),this.params||(this.params={}),"data"===this.params.protocol)return void g("Ajax/DataUrl/Excluded");this.params.status=e?e.status:0;var n;"string"==typeof this.rxSize&&this.rxSize.length>0&&(n=+this.rxSize);var r={txSize:this.txSize,rxSize:n,duration:a.now()-this.startTime};s("xhr",[this.params,r,this.startTime,this.endTime,"fetch"],this)})}},{}],18:[function(t,e,n){var r={};e.exports=function(t){if(t in r)return r[t];if(0===(t||"").indexOf("data:"))return{protocol:"data"};var e=document.createElement("a"),n=window.location,o={};e.href=t,o.port=e.port;var i=e.href.split("://");!o.port&&i[1]&&(o.port=i[1].split("/")[0].split("@").pop().split(":")[1]),o.port&&"0"!==o.port||(o.port="https"===i[0]?"443":"80"),o.hostname=e.hostname||n.hostname,o.pathname=e.pathname,o.protocol=i[0],"/"!==o.pathname.charAt(0)&&(o.pathname="/"+o.pathname);var a=!e.protocol||":"===e.protocol||e.protocol===n.protocol,s=e.hostname===document.domain&&e.port===n.port;return o.sameOrigin=a&&(!e.hostname||s),"/"===o.pathname&&(r[t]=o),o}},{}],19:[function(t,e,n){function r(t,e){var n=t.responseType;return"json"===n&&null!==e?e:"arraybuffer"===n||"blob"===n||"json"===n?o(t.response):"text"===n||""===n||void 0===n?o(t.responseText):void 0}var o=t(22);e.exports=r},{}],20:[function(t,e,n){function r(){}function o(t,e,n,r){return function(){return u.recordSupportability("API/"+e+"/called"),i(t+e,[f.now()].concat(s(arguments)),n?null:this,r),n?void 0:this}}var i=t("handle"),a=t(32),s=t(33),c=t("ee").get("tracer"),f=t("loader"),u=t(25),d=NREUM;"undefined"==typeof window.newrelic&&(newrelic=d);var p=["setPageViewName","setCustomAttribute","setErrorHandler","finished","addToTrace","inlineHit","addRelease"],l="api-",h=l+"ixn-";a(p,function(t,e){d[e]=o(l,e,!0,"api")}),d.addPageAction=o(l,"addPageAction",!0),d.setCurrentRouteName=o(l,"routeName",!0),e.exports=newrelic,d.interaction=function(){return(new r).get()};var m=r.prototype={createTracer:function(t,e){var n={},r=this,o="function"==typeof e;return i(h+"tracer",[f.now(),t,n],r),function(){if(c.emit((o?"":"no-")+"fn-start",[f.now(),r,o],n),o)try{return e.apply(this,arguments)}catch(t){throw c.emit("fn-err",[arguments,this,t],n),t}finally{c.emit("fn-end",[f.now()],n)}}}};a("actionText,setName,setAttribute,save,ignore,onEnd,getContext,end,get".split(","),function(t,e){m[e]=o(h,e)}),newrelic.noticeError=function(t,e){"string"==typeof t&&(t=new Error(t)),u.recordSupportability("API/noticeError/called"),i("err",[t,f.now(),!1,e])}},{}],21:[function(t,e,n){function r(t){if(NREUM.init){for(var e=NREUM.init,n=t.split("."),r=0;r<n.length-1;r++)if(e=e[n[r]],"object"!=typeof e)return;return e=e[n[n.length-1]]}}e.exports={getConfiguration:r}},{}],22:[function(t,e,n){e.exports=function(t){if("string"==typeof t&&t.length)return t.length;if("object"==typeof t){if("undefined"!=typeof ArrayBuffer&&t instanceof ArrayBuffer&&t.byteLength)return t.byteLength;if("undefined"!=typeof Blob&&t instanceof Blob&&t.size)return t.size;if(!("undefined"!=typeof FormData&&t instanceof FormData))try{return JSON.stringify(t).length}catch(e){return}}}},{}],23:[function(t,e,n){var r=!1;try{var o=Object.defineProperty({},"passive",{get:function(){r=!0}});window.addEventListener("testPassive",null,o),window.removeEventListener("testPassive",null,o)}catch(i){}e.exports=function(t){return r?{passive:!0,capture:!!t}:!!t}},{}],24:[function(t,e,n){var r=0,o=navigator.userAgent.match(/Firefox[\/\s](\d+\.\d+)/);o&&(r=+o[1]),e.exports=r},{}],25:[function(t,e,n){function r(t,e){var n=[a,t,{name:t},e];return i("storeMetric",n,null,"api"),n}function o(t,e){var n=[s,t,{name:t},e];return i("storeEventMetrics",n,null,"api"),n}var i=t("handle"),a="sm",s="cm";e.exports={constants:{SUPPORTABILITY_METRIC:a,CUSTOM_METRIC:s},recordSupportability:r,recordCustom:o}},{}],26:[function(t,e,n){function r(){return s.exists&&performance.now?Math.round(performance.now()):(i=Math.max((new Date).getTime(),i))-a}function o(){return i}var i=(new Date).getTime(),a=i,s=t(34);e.exports=r,e.exports.offset=a,e.exports.getLastTimestamp=o},{}],27:[function(t,e,n){function r(t){return!(!t||!t.protocol||"file:"===t.protocol)}e.exports=r},{}],28:[function(t,e,n){function r(t,e){var n=t.getEntries();n.forEach(function(t){"first-paint"===t.name?l("timing",["fp",Math.floor(t.startTime)]):"first-contentful-paint"===t.name&&l("timing",["fcp",Math.floor(t.startTime)])})}function o(t,e){var n=t.getEntries();if(n.length>0){var r=n[n.length-1];if(f&&f<r.startTime)return;var o=[r],i=a({});i&&o.push(i),l("lcp",o)}}function i(t){t.getEntries().forEach(function(t){t.hadRecentInput||l("cls",[t])})}function a(t){var e=navigator.connection||navigator.mozConnection||navigator.webkitConnection;if(e)return e.type&&(t["net-type"]=e.type),e.effectiveType&&(t["net-etype"]=e.effectiveType),e.rtt&&(t["net-rtt"]=e.rtt),e.downlink&&(t["net-dlink"]=e.downlink),t}function s(t){if(t instanceof w&&!y){var e=Math.round(t.timeStamp),n={type:t.type};a(n),e<=h.now()?n.fid=h.now()-e:e>h.offset&&e<=Date.now()?(e-=h.offset,n.fid=h.now()-e):e=h.now(),y=!0,l("timing",["fi",e,n])}}function c(t){"hidden"===t&&(f=h.now(),l("pageHide",[f]))}if(!("init"in NREUM&&"page_view_timing"in NREUM.init&&"enabled"in NREUM.init.page_view_timing&&NREUM.init.page_view_timing.enabled===!1)){var f,u,d,p,l=t("handle"),h=t("loader"),m=t(31),v=t(23),w=NREUM.o.EV;if("PerformanceObserver"in window&&"function"==typeof window.PerformanceObserver){u=new PerformanceObserver(r);try{u.observe({entryTypes:["paint"]})}catch(g){}d=new PerformanceObserver(o);try{d.observe({entryTypes:["largest-contentful-paint"]})}catch(g){}p=new PerformanceObserver(i);try{p.observe({type:"layout-shift",buffered:!0})}catch(g){}}if("addEventListener"in document){var y=!1,x=["click","keydown","mousedown","pointerdown","touchstart"];x.forEach(function(t){document.addEventListener(t,s,v(!1))})}m(c)}},{}],29:[function(t,e,n){function r(){function t(){return e?15&e[n++]:16*Math.random()|0}var e=null,n=0,r=window.crypto||window.msCrypto;r&&r.getRandomValues&&(e=r.getRandomValues(new Uint8Array(31)));for(var o,i="xxxxxxxx-xxxx-4xxx-yxxx-xxxxxxxxxxxx",a="",s=0;s<i.length;s++)o=i[s],"x"===o?a+=t().toString(16):"y"===o?(o=3&t()|8,a+=o.toString(16)):a+=o;return a}function o(){return a(16)}function i(){return a(32)}function a(t){function e(){return n?15&n[r++]:16*Math.random()|0}var n=null,r=0,o=window.crypto||window.msCrypto;o&&o.getRandomValues&&Uint8Array&&(n=o.getRandomValues(new Uint8Array(31)));for(var i=[],a=0;a<t;a++)i.push(e().toString(16));return i.join("")}e.exports={generateUuid:r,generateSpanId:o,generateTraceId:i}},{}],30:[function(t,e,n){function r(t,e){if(!o)return!1;if(t!==o)return!1;if(!e)return!0;if(!i)return!1;for(var n=i.split("."),r=e.split("."),a=0;a<r.length;a++)if(r[a]!==n[a])return!1;return!0}var o=null,i=null,a=/Version\/(\S+)\s+Safari/;if(navigator.userAgent){var s=navigator.userAgent,c=s.match(a);c&&s.indexOf("Chrome")===-1&&s.indexOf("Chromium")===-1&&(o="Safari",i=c[1])}e.exports={agent:o,version:i,match:r}},{}],31:[function(t,e,n){function r(t){function e(){t(s&&document[s]?document[s]:document[i]?"hidden":"visible")}"addEventListener"in document&&a&&document.addEventListener(a,e,o(!1))}var o=t(23);e.exports=r;var i,a,s;"undefined"!=typeof document.hidden?(i="hidden",a="visibilitychange",s="visibilityState"):"undefined"!=typeof document.msHidden?(i="msHidden",a="msvisibilitychange"):"undefined"!=typeof document.webkitHidden&&(i="webkitHidden",a="webkitvisibilitychange",s="webkitVisibilityState")},{}],32:[function(t,e,n){function r(t,e){var n=[],r="",i=0;for(r in t)o.call(t,r)&&(n[i]=e(r,t[r]),i+=1);return n}var o=Object.prototype.hasOwnProperty;e.exports=r},{}],33:[function(t,e,n){function r(t,e,n){e||(e=0),"undefined"==typeof n&&(n=t?t.length:0);for(var r=-1,o=n-e||0,i=Array(o<0?0:o);++r<o;)i[r]=t[e+r];return i}e.exports=r},{}],34:[function(t,e,n){e.exports={exists:"undefined"!=typeof window.performance&&window.performance.timing&&"undefined"!=typeof window.performance.timing.navigationStart}},{}],ee:[function(t,e,n){function r(){}function o(t){function e(t){return t&&t instanceof r?t:t?f(t,c,a):a()}function n(n,r,o,i,a){if(a!==!1&&(a=!0),!l.aborted||i){t&&a&&t(n,r,o);for(var s=e(o),c=m(n),f=c.length,u=0;u<f;u++)c[u].apply(s,r);var p=d[y[n]];return p&&p.push([x,n,r,s]),s}}function i(t,e){g[t]=m(t).concat(e)}function h(t,e){var n=g[t];if(n)for(var r=0;r<n.length;r++)n[r]===e&&n.splice(r,1)}function m(t){return g[t]||[]}function v(t){return p[t]=p[t]||o(n)}function w(t,e){l.aborted||u(t,function(t,n){e=e||"feature",y[n]=e,e in d||(d[e]=[])})}var g={},y={},x={on:i,addEventListener:i,removeEventListener:h,emit:n,get:v,listeners:m,context:e,buffer:w,abort:s,aborted:!1};return x}function i(t){return f(t,c,a)}function a(){return new r}function s(){(d.api||d.feature)&&(l.aborted=!0,d=l.backlog={})}var c="nr@context",f=t("gos"),u=t(32),d={},p={},l=e.exports=o();e.exports.getOrSetContext=i,l.backlog=d},{}],gos:[function(t,e,n){function r(t,e,n){if(o.call(t,e))return t[e];var r=n();if(Object.defineProperty&&Object.keys)try{return Object.defineProperty(t,e,{value:r,writable:!0,enumerable:!1}),r}catch(i){}return t[e]=r,r}var o=Object.prototype.hasOwnProperty;e.exports=r},{}],handle:[function(t,e,n){function r(t,e,n,r){o.buffer([t],r),o.emit(t,e,n)}var o=t("ee").get("handle");e.exports=r,r.ee=o},{}],id:[function(t,e,n){function r(t){var e=typeof t;return!t||"object"!==e&&"function"!==e?-1:t===window?0:a(t,i,function(){return o++})}var o=1,i="nr@id",a=t("gos");e.exports=r},{}],loader:[function(t,e,n){function r(){if(!S++){var t=T.info=NREUM.info,e=v.getElementsByTagName("script")[0];if(setTimeout(f.abort,3e4),!(t&&t.licenseKey&&t.applicationID&&e))return f.abort();c(R,function(e,n){t[e]||(t[e]=n)});var n=a();s("mark",["onload",n+T.offset],null,"api"),s("timing",["load",n]);var r=v.createElement("script");0===t.agent.indexOf("http://")||0===t.agent.indexOf("https://")?r.src=t.agent:r.src=h+"://"+t.agent,e.parentNode.insertBefore(r,e)}}function o(){"complete"===v.readyState&&i()}function i(){s("mark",["domContent",a()+T.offset],null,"api")}var a=t(26),s=t("handle"),c=t(32),f=t("ee"),u=t(30),d=t(27),p=t(21),l=t(23),h=p.getConfiguration("ssl")===!1?"http":"https",m=window,v=m.document,w="addEventListener",g="attachEvent",y=m.XMLHttpRequest,x=y&&y.prototype,b=!d(m.location);NREUM.o={ST:setTimeout,SI:m.setImmediate,CT:clearTimeout,XHR:y,REQ:m.Request,EV:m.Event,PR:m.Promise,MO:m.MutationObserver};var E=""+location,R={beacon:"bam.nr-data.net",errorBeacon:"bam.nr-data.net",agent:"js-agent.newrelic.com/nr-spa-1215.min.js"},O=y&&x&&x[w]&&!/CriOS/.test(navigator.userAgent),T=e.exports={offset:a.getLastTimestamp(),now:a,origin:E,features:{},xhrWrappable:O,userAgent:u,disabled:b};if(!b){t(20),t(28),v[w]?(v[w]("DOMContentLoaded",i,l(!1)),m[w]("load",r,l(!1))):(v[g]("onreadystatechange",o),m[g]("onload",r)),s("mark",["firstbyte",a.getLastTimestamp()],null,"api");var S=0}},{}],"wrap-function":[function(t,e,n){function r(t,e){function n(e,n,r,c,f){function nrWrapper(){var i,a,u,p;try{a=this,i=d(arguments),u="function"==typeof r?r(i,a):r||{}}catch(l){o([l,"",[i,a,c],u],t)}s(n+"start",[i,a,c],u,f);try{return p=e.apply(a,i)}catch(h){throw s(n+"err",[i,a,h],u,f),h}finally{s(n+"end",[i,a,p],u,f)}}return a(e)?e:(n||(n=""),nrWrapper[p]=e,i(e,nrWrapper,t),nrWrapper)}function r(t,e,r,o,i){r||(r="");var s,c,f,u="-"===r.charAt(0);for(f=0;f<e.length;f++)c=e[f],s=t[c],a(s)||(t[c]=n(s,u?c+r:r,o,c,i))}function s(n,r,i,a){if(!h||e){var s=h;h=!0;try{t.emit(n,r,i,e,a)}catch(c){o([c,n,r,i],t)}h=s}}return t||(t=u),n.inPlace=r,n.flag=p,n}function o(t,e){e||(e=u);try{e.emit("internal-error",t)}catch(n){}}function i(t,e,n){if(Object.defineProperty&&Object.keys)try{var r=Object.keys(t);return r.forEach(function(n){Object.defineProperty(e,n,{get:function(){return t[n]},set:function(e){return t[n]=e,e}})}),e}catch(i){o([i],n)}for(var a in t)l.call(t,a)&&(e[a]=t[a]);return e}function a(t){return!(t&&t instanceof Function&&t.apply&&!t[p])}function s(t,e){var n=e(t);return n[p]=t,i(t,n,u),n}function c(t,e,n){var r=t[e];t[e]=s(r,n)}function f(){for(var t=arguments.length,e=new Array(t),n=0;n<t;++n)e[n]=arguments[n];return e}var u=t("ee"),d=t(33),p="nr@original",l=Object.prototype.hasOwnProperty,h=!1;e.exports=r,e.exports.wrapFunction=s,e.exports.wrapInPlace=c,e.exports.argsToArray=f},{}]},{},["loader",2,17,5,3,4]);
      ;NREUM.loader_config={accountID:"3464476",trustKey:"3464476",agentID:"1120059892",licenseKey:"NRJS-74e61500c43a8461791",applicationID:"1120059892"}
      ;NREUM.info={beacon:"bam.nr-data.net",errorBeacon:"bam.nr-data.net",licenseKey:"NRJS-74e61500c43a8461791",applicationID:"1120059892",sa:1}</script><style></style><meta name="viewport" content="width=device-width,initial-scale=1"><script defer="defer" src="./lesson_files/1659.376c4203.js.завантаження"></script><script defer="defer" src="./lesson_files/main.5ed67a4e.js.завантаження"></script><script src="./lesson_files/logger.min.js.завантаження" async=""></script><style>.rc-color-picker-panel-inner {
  position: relative;
  border-radius: 4px;
  box-shadow: 0 1px 5px #ccc;
  border: 1px solid #ccc;
  padding-bottom: 8px;
}
.rc-color-picker-panel-wrap {
  margin: 5px 0 0;
  height: 30px;
  width: 100%;
  position: relative;
}
.rc-color-picker-panel-wrap-preview {
  position: absolute;
  right: 8px;
}
.rc-color-picker-panel-wrap-ribbon {
  position: absolute;
  left: 8px;
  top: 0;
  right: 43px;
  height: 30px;
}
.rc-color-picker-panel-wrap-alpha {
  position: absolute;
  left: 8px;
  right: 43px;
  bottom: 0;
  height: 12.5px;
}
.rc-color-picker-panel-wrap-has-alpha .rc-color-picker-panel-wrap-ribbon {
  height: 12.5px;
}
.rc-color-picker-trigger {
  border: 1px solid #999;
  display: inline-block;
  padding: 2px;
  border-radius: 2px;
  -webkit-user-select: none;
     -moz-user-select: none;
      -ms-user-select: none;
          user-select: none;
  width: 20px;
  height: 20px;
  cursor: pointer;
  box-shadow: 0 0 0 2px #fff inset;
}
.rc-color-picker-trigger-open {
  box-shadow: 0px 0px 3px #999;
}
.rc-color-picker-panel {
  width: 218px;
  background-color: #fff;
  box-sizing: border-box;
  outline: none;
  z-index: 9;
  border-radius: 4px;
  -moz-user-select: none;
  -khtml-user-select: none;
  -webkit-user-select: none;
  -ms-user-select: none;
  user-select: none;
}
.rc-color-picker-panel * {
  box-sizing: border-box;
}
.rc-color-picker-panel-open {
  display: block;
}
.rc-color-picker-panel-close {
  display: none;
}
.rc-color-picker-panel-preview {
  height: 30px;
  width: 30px;
  overflow: hidden;
  border-radius: 2px;
  background-image: url('data:image/png;base64,R0lGODdhCgAKAPAAAOXl5f///ywAAAAACgAKAEACEIQdqXt9GxyETrI279OIgwIAOw==');
}
.rc-color-picker-panel-preview span {
  box-shadow: 0 0 2px #808080 inset;
}
.rc-color-picker-panel-preview span,
.rc-color-picker-panel-preview input[type=color] {
  position: absolute;
  display: block;
  height: 100%;
  width: 30px;
  border-radius: 2px;
}
.rc-color-picker-panel-preview input[type=color] {
  opacity: 0;
}
.rc-color-picker-panel-board {
  position: relative;
  font-size: 0;
  -webkit-user-select: none;
     -moz-user-select: none;
      -ms-user-select: none;
          user-select: none;
  margin: 8px 8px 0px;
}
.rc-color-picker-panel-board span {
  position: absolute;
  border-radius: 10px;
  border: 1px solid #fff;
  width: 9px;
  height: 9px;
  margin: -4px 0 0 -4px;
  left: -999px;
  top: -999px;
  box-shadow: 0 0 1px rgba(120, 120, 120, 0.7);
  z-index: 2;
}
.rc-color-picker-panel-board-hsv {
  width: 200px;
  height: 150px;
  position: relative;
  z-index: 1;
  border-radius: 2px;
}
.rc-color-picker-panel-board-value {
  border-radius: 2px;
  position: absolute;
  width: 100%;
  height: 100%;
  left: 0;
  top: 0;
  z-index: 2;
  background-image: url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiA/PjxzdmcgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB3aWR0aD0iMTAwJSIgaGVpZ2h0PSIxMDAlIiB2aWV3Qm94PSIwIDAgMSAxIiBwcmVzZXJ2ZUFzcGVjdFJhdGlvPSJub25lIj48bGluZWFyR3JhZGllbnQgaWQ9Imxlc3NoYXQtZ2VuZXJhdGVkIiBncmFkaWVudFVuaXRzPSJ1c2VyU3BhY2VPblVzZSIgeDE9IjAlIiB5MT0iMCUiIHgyPSIwJSIgeTI9IjEwMCUiPjxzdG9wIG9mZnNldD0iMCUiIHN0b3AtY29sb3I9InJnYigwLDAsMCkiIHN0b3Atb3BhY2l0eT0iMCIvPjxzdG9wIG9mZnNldD0iMTAwJSIgc3RvcC1jb2xvcj0iIzAwMDAwMCIgc3RvcC1vcGFjaXR5PSIxIi8+PC9saW5lYXJHcmFkaWVudD48cmVjdCB4PSIwIiB5PSIwIiB3aWR0aD0iMSIgaGVpZ2h0PSIxIiBmaWxsPSJ1cmwoI2xlc3NoYXQtZ2VuZXJhdGVkKSIgLz48L3N2Zz4=);
  background-image: -webkit-linear-gradient(top, transparent 0%, #000000 100%);
  background-image: -moz-linear-gradient(top, transparent 0%, #000000 100%);
  background-image: -o-linear-gradient(top, transparent 0%, #000000 100%);
  background-image: linear-gradient(to bottom, transparent 0%, #000000 100%);
}
.rc-color-picker-panel-board-saturation {
  border-radius: 2px;
  position: absolute;
  width: 100%;
  height: 100%;
  left: 0;
  top: 0;
  z-index: 1;
  background-image: url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiA/PjxzdmcgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB3aWR0aD0iMTAwJSIgaGVpZ2h0PSIxMDAlIiB2aWV3Qm94PSIwIDAgMSAxIiBwcmVzZXJ2ZUFzcGVjdFJhdGlvPSJub25lIj48bGluZWFyR3JhZGllbnQgaWQ9Imxlc3NoYXQtZ2VuZXJhdGVkIiBncmFkaWVudFVuaXRzPSJ1c2VyU3BhY2VPblVzZSIgeDE9IjAlIiB5MT0iMCUiIHgyPSIxMDAlIiB5Mj0iMCUiPjxzdG9wIG9mZnNldD0iMCUiIHN0b3AtY29sb3I9IiNmZmZmZmYiIHN0b3Atb3BhY2l0eT0iMSIvPjxzdG9wIG9mZnNldD0iMTAwJSIgc3RvcC1jb2xvcj0icmdiKDAsMCwwKSIgc3RvcC1vcGFjaXR5PSIwIi8+PC9saW5lYXJHcmFkaWVudD48cmVjdCB4PSIwIiB5PSIwIiB3aWR0aD0iMSIgaGVpZ2h0PSIxIiBmaWxsPSJ1cmwoI2xlc3NoYXQtZ2VuZXJhdGVkKSIgLz48L3N2Zz4=);
  background-image: -webkit-linear-gradient(left, #ffffff 0%, transparent 100%);
  background-image: -moz-linear-gradient(left, #ffffff 0%, transparent 100%);
  background-image: -o-linear-gradient(left, #ffffff 0%, transparent 100%);
  background-image: linear-gradient(to right, #ffffff 0%, transparent 100%);
}
.rc-color-picker-panel-board-handler {
  box-shadow: 0 0 2px #808080 inset;
  border-radius: 2px;
  cursor: crosshair;
  -webkit-user-select: none;
     -moz-user-select: none;
      -ms-user-select: none;
          user-select: none;
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  z-index: 3;
}
.rc-color-picker-panel-ribbon {
  position: relative;
  height: 100%;
  border-radius: 2px;
  box-shadow: 0 0 2px #808080 inset;
  background-image: url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiA/PjxzdmcgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB3aWR0aD0iMTAwJSIgaGVpZ2h0PSIxMDAlIiB2aWV3Qm94PSIwIDAgMSAxIiBwcmVzZXJ2ZUFzcGVjdFJhdGlvPSJub25lIj48bGluZWFyR3JhZGllbnQgaWQ9Imxlc3NoYXQtZ2VuZXJhdGVkIiBncmFkaWVudFVuaXRzPSJ1c2VyU3BhY2VPblVzZSIgeDE9IjAlIiB5MT0iMCUiIHgyPSIxMDAlIiB5Mj0iMCUiPjxzdG9wIG9mZnNldD0iMCUiIHN0b3AtY29sb3I9IiNmZjAwMDAiIHN0b3Atb3BhY2l0eT0iMSIvPjxzdG9wIG9mZnNldD0iMTAlIiBzdG9wLWNvbG9yPSIjZmY5OTAwIiBzdG9wLW9wYWNpdHk9IjEiLz48c3RvcCBvZmZzZXQ9IjIwJSIgc3RvcC1jb2xvcj0iI2NkZmYwMCIgc3RvcC1vcGFjaXR5PSIxIi8+PHN0b3Agb2Zmc2V0PSIzMCUiIHN0b3AtY29sb3I9IiMzNWZmMDAiIHN0b3Atb3BhY2l0eT0iMSIvPjxzdG9wIG9mZnNldD0iNDAlIiBzdG9wLWNvbG9yPSIjMDBmZjY2IiBzdG9wLW9wYWNpdHk9IjEiLz48c3RvcCBvZmZzZXQ9IjUwJSIgc3RvcC1jb2xvcj0iIzAwZmZmZCIgc3RvcC1vcGFjaXR5PSIxIi8+PHN0b3Agb2Zmc2V0PSI2MCUiIHN0b3AtY29sb3I9IiMwMDY2ZmYiIHN0b3Atb3BhY2l0eT0iMSIvPjxzdG9wIG9mZnNldD0iNzAlIiBzdG9wLWNvbG9yPSIjMzIwMGZmIiBzdG9wLW9wYWNpdHk9IjEiLz48c3RvcCBvZmZzZXQ9IjgwJSIgc3RvcC1jb2xvcj0iI2NkMDBmZiIgc3RvcC1vcGFjaXR5PSIxIi8+PHN0b3Agb2Zmc2V0PSI5MCUiIHN0b3AtY29sb3I9IiNmZjAwOTkiIHN0b3Atb3BhY2l0eT0iMSIvPjxzdG9wIG9mZnNldD0iMTAwJSIgc3RvcC1jb2xvcj0iI2ZmMDAwMCIgc3RvcC1vcGFjaXR5PSIxIi8+PC9saW5lYXJHcmFkaWVudD48cmVjdCB4PSIwIiB5PSIwIiB3aWR0aD0iMSIgaGVpZ2h0PSIxIiBmaWxsPSJ1cmwoI2xlc3NoYXQtZ2VuZXJhdGVkKSIgLz48L3N2Zz4=);
  background-image: -webkit-linear-gradient(left, #ff0000 0%, #ff9900 10%, #cdff00 20%, #35ff00 30%, #00ff66 40%, #00fffd 50%, #0066ff 60%, #3200ff 70%, #cd00ff 80%, #ff0099 90%, #ff0000 100%);
  background-image: -moz-linear-gradient(left, #ff0000 0%, #ff9900 10%, #cdff00 20%, #35ff00 30%, #00ff66 40%, #00fffd 50%, #0066ff 60%, #3200ff 70%, #cd00ff 80%, #ff0099 90%, #ff0000 100%);
  background-image: -o-linear-gradient(left, #ff0000 0%, #ff9900 10%, #cdff00 20%, #35ff00 30%, #00ff66 40%, #00fffd 50%, #0066ff 60%, #3200ff 70%, #cd00ff 80%, #ff0099 90%, #ff0000 100%);
  background-image: linear-gradient(to right, #ff0000 0%, #ff9900 10%, #cdff00 20%, #35ff00 30%, #00ff66 40%, #00fffd 50%, #0066ff 60%, #3200ff 70%, #cd00ff 80%, #ff0099 90%, #ff0000 100%);
}
.rc-color-picker-panel-ribbon span {
  position: absolute;
  top: 0;
  height: 100%;
  width: 4px;
  border: 1px solid #000000;
  padding: 1px 0;
  margin-left: -2px;
  background-color: #fff;
  border-radius: 3px;
}
.rc-color-picker-panel-ribbon-handler {
  position: absolute;
  width: 104%;
  height: 100%;
  left: -2%;
  cursor: pointer;
}
.rc-color-picker-panel-alpha {
  position: relative;
  height: 100%;
  width: 100%;
  border-radius: 2px;
  background-image: url('data:image/png;base64,R0lGODdhCgAKAPAAAOXl5f///ywAAAAACgAKAEACEIQdqXt9GxyETrI279OIgwIAOw==');
  background-repeat: repeat;
  -webkit-user-select: none;
     -moz-user-select: none;
      -ms-user-select: none;
          user-select: none;
}
.rc-color-picker-panel-alpha-bg {
  position: absolute;
  width: 100%;
  height: 100%;
  border-radius: 2px;
  box-shadow: 0 0 2px #808080 inset;
}
.rc-color-picker-panel-alpha span {
  position: absolute;
  top: 0;
  height: 100%;
  width: 4px;
  border: 1px solid #000000;
  padding: 1px 0;
  margin-left: -2px;
  background-color: #fff;
  border-radius: 3px;
}
.rc-color-picker-panel-alpha-handler {
  position: absolute;
  width: 104%;
  height: 100%;
  left: -2%;
  cursor: pointer;
}
.rc-color-picker-panel-params {
  font-size: 12px;
}
.rc-color-picker-panel-params-input {
  overflow: hidden;
  padding: 2px 8px;
}
.rc-color-picker-panel-params input {
  -webkit-user-select: text;
     -moz-user-select: text;
      -ms-user-select: text;
          user-select: text;
  text-align: center;
  padding: 1px;
  margin: 0;
  float: left;
  border-radius: 2px;
  border: 1px solid #CACACA;
  font-family: 'Helvetica Neue', Helvetica, sans-serif;
}
.rc-color-picker-panel-params-hex {
  width: 52px;
}
.rc-color-picker-panel-params input[type=number] {
  margin-left: 5px;
  width: 44px;
}
.rc-color-picker-panel-params input[type=number]::-webkit-inner-spin-button {
  -webkit-appearance: none;
}
.rc-color-picker-panel-params-lable {
  padding: 2px 8px;
  height: 22px;
  line-height: 18px;
  -webkit-user-select: none;
     -moz-user-select: none;
      -ms-user-select: none;
          user-select: none;
}
.rc-color-picker-panel-params-lable label {
  float: left;
  text-align: center;
}
.rc-color-picker-panel-params-lable-hex {
  width: 52px;
}
.rc-color-picker-panel-params-lable-number,
.rc-color-picker-panel-params-lable-alpha {
  margin-left: 5px;
  width: 44px;
  text-transform: uppercase;
}
.rc-color-picker-panel-params-lable-number:hover {
  border-radius: 2px;
  background-color: #eee;
  box-shadow: 0 0 0 1px #ccc inset;
  cursor: pointer;
}
.rc-color-picker-panel-params-has-alpha input[type=number] {
  width: 32px;
}
.rc-color-picker-panel-params-has-alpha .rc-color-picker-panel-params-lable-number,
.rc-color-picker-panel-params-has-alpha .rc-color-picker-panel-params-lable-alpha {
  width: 32px;
}
.rc-color-picker {
  position: absolute;
  left: -9999px;
  top: -9999px;
  z-index: 1000;
}
.rc-color-picker-wrap {
  display: inline-block;
}
.rc-color-picker-slide-up-enter {
  animation-duration: .3s;
  animation-fill-mode: both;
  transform-origin: 0 0;
  display: block !important;
  opacity: 0;
  animation-timing-function: cubic-bezier(0.08, 0.82, 0.17, 1);
  animation-play-state: paused;
}
.rc-color-picker-slide-up-appear {
  animation-duration: .3s;
  animation-fill-mode: both;
  transform-origin: 0 0;
  display: block !important;
  opacity: 0;
  animation-timing-function: cubic-bezier(0.08, 0.82, 0.17, 1);
  animation-play-state: paused;
}
.rc-color-picker-slide-up-leave {
  animation-duration: .3s;
  animation-fill-mode: both;
  transform-origin: 0 0;
  display: block !important;
  opacity: 1;
  animation-timing-function: cubic-bezier(0.6, 0.04, 0.98, 0.34);
  animation-play-state: paused;
}
.rc-color-picker-slide-up-enter.rc-color-picker-slide-up-enter-active.rc-color-picker-placement-bottomLeft,
.rc-color-picker-slide-up-enter.rc-color-picker-slide-up-enter-active.rc-color-picker-placement-bottomRight,
.rc-color-picker-slide-up-appear.rc-color-picker-slide-up-appear-active.rc-color-picker-placement-bottomLeft,
.rc-color-picker-slide-up-appear.rc-color-picker-slide-up-appear-active.rc-color-picker-placement-bottomRight {
  animation-name: rcColorPickerSlideUpIn;
  animation-play-state: running;
}
.rc-color-picker-slide-up-enter.rc-color-picker-slide-up-enter-active.rc-color-picker-placement-topLeft,
.rc-color-picker-slide-up-enter.rc-color-picker-slide-up-enter-active.rc-color-picker-placement-topRight,
.rc-color-picker-slide-up-appear.rc-color-picker-slide-up-appear-active.rc-color-picker-placement-topLeft,
.rc-color-picker-slide-up-appear.rc-color-picker-slide-up-appear-active.rc-color-picker-placement-topRight {
  animation-name: rcColorPickerSlideDownIn;
  animation-play-state: running;
}
.rc-color-picker-slide-up-leave.rc-color-picker-slide-up-leave-active.rc-color-picker-placement-bottomLeft,
.rc-color-picker-slide-up-leave.rc-color-picker-slide-up-leave-active.rc-color-picker-placement-bottomRight {
  animation-name: rcColorPickerSlideUpOut;
  animation-play-state: running;
}
.rc-color-picker-slide-up-leave.rc-color-picker-slide-up-leave-active.rc-color-picker-placement-topLeft,
.rc-color-picker-slide-up-leave.rc-color-picker-slide-up-leave-active.rc-color-picker-placement-topRight {
  animation-name: rcColorPickerSlideDownOut;
  animation-play-state: running;
}
@keyframes rcColorPickerSlideUpIn {
  0% {
    opacity: 0;
    transform-origin: 0% 0%;
    transform: scaleY(0);
  }
  100% {
    opacity: 1;
    transform-origin: 0% 0%;
    transform: scaleY(1);
  }
}
@keyframes rcColorPickerSlideUpOut {
  0% {
    opacity: 1;
    transform-origin: 0% 0%;
    transform: scaleY(1);
  }
  100% {
    opacity: 0;
    transform-origin: 0% 0%;
    transform: scaleY(0);
  }
}
@keyframes rcColorPickerSlideDownIn {
  0% {
    opacity: 0;
    transform-origin: 100% 100%;
    transform: scaleY(0);
  }
  100% {
    opacity: 1;
    transform-origin: 100% 100%;
    transform: scaleY(1);
  }
}
@keyframes rcColorPickerSlideDownOut {
  0% {
    opacity: 1;
    transform-origin: 100% 100%;
    transform: scaleY(1);
  }
  100% {
    opacity: 0;
    transform-origin: 100% 100%;
    transform: scaleY(0);
  }
}
</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

.monaco-editor .accessibilityHelpWidget {
	padding: 10px;
	vertical-align: middle;
	overflow: scroll;
}</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

.monaco-aria-container {
	position: absolute; /* try to hide from window but not from screen readers */
	left:-999em;
}</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

.monaco-editor .selection-anchor {
	background-color: #007ACC;
	width: 2px !important;
}
</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

.monaco-editor .bracket-match {
	box-sizing: border-box;
}
</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

.monaco-editor .monaco-editor-overlaymessage {
	padding-bottom: 8px;
	z-index: 10000;
}

.monaco-editor .monaco-editor-overlaymessage.below {
	padding-bottom: 0;
	padding-top: 8px;
	z-index: 10000;
}

@keyframes fadeIn {
	from { opacity: 0; }
	to { opacity: 1; }
}
.monaco-editor .monaco-editor-overlaymessage.fadeIn {
	animation: fadeIn 150ms ease-out;
}

@keyframes fadeOut {
	from { opacity: 1; }
	to { opacity: 0; }
}
.monaco-editor .monaco-editor-overlaymessage.fadeOut {
	animation: fadeOut 100ms ease-out;
}

.monaco-editor .monaco-editor-overlaymessage .message {
	padding: 1px 4px;
}

.monaco-editor .monaco-editor-overlaymessage .anchor {
	width: 0 !important;
	height: 0 !important;
	border-color: transparent;
	border-style: solid;
	z-index: 1000;
	border-width: 8px;
	position: absolute;
}

.monaco-editor .monaco-editor-overlaymessage:not(.below) .anchor.top,
.monaco-editor .monaco-editor-overlaymessage.below .anchor.below {
	display: none;
}

.monaco-editor .monaco-editor-overlaymessage.below .anchor.top {
	display: inherit;
	top: -8px;
}
</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

.monaco-editor .contentWidgets .codicon-light-bulb,
.monaco-editor .contentWidgets .codicon-lightbulb-autofix {
	display: flex;
	align-items: center;
	justify-content: center;
}

.monaco-editor .contentWidgets .codicon-light-bulb:hover,
.monaco-editor .contentWidgets .codicon-lightbulb-autofix:hover {
	cursor: pointer;
}
</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

.monaco-editor .codelens-decoration {
	overflow: hidden;
	display: inline-block;
	text-overflow: ellipsis;
	white-space: nowrap;
}

.monaco-editor .codelens-decoration > span,
.monaco-editor .codelens-decoration > a {
	user-select: none;
	-webkit-user-select: none;
	-ms-user-select: none;
	white-space: nowrap;
	vertical-align: sub;
}

.monaco-editor .codelens-decoration > a {
	text-decoration: none;
}

.monaco-editor .codelens-decoration > a:hover {
	cursor: pointer;
}

.monaco-editor .codelens-decoration .codicon {
	vertical-align: middle;
	color: currentColor !important;
}

.monaco-editor .codelens-decoration > a:hover .codicon::before {
	cursor: pointer;
}

@keyframes fadein {
	0% { opacity: 0; visibility: visible;}
	100% { opacity: 1; }
}

.monaco-editor .codelens-decoration.fadein {
	animation: fadein 0.1s linear;
}
</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

.monaco-editor .goto-definition-link {
	text-decoration: underline;
	cursor: pointer;
}</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

.monaco-action-bar {
	white-space: nowrap;
	height: 100%;
}

.monaco-action-bar .actions-container {
	display: flex;
	margin: 0 auto;
	padding: 0;
	height: 100%;
	width: 100%;
	align-items: center;
}

.monaco-action-bar.vertical .actions-container {
	display: inline-block;
}

.monaco-action-bar .action-item {
	display: block;
	align-items: center;
	justify-content: center;
	cursor: pointer;
	position: relative;  /* DO NOT REMOVE - this is the key to preventing the ghosting icon bug in Chrome 42 */
}

.monaco-action-bar .action-item.disabled {
	cursor: default;
}

.monaco-action-bar .action-item .icon,
.monaco-action-bar .action-item .codicon {
	display: block;
}

.monaco-action-bar .action-item .codicon {
	display: flex;
	align-items: center;
	width: 16px;
	height: 16px;
}

.monaco-action-bar .action-label {
	font-size: 11px;
	padding: 3px;
	border-radius: 5px;
}

.monaco-action-bar .action-item.disabled .action-label,
.monaco-action-bar .action-item.disabled .action-label::before,
.monaco-action-bar .action-item.disabled .action-label:hover {
	opacity: 0.4;
}

/* Vertical actions */

.monaco-action-bar.vertical {
	text-align: left;
}

.monaco-action-bar.vertical .action-item {
	display: block;
}

.monaco-action-bar.vertical .action-label.separator {
	display: block;
	border-bottom: 1px solid #bbb;
	padding-top: 1px;
	margin-left: .8em;
	margin-right: .8em;
}

.monaco-action-bar .action-item .action-label.separator {
	width: 1px;
	height: 16px;
	margin: 5px 4px !important;
	cursor: default;
	min-width: 1px;
	padding: 0;
	background-color: #bbb;
}

.secondary-actions .monaco-action-bar .action-label {
	margin-left: 6px;
}

/* Action Items */
.monaco-action-bar .action-item.select-container {
	overflow: hidden; /* somehow the dropdown overflows its container, we prevent it here to not push */
	flex: 1;
	max-width: 170px;
	min-width: 60px;
	display: flex;
	align-items: center;
	justify-content: center;
	margin-right: 10px;
}

.monaco-action-bar .action-item.action-dropdown-item {
	display: flex;
}

.monaco-action-bar .action-item.action-dropdown-item > .action-label {
	margin-right: 1px;
}
</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

.monaco-editor .peekview-widget .head {
	box-sizing: border-box;
	display: flex;
}

.monaco-editor .peekview-widget .head .peekview-title {
	display: flex;
	align-items: center;
	font-size: 13px;
	margin-left: 20px;
	min-width: 0;
}

.monaco-editor .peekview-widget .head .peekview-title.clickable {
	cursor: pointer;
}

.monaco-editor .peekview-widget .head .peekview-title .dirname:not(:empty) {
	font-size: 0.9em;
	margin-left: 0.5em;
}

.monaco-editor .peekview-widget .head .peekview-title .meta {
	white-space: nowrap;
}

.monaco-editor .peekview-widget .head .peekview-title .dirname {
	white-space: nowrap;
}

.monaco-editor .peekview-widget .head .peekview-title .filename {
	overflow: hidden;
	text-overflow: ellipsis;
	white-space: nowrap;
}

.monaco-editor .peekview-widget .head .peekview-title .meta:not(:empty)::before {
	content: '-';
	padding: 0 0.3em;
}

.monaco-editor .peekview-widget .head .peekview-actions {
	flex: 1;
	text-align: right;
	padding-right: 2px;
}

.monaco-editor .peekview-widget .head .peekview-actions > .monaco-action-bar {
	display: inline-block;
}

.monaco-editor .peekview-widget .head .peekview-actions > .monaco-action-bar,
.monaco-editor .peekview-widget .head .peekview-actions > .monaco-action-bar > .actions-container {
	height: 100%;
}

.monaco-editor .peekview-widget > .body {
	border-top: 1px solid;
	position: relative;
}

.monaco-editor .peekview-widget .head .peekview-title .codicon {
	margin-right: 4px;
}

.monaco-editor .peekview-widget .monaco-list .monaco-list-row.focused .codicon {
	color: inherit !important;
}
</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

/* -------------------- IE10 remove auto clear button -------------------- */

::-ms-clear {
	display: none;
}

/* All widgets */
/* I am not a big fan of this rule */
.monaco-editor .editor-widget input {
	color: inherit;
}

/* -------------------- Editor -------------------- */

.monaco-editor {
	position: relative;
	overflow: visible;
	-webkit-text-size-adjust: 100%;
}

/* -------------------- Misc -------------------- */

.monaco-editor .overflow-guard {
	position: relative;
	overflow: hidden;
}

.monaco-editor .view-overlays {
	position: absolute;
	top: 0;
}

/*
.monaco-editor .auto-closed-character {
	opacity: 0.3;
}
*/
</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

.monaco-editor .inputarea {
	min-width: 0;
	min-height: 0;
	margin: 0;
	padding: 0;
	position: absolute;
	outline: none !important;
	resize: none;
	border: none;
	overflow: hidden;
	color: transparent;
	background-color: transparent;
}
/*.monaco-editor .inputarea {
	position: fixed !important;
	width: 800px !important;
	height: 500px !important;
	top: initial !important;
	left: initial !important;
	bottom: 0 !important;
	right: 0 !important;
	color: black !important;
	background: white !important;
	line-height: 15px !important;
	font-size: 14px !important;
}*/
.monaco-editor .inputarea.ime-input {
	z-index: 10;
}
</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

.monaco-editor .margin-view-overlays .line-numbers {
	font-variant-numeric: tabular-nums;
	position: absolute;
	text-align: right;
	display: inline-block;
	vertical-align: middle;
	box-sizing: border-box;
	cursor: default;
	height: 100%;
}

.monaco-editor .relative-current-line-number {
	text-align: left;
	display: inline-block;
	width: 100%;
}

.monaco-editor .margin-view-overlays .line-numbers.lh-odd {
	margin-top: 1px;
}
</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

.monaco-mouse-cursor-text {
	cursor: text;
}

/* The following selector looks a bit funny, but that is needed to cover all the workbench and the editor!! */
.vs-dark .mac .monaco-mouse-cursor-text, .hc-black .mac .monaco-mouse-cursor-text,
.vs-dark.mac .monaco-mouse-cursor-text, .hc-black.mac .monaco-mouse-cursor-text {
	cursor: -webkit-image-set(url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAQAAAC1+jfqAAAAL0lEQVQoz2NgCD3x//9/BhBYBWdhgFVAiVW4JBFKGIa4AqD0//9D3pt4I4tAdAMAHTQ/j5Zom30AAAAASUVORK5CYII=) 1x, url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACAAAAAgCAQAAADZc7J/AAAAz0lEQVRIx2NgYGBY/R8I/vx5eelX3n82IJ9FxGf6tksvf/8FiTMQAcAGQMDvSwu09abffY8QYSAScNk45G198eX//yev73/4///701eh//kZSARckrNBRvz//+8+6ZohwCzjGNjdgQxkAg7B9WADeBjIBqtJCbhRA0YNoIkBSNmaPEMoNmA0FkYNoFKhapJ6FGyAH3nauaSmPfwI0v/3OukVi0CIZ+F25KrtYcx/CTIy0e+rC7R1Z4KMICVTQQ14feVXIbR695u14+Ir4gwAAD49E54wc1kWAAAAAElFTkSuQmCC) 2x) 5 8, text;
}
</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

.monaco-editor .view-overlays .current-line {
	display: block;
	position: absolute;
	left: 0;
	top: 0;
	box-sizing: border-box;
}

.monaco-editor .margin-view-overlays .current-line {
	display: block;
	position: absolute;
	left: 0;
	top: 0;
	box-sizing: border-box;
}

.monaco-editor .margin-view-overlays .current-line.current-line-margin.current-line-margin-both {
	border-right: 0;
}
</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

/*
	Keeping name short for faster parsing.
	cdr = core decorations rendering (div)
*/
.monaco-editor .lines-content .cdr {
	position: absolute;
}</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

/* Arrows */
.monaco-scrollable-element > .scrollbar > .scra {
	cursor: pointer;
	font-size: 11px !important;
}

.monaco-scrollable-element > .visible {
	opacity: 1;

	/* Background rule added for IE9 - to allow clicks on dom node */
	background:rgba(0,0,0,0);

	transition: opacity 100ms linear;
}
.monaco-scrollable-element > .invisible {
	opacity: 0;
	pointer-events: none;
}
.monaco-scrollable-element > .invisible.fade {
	transition: opacity 800ms linear;
}

/* Scrollable Content Inset Shadow */
.monaco-scrollable-element > .shadow {
	position: absolute;
	display: none;
}
.monaco-scrollable-element > .shadow.top {
	display: block;
	top: 0;
	left: 3px;
	height: 3px;
	width: 100%;
}
.monaco-scrollable-element > .shadow.left {
	display: block;
	top: 3px;
	left: 0;
	height: 100%;
	width: 3px;
}
.monaco-scrollable-element > .shadow.top-left-corner {
	display: block;
	top: 0;
	left: 0;
	height: 3px;
	width: 3px;
}
</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

.monaco-editor .glyph-margin {
	position: absolute;
	top: 0;
}

/*
	Keeping name short for faster parsing.
	cgmr = core glyph margin rendering (div)
*/
.monaco-editor .margin-view-overlays .cgmr {
	position: absolute;
	display: flex;
	align-items: center;
	justify-content: center;
}
</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

.monaco-editor .lines-content .core-guide {
	position: absolute;
	box-sizing: border-box;
}
</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

/* Uncomment to see lines flashing when they're painted */
/*.monaco-editor .view-lines > .view-line {
	background-color: none;
	animation-name: flash-background;
	animation-duration: 800ms;
}
@keyframes flash-background {
	0%   { background-color: lightgreen; }
	100% { background-color: none }
}*/

.mtkcontrol {
	color: rgb(255, 255, 255) !important;
	background: rgb(150, 0, 0) !important;
}

.monaco-editor.no-user-select .lines-content,
.monaco-editor.no-user-select .view-line,
.monaco-editor.no-user-select .view-lines {
	user-select: none;
	-webkit-user-select: none;
	-ms-user-select: none;
}

.monaco-editor .view-lines {
	white-space: nowrap;
}

.monaco-editor .view-line {
	position: absolute;
	width: 100%;
}

.monaco-editor .mtkz {
	display: inline-block;
}

/* TODO@tokenization bootstrap fix */
/*.monaco-editor .view-line > span > span {
	float: none;
	min-height: inherit;
	margin-left: inherit;
}*/
</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/
.monaco-editor .lines-decorations {
	position: absolute;
	top: 0;
	background: white;
}

/*
	Keeping name short for faster parsing.
	cldr = core lines decorations rendering (div)
*/
.monaco-editor .margin-view-overlays .cldr {
	position: absolute;
	height: 100%;
}</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

/*
	Keeping name short for faster parsing.
	cmdr = core margin decorations rendering (div)
*/
.monaco-editor .margin-view-overlays .cmdr {
	position: absolute;
	left: 0;
	width: 100%;
	height: 100%;
}</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

/* START cover the case that slider is visible on mouseover */
.monaco-editor .minimap.slider-mouseover .minimap-slider {
	opacity: 0;
	transition: opacity 100ms linear;
}
.monaco-editor .minimap.slider-mouseover:hover .minimap-slider {
	opacity: 1;
}
.monaco-editor .minimap.slider-mouseover .minimap-slider.active {
	opacity: 1;
}
/* END cover the case that slider is visible on mouseover */

.monaco-editor .minimap-shadow-hidden {
	position: absolute;
	width: 0;
}
.monaco-editor .minimap-shadow-visible {
	position: absolute;
	left: -6px;
	width: 6px;
}
.monaco-editor.no-minimap-shadow .minimap-shadow-visible {
	position: absolute;
	left: -1px;
	width: 1px;
}
</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/
.monaco-editor .overlayWidgets {
	position: absolute;
	top: 0;
	left:0;
}</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

.monaco-editor .view-ruler {
	position: absolute;
	top: 0;
}</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

.monaco-editor .scroll-decoration {
	position: absolute;
	top: 0;
	left: 0;
	height: 6px;
}</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

/*
	Keeping name short for faster parsing.
	cslr = core selections layer rendering (div)
*/
.monaco-editor .lines-content .cslr {
	position: absolute;
}

.monaco-editor			.top-left-radius		{ border-top-left-radius: 3px; }
.monaco-editor			.bottom-left-radius		{ border-bottom-left-radius: 3px; }
.monaco-editor			.top-right-radius		{ border-top-right-radius: 3px; }
.monaco-editor			.bottom-right-radius	{ border-bottom-right-radius: 3px; }

.monaco-editor.hc-black .top-left-radius		{ border-top-left-radius: 0; }
.monaco-editor.hc-black .bottom-left-radius		{ border-bottom-left-radius: 0; }
.monaco-editor.hc-black .top-right-radius		{ border-top-right-radius: 0; }
.monaco-editor.hc-black .bottom-right-radius	{ border-bottom-right-radius: 0; }
</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/
.monaco-editor .cursors-layer {
	position: absolute;
	top: 0;
}

.monaco-editor .cursors-layer > .cursor {
	position: absolute;
	overflow: hidden;
}

/* -- smooth-caret-animation -- */
.monaco-editor .cursors-layer.cursor-smooth-caret-animation > .cursor {
	transition: all 80ms;
}

/* -- block-outline-style -- */
.monaco-editor .cursors-layer.cursor-block-outline-style > .cursor {
	box-sizing: border-box;
	background: transparent !important;
	border-style: solid;
	border-width: 1px;
}

/* -- underline-style -- */
.monaco-editor .cursors-layer.cursor-underline-style > .cursor {
	border-bottom-width: 2px;
	border-bottom-style: solid;
	background: transparent !important;
	box-sizing: border-box;
}

/* -- underline-thin-style -- */
.monaco-editor .cursors-layer.cursor-underline-thin-style > .cursor {
	border-bottom-width: 1px;
	border-bottom-style: solid;
	background: transparent !important;
	box-sizing: border-box;
}

@keyframes monaco-cursor-smooth {
	0%,
	20% {
		opacity: 1;
	}
	60%,
	100% {
		opacity: 0;
	}
}

@keyframes monaco-cursor-phase {
	0%,
	20% {
		opacity: 1;
	}
	90%,
	100% {
		opacity: 0;
	}
}

@keyframes monaco-cursor-expand {
	0%,
	20% {
		transform: scaleY(1);
	}
	80%,
	100% {
		transform: scaleY(0);
	}
}

.cursor-smooth {
	animation: monaco-cursor-smooth 0.5s ease-in-out 0s 20 alternate;
}

.cursor-phase {
	animation: monaco-cursor-phase 0.5s ease-in-out 0s 20 alternate;
}

.cursor-expand > .cursor {
	animation: monaco-cursor-expand 0.5s ease-in-out 0s 20 alternate;
}
</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

:root {
	--sash-size: 4px;
}

.monaco-sash {
	position: absolute;
	z-index: 35;
	touch-action: none;
}

.monaco-sash.disabled {
	pointer-events: none;
}

.monaco-sash.mac.vertical {
	cursor: col-resize;
}

.monaco-sash.vertical.minimum {
	cursor: e-resize;
}

.monaco-sash.vertical.maximum {
	cursor: w-resize;
}

.monaco-sash.mac.horizontal {
	cursor: row-resize;
}

.monaco-sash.horizontal.minimum {
	cursor: s-resize;
}

.monaco-sash.horizontal.maximum {
	cursor: n-resize;
}

.monaco-sash.disabled {
	cursor: default !important;
	pointer-events: none !important;
}

.monaco-sash.vertical {
	cursor: ew-resize;
	top: 0;
	width: var(--sash-size);
	height: 100%;
}

.monaco-sash.horizontal {
	cursor: ns-resize;
	left: 0;
	width: 100%;
	height: var(--sash-size);
}

.monaco-sash:not(.disabled) > .orthogonal-drag-handle {
	content: " ";
	height: calc(var(--sash-size) * 2);
	width: calc(var(--sash-size) * 2);
	z-index: 100;
	display: block;
	cursor: all-scroll;
	position: absolute;
}

.monaco-sash.horizontal.orthogonal-edge-north:not(.disabled)
	> .orthogonal-drag-handle.start,
.monaco-sash.horizontal.orthogonal-edge-south:not(.disabled)
	> .orthogonal-drag-handle.end {
	cursor: nwse-resize;
}

.monaco-sash.horizontal.orthogonal-edge-north:not(.disabled)
	> .orthogonal-drag-handle.end,
.monaco-sash.horizontal.orthogonal-edge-south:not(.disabled)
	> .orthogonal-drag-handle.start {
	cursor: nesw-resize;
}

.monaco-sash.vertical > .orthogonal-drag-handle.start {
	left: calc(var(--sash-size) * -0.5);
	top: calc(var(--sash-size) * -1);
}
.monaco-sash.vertical > .orthogonal-drag-handle.end {
	left: calc(var(--sash-size) * -0.5);
	bottom: calc(var(--sash-size) * -1);
}
.monaco-sash.horizontal > .orthogonal-drag-handle.start {
	top: calc(var(--sash-size) * -0.5);
	left: calc(var(--sash-size) * -1);
}
.monaco-sash.horizontal > .orthogonal-drag-handle.end {
	top: calc(var(--sash-size) * -0.5);
	right: calc(var(--sash-size) * -1);
}

.monaco-sash:before {
	content: '';
	pointer-events: none;
	position: absolute;
	width: 100%;
	height: 100%;
	transition: background-color 0.1s ease-out;
	background: transparent;
}

.monaco-sash.vertical:before {
	width: var(--sash-hover-size);
	left: calc(50% - (var(--sash-hover-size) / 2));
}

.monaco-sash.horizontal:before {
	height: var(--sash-hover-size);
	top: calc(50% - (var(--sash-hover-size) / 2));
}

/** Debug **/

.monaco-sash.debug {
	background: cyan;
}

.monaco-sash.debug.disabled {
	background: rgba(0, 255, 255, 0.2);
}

.monaco-sash.debug:not(.disabled) > .orthogonal-drag-handle {
	background: red;
}
</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/
.monaco-editor .zone-widget {
	position: absolute;
	z-index: 10;
}


.monaco-editor .zone-widget .zone-widget-container {
	border-top-style: solid;
	border-bottom-style: solid;
	border-top-width: 0;
	border-bottom-width: 0;
	position: relative;
}
</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

.monaco-dropdown {
	height: 100%;
	padding: 0;
}

.monaco-dropdown > .dropdown-label {
	cursor: pointer;
	height: 100%;
	display: flex;
	align-items: center;
	justify-content: center;
}

.monaco-dropdown > .dropdown-label > .action-label.disabled {
	cursor: default;
}

.monaco-dropdown-with-primary {
	display: flex !important;
	flex-direction: row;
	border-radius: 5px;
}

.monaco-dropdown-with-primary > .action-container > .action-label {
	margin-right: 0;
}

.monaco-dropdown-with-primary > .dropdown-action-container > .monaco-dropdown > .dropdown-label .codicon[class*='codicon-'] {
	font-size: 12px;
	padding-left: 0px;
	padding-right: 0px;
	line-height: 16px;
	margin-left: -3px;
}

.monaco-dropdown-with-primary > .dropdown-action-container > .monaco-dropdown > .dropdown-label > .action-label {
	display: block;
	background-size: 16px;
	background-position: center center;
	background-repeat: no-repeat;
}
</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

.monaco-action-bar .action-item.menu-entry .action-label.icon {
	width: 16px;
	height: 16px;
	background-repeat: no-repeat;
	background-position: 50%;
	background-size: 16px;
}

.monaco-action-bar .action-item.menu-entry .action-label {
	background-image: var(--menu-entry-icon-light);
}

.vs-dark .monaco-action-bar .action-item.menu-entry .action-label,
.hc-black .monaco-action-bar .action-item.menu-entry .action-label {
	background-image: var(--menu-entry-icon-dark);
}


.monaco-dropdown-with-default {
	display: flex !important;
	flex-direction: row;
	border-radius: 5px;
}

.monaco-dropdown-with-default > .action-container > .action-label {
	margin-right: 0;
}

.monaco-dropdown-with-default > .action-container.menu-entry > .action-label.icon {
	width: 16px;
	height: 16px;
	background-repeat: no-repeat;
	background-position: 50%;
	background-size: 16px;
}

.monaco-dropdown-with-default > .action-container.menu-entry > .action-label {
	background-image: var(--menu-entry-icon-light);
}

.vs-dark .monaco-dropdown-with-default > .action-container.menu-entry > .action-label,
.hc-black .monaco-dropdown-with-default > .action-container.menu-entry > .action-label {
	background-image: var(--menu-entry-icon-dark);
}

.monaco-dropdown-with-default > .dropdown-action-container > .monaco-dropdown > .dropdown-label .codicon[class*='codicon-'] {
	font-size: 12px;
	padding-left: 0px;
	padding-right: 0px;
	line-height: 16px;
	margin-left: -3px;
}

.monaco-dropdown-with-default > .dropdown-action-container > .monaco-dropdown > .dropdown-label > .action-label {
	display: block;
	background-size: 16px;
	background-position: center center;
	background-repeat: no-repeat;
}
</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

.monaco-list {
	position: relative;
	height: 100%;
	width: 100%;
	white-space: nowrap;
}

.monaco-list.mouse-support {
	user-select: none;
	-webkit-user-select: none;
	-ms-user-select: none;
}

.monaco-list > .monaco-scrollable-element {
	height: 100%;
}

.monaco-list-rows {
	position: relative;
	width: 100%;
	height: 100%;
}

.monaco-list.horizontal-scrolling .monaco-list-rows {
	width: auto;
	min-width: 100%;
}

.monaco-list-row {
	position: absolute;
	box-sizing: border-box;
	overflow: hidden;
	width: 100%;
}

.monaco-list.mouse-support .monaco-list-row {
	cursor: pointer;
	touch-action: none;
}

/* for OS X ballistic scrolling */
.monaco-list-row.scrolling {
	display: none !important;
}

/* Focus */
.monaco-list.element-focused,
.monaco-list.selection-single,
.monaco-list.selection-multiple {
	outline: 0 !important;
}

/* Dnd */
.monaco-drag-image {
	display: inline-block;
	padding: 1px 7px;
	border-radius: 10px;
	font-size: 12px;
	position: absolute;
	z-index: 1000;
}

/* Type filter */

.monaco-list-type-filter {
	display: flex;
	align-items: center;
	position: absolute;
	border-radius: 2px;
	padding: 0px 3px;
	max-width: calc(100% - 10px);
	text-overflow: ellipsis;
	overflow: hidden;
	text-align: right;
	box-sizing: border-box;
	cursor: all-scroll;
	font-size: 13px;
	line-height: 18px;
	height: 20px;
	z-index: 1;
	top: 4px;
}

.monaco-list-type-filter.dragging {
	transition: top 0.2s, left 0.2s;
}

.monaco-list-type-filter.ne {
	right: 4px;
}

.monaco-list-type-filter.nw {
	left: 4px;
}

.monaco-list-type-filter > .controls {
	display: flex;
	align-items: center;
	box-sizing: border-box;
	transition: width 0.2s;
	width: 0;
}

.monaco-list-type-filter.dragging > .controls,
.monaco-list-type-filter:hover > .controls {
	width: 36px;
}

.monaco-list-type-filter > .controls > * {
	border: none;
	box-sizing: border-box;
	-webkit-appearance: none;
	-moz-appearance: none;
	background: none;
	width: 16px;
	height: 16px;
	flex-shrink: 0;
	margin: 0;
	padding: 0;
	display: flex;
	align-items: center;
	justify-content: center;
	cursor: pointer;
}

.monaco-list-type-filter > .controls > .filter {
	margin-left: 4px;
}

.monaco-list-type-filter-message {
	position: absolute;
	box-sizing: border-box;
	width: 100%;
	height: 100%;
	top: 0;
	left: 0;
	padding: 40px 1em 1em 1em;
	text-align: center;
	white-space: normal;
	opacity: 0.7;
	pointer-events: none;
}

.monaco-list-type-filter-message:empty {
	display: none;
}

/* Electron */

.monaco-list-type-filter {
	cursor: grab;
}

.monaco-list-type-filter.dragging {
	cursor: grabbing;
}
</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

.monaco-split-view2 {
	position: relative;
	width: 100%;
	height: 100%;
}

.monaco-split-view2 > .sash-container {
	position: absolute;
	width: 100%;
	height: 100%;
	pointer-events: none;
}

.monaco-split-view2 > .sash-container > .monaco-sash {
	pointer-events: initial;
}

.monaco-split-view2 > .monaco-scrollable-element {
	width: 100%;
	height: 100%;
}

.monaco-split-view2 > .monaco-scrollable-element > .split-view-container {
	width: 100%;
	height: 100%;
	white-space: nowrap;
	position: relative;
}

.monaco-split-view2 > .monaco-scrollable-element > .split-view-container > .split-view-view {
	white-space: initial;
	position: absolute;
}

.monaco-split-view2 > .monaco-scrollable-element > .split-view-container > .split-view-view:not(.visible) {
	display: none;
}

.monaco-split-view2.vertical > .monaco-scrollable-element > .split-view-container > .split-view-view {
	width: 100%;
}

.monaco-split-view2.horizontal > .monaco-scrollable-element > .split-view-container > .split-view-view {
	height: 100%;
}

.monaco-split-view2.separator-border > .monaco-scrollable-element > .split-view-container > .split-view-view:not(:first-child)::before {
	content: ' ';
	position: absolute;
	top: 0;
	left: 0;
	z-index: 5;
	pointer-events: none;
	background-color: var(--separator-border);
}

.monaco-split-view2.separator-border.horizontal > .monaco-scrollable-element > .split-view-container > .split-view-view:not(:first-child)::before {
	height: 100%;
	width: 1px;
}

.monaco-split-view2.separator-border.vertical > .monaco-scrollable-element > .split-view-container > .split-view-view:not(:first-child)::before {
	height: 1px;
	width: 100%;
}
</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

.monaco-table {
	display: flex;
	flex-direction: column;
	position: relative;
	height: 100%;
	width: 100%;
	white-space: nowrap;
}

.monaco-table > .monaco-split-view2 {
	border-bottom: 1px solid transparent;
}

.monaco-table > .monaco-list {
	flex: 1;
}

.monaco-table-tr {
	display: flex;
	height: 100%;
}

.monaco-table-th {
	width: 100%;
	height: 100%;
	font-weight: bold;
	overflow: hidden;
	text-overflow: ellipsis;
}

.monaco-table-th,
.monaco-table-td {
	box-sizing: border-box;
	flex-shrink: 0;
	overflow: hidden;
	white-space: nowrap;
	text-overflow: ellipsis;
}

.monaco-table > .monaco-split-view2 .monaco-sash.vertical::before {
	content: "";
	position: absolute;
	left: calc(var(--sash-size) / 2);
	width: 0;
	border-left: 1px solid transparent;
}

.monaco-table > .monaco-split-view2,
.monaco-table > .monaco-split-view2 .monaco-sash.vertical::before {
	transition: border-color 0.2s ease-out;
}
/*
.monaco-table:hover > .monaco-split-view2,
.monaco-table:hover > .monaco-split-view2 .monaco-sash.vertical::before {
	border-color: rgba(204, 204, 204, 0.2);
} */
</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

.monaco-tl-row {
	display: flex;
	height: 100%;
	align-items: center;
	position: relative;
}

.monaco-tl-indent {
	height: 100%;
	position: absolute;
	top: 0;
	left: 16px;
	pointer-events: none;
}

.hide-arrows .monaco-tl-indent {
	left: 12px;
}

.monaco-tl-indent > .indent-guide {
	display: inline-block;
	box-sizing: border-box;
	height: 100%;
	border-left: 1px solid transparent;
}

.monaco-tl-indent > .indent-guide {
	transition: border-color 0.1s linear;
}

.monaco-tl-twistie,
.monaco-tl-contents {
	height: 100%;
}

.monaco-tl-twistie {
	font-size: 10px;
	text-align: right;
	padding-right: 6px;
	flex-shrink: 0;
	width: 16px;
	display: flex !important;
	align-items: center;
	justify-content: center;
	transform: translateX(3px);
}

.monaco-tl-contents {
	flex: 1;
	overflow: hidden;
}

.monaco-tl-twistie::before {
	border-radius: 20px;
}

.monaco-tl-twistie.collapsed::before {
	transform: rotate(-90deg);
}

.monaco-tl-twistie.codicon-tree-item-loading::before {
	/* Use steps to throttle FPS to reduce CPU usage */
	animation: codicon-spin 1.25s steps(30) infinite;
}
</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

/* -- zone widget */
.monaco-editor .zone-widget .zone-widget-container.reference-zone-widget {
	border-top-width: 1px;
	border-bottom-width: 1px;
}

.monaco-editor .reference-zone-widget .inline {
	display: inline-block;
	vertical-align: top;
}

.monaco-editor .reference-zone-widget .messages {
	height: 100%;
	width: 100%;
	text-align: center;
	padding: 3em 0;
}

.monaco-editor .reference-zone-widget .ref-tree {
	line-height: 23px;
}

.monaco-editor .reference-zone-widget .ref-tree .reference {
	text-overflow: ellipsis;
	overflow: hidden;
}

.monaco-editor .reference-zone-widget .ref-tree .reference-file {
	display: inline-flex;
	width: 100%;
	height: 100%;
}

.monaco-editor .reference-zone-widget .ref-tree .monaco-list:focus .selected .reference-file {
	color: inherit !important;
}

.monaco-editor .reference-zone-widget .ref-tree .reference-file .count {
	margin-right: 12px;
	margin-left: auto;
}

/* High Contrast Theming */

.monaco-editor.hc-black .reference-zone-widget .ref-tree .reference-file {
	font-weight: bold;
}
</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

.monaco-count-badge {
	padding: 3px 6px;
	border-radius: 11px;
	font-size: 11px;
	min-width: 18px;
	min-height: 18px;
	line-height: 11px;
	font-weight: normal;
	text-align: center;
	display: inline-block;
	box-sizing: border-box;
}

.monaco-count-badge.long {
	padding: 2px 3px;
	border-radius: 2px;
	min-height: auto;
	line-height: normal;
}
</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

/* ---------- Icon label ---------- */

.monaco-icon-label {
	display: flex; /* required for icons support :before rule */
	overflow: hidden;
	text-overflow: ellipsis;
}

.monaco-icon-label::before {

	/* svg icons rendered as background image */
	background-size: 16px;
	background-position: left center;
	background-repeat: no-repeat;
	padding-right: 6px;
	width: 16px;
	height: 22px;
	line-height: inherit !important;
	display: inline-block;

	/* fonts icons */
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
	vertical-align: top;

	flex-shrink: 0; /* fix for https://github.com/microsoft/vscode/issues/13787 */
}

.monaco-icon-label > .monaco-icon-label-container {
	min-width: 0;
	overflow: hidden;
	text-overflow: ellipsis;
	flex: 1;
}

.monaco-icon-label > .monaco-icon-label-container > .monaco-icon-name-container > .label-name {
	color: inherit;
	white-space: pre; /* enable to show labels that include multiple whitespaces */
}

.monaco-icon-label > .monaco-icon-label-container > .monaco-icon-name-container > .label-name > .label-separator {
	margin: 0 2px;
	opacity: 0.5;
}

.monaco-icon-label > .monaco-icon-label-container > .monaco-icon-description-container > .label-description {
	opacity: .7;
	margin-left: 0.5em;
	font-size: 0.9em;
	white-space: pre; /* enable to show labels that include multiple whitespaces */
}

.monaco-icon-label.nowrap > .monaco-icon-label-container > .monaco-icon-description-container > .label-description{
	white-space: nowrap
}

.vs .monaco-icon-label > .monaco-icon-label-container > .monaco-icon-description-container > .label-description {
	opacity: .95;
}

.monaco-icon-label.italic > .monaco-icon-label-container > .monaco-icon-name-container > .label-name,
.monaco-icon-label.italic > .monaco-icon-label-container > .monaco-icon-description-container > .label-description {
	font-style: italic;
}

.monaco-icon-label.deprecated {
	text-decoration: line-through;
	opacity: 0.66;
}

/* make sure apply italic font style to decorations as well */
.monaco-icon-label.italic::after {
	font-style: italic;
}

.monaco-icon-label.strikethrough > .monaco-icon-label-container > .monaco-icon-name-container > .label-name,
.monaco-icon-label.strikethrough > .monaco-icon-label-container > .monaco-icon-description-container > .label-description {
	text-decoration: line-through;
}

.monaco-icon-label::after {
	opacity: 0.75;
	font-size: 90%;
	font-weight: 600;
	margin: auto 16px 0 5px; /* https://github.com/microsoft/vscode/issues/113223 */
	text-align: center;
}

/* make sure selection color wins when a label is being selected */
.monaco-list:focus .selected .monaco-icon-label, /* list */
.monaco-list:focus .selected .monaco-icon-label::after
{
	color: inherit !important;
}

.monaco-list-row.focused.selected .label-description,
.monaco-list-row.selected .label-description {
	opacity: .8;
}
</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

.monaco-hover {
	cursor: default;
	position: absolute;
	overflow: hidden;
	z-index: 50;
	user-select: text;
	-webkit-user-select: text;
	-ms-user-select: text;
	box-sizing: initial;
	animation: fadein 100ms linear;
	line-height: 1.5em;
}

.monaco-hover.hidden {
	display: none;
}

.monaco-hover .hover-contents:not(.html-hover-contents) {
	padding: 4px 8px;
}

.monaco-hover .markdown-hover > .hover-contents:not(.code-hover-contents) {
	max-width: 500px;
	word-wrap: break-word;
}

.monaco-hover .markdown-hover > .hover-contents:not(.code-hover-contents) hr {
	min-width: 100%;
}

.monaco-hover p,
.monaco-hover .code,
.monaco-hover ul {
	margin: 8px 0;
}

.monaco-hover code {
	font-family: var(--monaco-monospace-font);
}

.monaco-hover hr {
	box-sizing: border-box;
	border-left: 0px;
	border-right: 0px;
	margin-top: 4px;
	margin-bottom: -4px;
	margin-left: -8px;
	margin-right: -8px;
	height: 1px;
}

.monaco-hover p:first-child,
.monaco-hover .code:first-child,
.monaco-hover ul:first-child {
	margin-top: 0;
}

.monaco-hover p:last-child,
.monaco-hover .code:last-child,
.monaco-hover ul:last-child {
	margin-bottom: 0;
}

/* MarkupContent Layout */
.monaco-hover ul {
	padding-left: 20px;
}
.monaco-hover ol {
	padding-left: 20px;
}

.monaco-hover li > p {
	margin-bottom: 0;
}

.monaco-hover li > ul {
	margin-top: 0;
}

.monaco-hover code {
	border-radius: 3px;
	padding: 0 0.4em;
}

.monaco-hover .monaco-tokenized-source {
	white-space: pre-wrap;
}

.monaco-hover .hover-row.status-bar {
	font-size: 12px;
	line-height: 22px;
}

.monaco-hover .hover-row.status-bar .actions {
	display: flex;
	padding: 0px 8px;
}

.monaco-hover .hover-row.status-bar .actions .action-container {
	margin-right: 16px;
	cursor: pointer;
}

.monaco-hover .hover-row.status-bar .actions .action-container .action .icon {
	padding-right: 4px;
}

.monaco-hover .markdown-hover .hover-contents .codicon {
	color: inherit;
	font-size: inherit;
	vertical-align: middle;
}

.monaco-hover .hover-contents a.code-link:hover,
.monaco-hover .hover-contents a.code-link {
	color: inherit;
}

.monaco-hover .hover-contents a.code-link:before {
	content: '(';
}

.monaco-hover .hover-contents a.code-link:after {
	content: ')';
}

.monaco-hover .hover-contents a.code-link > span {
	text-decoration: underline;
	/** Hack to force underline to show **/
	border-bottom: 1px solid transparent;
	text-underline-position: under;
}

/** Spans in markdown hovers need a margin-bottom to avoid looking cramped: https://github.com/microsoft/vscode/issues/101496 **/
.monaco-hover .markdown-hover .hover-contents:not(.code-hover-contents):not(.html-hover-contents) span {
	margin-bottom: 4px;
	display: inline-block;
}

.monaco-hover-content .action-container a {
	-webkit-user-select: none;
	user-select: none;
}

.monaco-hover-content .action-container.disabled {
	pointer-events: none;
	opacity: 0.4;
	cursor: default;
}
</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

.colorpicker-widget {
	height: 190px;
	user-select: none;
	-webkit-user-select: none;
	-ms-user-select: none;
}

.monaco-editor .colorpicker-hover:focus {
	outline: none;
}


/* Header */

.colorpicker-header {
	display: flex;
	height: 24px;
	position: relative;
	background: url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAQAAAAECAYAAACp8Z5+AAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsMAAA7DAcdvqGQAAAAZdEVYdFNvZnR3YXJlAHBhaW50Lm5ldCA0LjAuMTZEaa/1AAAAHUlEQVQYV2PYvXu3JAi7uLiAMaYAjAGTQBPYLQkAa/0Zef3qRswAAAAASUVORK5CYII=");
	background-size: 9px 9px;
	image-rendering: pixelated;
}

.colorpicker-header .picked-color {
	width: 216px;
	display: flex;
	align-items: center;
	justify-content: center;
	line-height: 24px;
	cursor: pointer;
	color: white;
	flex: 1;
}

.colorpicker-header .picked-color .codicon {
	color: inherit;
	font-size: 14px;
	position: absolute;
	left: 8px;
}

.colorpicker-header .picked-color.light {
	color: black;
}

.colorpicker-header .original-color {
	width: 74px;
	z-index: inherit;
	cursor: pointer;
}


/* Body */

.colorpicker-body {
	display: flex;
	padding: 8px;
	position: relative;
}

.colorpicker-body .saturation-wrap {
	overflow: hidden;
	height: 150px;
	position: relative;
	min-width: 220px;
	flex: 1;
}

.colorpicker-body .saturation-box {
	height: 150px;
	position: absolute;
}

.colorpicker-body .saturation-selection {
	width: 9px;
	height: 9px;
	margin: -5px 0 0 -5px;
	border: 1px solid rgb(255, 255, 255);
	border-radius: 100%;
	box-shadow: 0px 0px 2px rgba(0, 0, 0, 0.8);
	position: absolute;
}

.colorpicker-body .strip {
	width: 25px;
	height: 150px;
}

.colorpicker-body .hue-strip {
	position: relative;
	margin-left: 8px;
	cursor: grab;
	background: linear-gradient(to bottom, #ff0000 0%, #ffff00 17%, #00ff00 33%, #00ffff 50%, #0000ff 67%, #ff00ff 83%, #ff0000 100%);
}

.colorpicker-body .opacity-strip {
	position: relative;
	margin-left: 8px;
	cursor: grab;
	background: url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAQAAAAECAYAAACp8Z5+AAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsMAAA7DAcdvqGQAAAAZdEVYdFNvZnR3YXJlAHBhaW50Lm5ldCA0LjAuMTZEaa/1AAAAHUlEQVQYV2PYvXu3JAi7uLiAMaYAjAGTQBPYLQkAa/0Zef3qRswAAAAASUVORK5CYII=");
	background-size: 9px 9px;
	image-rendering: pixelated;
}

.colorpicker-body .strip.grabbing {
	cursor: grabbing;
}

.colorpicker-body .slider {
	position: absolute;
	top: 0;
	left: -2px;
	width: calc(100% + 4px);
	height: 4px;
	box-sizing: border-box;
	border: 1px solid rgba(255, 255, 255, 0.71);
	box-shadow: 0px 0px 1px rgba(0, 0, 0, 0.85);
}

.colorpicker-body .strip .overlay {
	height: 150px;
	pointer-events: none;
}
</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

/* marker zone */

.monaco-editor .peekview-widget .head .peekview-title .severity-icon {
	display: inline-block;
	vertical-align: text-top;
	margin-right: 4px;
}

.monaco-editor .marker-widget {
	text-overflow: ellipsis;
	white-space: nowrap;
}

.monaco-editor .marker-widget > .stale {
	opacity: 0.6;
	font-style: italic;
}

.monaco-editor .marker-widget .title {
	display: inline-block;
	padding-right: 5px;
}

.monaco-editor .marker-widget .descriptioncontainer {
	position: absolute;
	white-space: pre;
	user-select: text;
	-webkit-user-select: text;
	-ms-user-select: text;
	padding: 8px 12px 0 20px;
}

.monaco-editor .marker-widget .descriptioncontainer .message {
	display: flex;
	flex-direction: column;
}

.monaco-editor .marker-widget .descriptioncontainer .message .details {
	padding-left: 6px;
}

.monaco-editor .marker-widget .descriptioncontainer .message .source,
.monaco-editor .marker-widget .descriptioncontainer .message span.code {
	opacity: 0.6;
}

.monaco-editor .marker-widget .descriptioncontainer .message a.code-link {
	opacity: 0.6;
	color: inherit;
}

.monaco-editor .marker-widget .descriptioncontainer .message a.code-link:before {
	content: '(';
}

.monaco-editor .marker-widget .descriptioncontainer .message a.code-link:after {
	content: ')';
}

.monaco-editor .marker-widget .descriptioncontainer .message a.code-link > span {
	text-decoration: underline;
	/** Hack to force underline to show **/
	border-bottom: 1px solid transparent;
	text-underline-position: under;
}

.monaco-editor .marker-widget .descriptioncontainer .filename {
	cursor: pointer;
}
</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

.monaco-editor .snippet-placeholder {
	min-width: 2px;
	outline-style: solid;
	outline-width: 1px;
}

.monaco-editor .finish-snippet-placeholder {
	outline-style: solid;
	outline-width: 1px;
}
</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

@font-face {
	font-family: "codicon";
	font-display: block;
	src: url(/singlepage/root/./static/media/codicon.59002d8c..ttf) format("truetype");
}

.codicon[class*='codicon-'] {
	font: normal normal normal 16px/1 codicon;
	display: inline-block;
	text-decoration: none;
	text-rendering: auto;
	text-align: center;
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
	user-select: none;
	-webkit-user-select: none;
	-ms-user-select: none;
}

/* icon rules are dynamically created in codiconStyles */
</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

.codicon-wrench-subaction {
	opacity: 0.5;
}

@keyframes codicon-spin {
	100% {
		transform:rotate(360deg);
	}
}

.codicon-sync.codicon-modifier-spin,
.codicon-loading.codicon-modifier-spin,
.codicon-gear.codicon-modifier-spin,
.codicon-notebook-state-executing.codicon-modifier-spin {
	/* Use steps to throttle FPS to reduce CPU usage */
	animation: codicon-spin 1.5s steps(30) infinite;
}

.codicon-modifier-disabled {
	opacity: 0.4;
}

/* custom speed & easing for loading icon */
.codicon-loading,
.codicon-tree-item-loading::before {
	animation-duration: 1s !important;
	animation-timing-function: cubic-bezier(0.53, 0.21, 0.29, 0.67) !important;
}
</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

/* Suggest widget*/

.monaco-editor .suggest-widget {
	width: 430px;
	z-index: 40;
	display: flex;
	flex-direction: column;
}

.monaco-editor .suggest-widget.message {
	flex-direction: row;
	align-items: center;
}

.monaco-editor .suggest-widget,
.monaco-editor .suggest-details {
	flex: 0 1 auto;
	width: 100%;
	border-style: solid;
	border-width: 1px;
}

.monaco-editor.hc-black .suggest-widget,
.monaco-editor.hc-black .suggest-details {
	border-width: 2px;
}

/* Styles for status bar part */


.monaco-editor .suggest-widget .suggest-status-bar {
	box-sizing: border-box;
	display: none;
	flex-flow: row nowrap;
	justify-content: space-between;
	width: 100%;
	font-size: 80%;
	padding: 0 4px 0 4px;
	border-top: 1px solid transparent;
	overflow: hidden;
}

.monaco-editor .suggest-widget.with-status-bar .suggest-status-bar {
	display: flex;
}

.monaco-editor .suggest-widget .suggest-status-bar .left {
	padding-right: 8px;
}

.monaco-editor .suggest-widget.with-status-bar .suggest-status-bar .action-label {
	opacity: 0.5;
	color: inherit;
}

.monaco-editor .suggest-widget.with-status-bar .suggest-status-bar .action-item:not(:last-of-type) .action-label {
	margin-right: 0;
}

.monaco-editor .suggest-widget.with-status-bar .suggest-status-bar .action-item:not(:last-of-type) .action-label::after {
	content: ', ';
	margin-right: 0.3em;
}

.monaco-editor .suggest-widget.with-status-bar .monaco-list .monaco-list-row>.contents>.main>.right>.readMore,
.monaco-editor .suggest-widget.with-status-bar .monaco-list .monaco-list-row.focused.string-label>.contents>.main>.right>.readMore {
	display: none;
}

.monaco-editor .suggest-widget.with-status-bar:not(.docs-side) .monaco-list .monaco-list-row:hover>.contents>.main>.right.can-expand-details>.details-label {
	width: 100%;
}

/* Styles for Message element for when widget is loading or is empty */

.monaco-editor .suggest-widget>.message {
	padding-left: 22px;
}

/** Styles for the list element **/

.monaco-editor .suggest-widget>.tree {
	height: 100%;
	width: 100%;
}

.monaco-editor .suggest-widget .monaco-list {
	user-select: none;
	-webkit-user-select: none;
	-ms-user-select: none;
}

/** Styles for each row in the list element **/

.monaco-editor .suggest-widget .monaco-list .monaco-list-row {
	display: flex;
	-mox-box-sizing: border-box;
	box-sizing: border-box;
	padding-right: 10px;
	background-repeat: no-repeat;
	background-position: 2px 2px;
	white-space: nowrap;
	cursor: pointer;
	touch-action: none;
}

.monaco-editor .suggest-widget .monaco-list .monaco-list-row>.contents {
	flex: 1;
	height: 100%;
	overflow: hidden;
	padding-left: 2px;
}

.monaco-editor .suggest-widget .monaco-list .monaco-list-row>.contents>.main {
	display: flex;
	overflow: hidden;
	text-overflow: ellipsis;
	white-space: pre;
	justify-content: space-between;
}

.monaco-editor .suggest-widget .monaco-list .monaco-list-row>.contents>.main>.left, .monaco-editor .suggest-widget .monaco-list .monaco-list-row>.contents>.main>.right {
	display: flex;
}

.monaco-editor .suggest-widget:not(.frozen) .monaco-highlighted-label .highlight {
	font-weight: bold;
}

/** ReadMore Icon styles **/

.monaco-editor .suggest-details>.monaco-scrollable-element>.body>.header>.codicon-close,
.monaco-editor .suggest-widget .monaco-list .monaco-list-row>.contents>.main>.right>.readMore::before {
	color: inherit;
	opacity: 1;
	font-size: 14px;
	cursor: pointer;
}

.monaco-editor .suggest-details>.monaco-scrollable-element>.body>.header>.codicon-close {
	position: absolute;
	top: 6px;
	right: 2px;
}

.monaco-editor .suggest-details>.monaco-scrollable-element>.body>.header>.codicon-close:hover,
.monaco-editor .suggest-widget .monaco-list .monaco-list-row>.contents>.main>.right>.readMore:hover {
	opacity: 1;
}

/** signature, qualifier, type/details opacity **/

.monaco-editor .suggest-widget .monaco-list .monaco-list-row>.contents>.main>.right>.details-label {
	opacity: 0.7;
}

.monaco-editor .suggest-widget .monaco-list .monaco-list-row>.contents>.main>.left>.signature-label {
	overflow: hidden;
	text-overflow: ellipsis;
	opacity: 0.6;
}

.monaco-editor .suggest-widget .monaco-list .monaco-list-row>.contents>.main>.left>.qualifier-label {
	margin-left: 12px;
	opacity: 0.4;
	font-size: 85%;
	line-height: initial;
	text-overflow: ellipsis;
	overflow: hidden;
	align-self: center;
}

/** Type Info and icon next to the label in the focused completion item **/

.monaco-editor .suggest-widget .monaco-list .monaco-list-row>.contents>.main>.right>.details-label {
	font-size: 85%;
	margin-left: 1.1em;
	overflow: hidden;
	text-overflow: ellipsis;
	white-space: nowrap;
}

.monaco-editor .suggest-widget .monaco-list .monaco-list-row>.contents>.main>.right>.details-label>.monaco-tokenized-source {
	display: inline;
}

/** Details: if using CompletionItem#details, show on focus **/

.monaco-editor .suggest-widget .monaco-list .monaco-list-row>.contents>.main>.right>.details-label {
	display: none;
}

.monaco-editor .suggest-widget:not(.shows-details) .monaco-list .monaco-list-row.focused>.contents>.main>.right>.details-label {
	display: inline;
}

/** Details: if using CompletionItemLabel#details, always show **/

.monaco-editor .suggest-widget .monaco-list .monaco-list-row:not(.string-label)>.contents>.main>.right>.details-label,
.monaco-editor .suggest-widget.docs-side .monaco-list .monaco-list-row.focused:not(.string-label)>.contents>.main>.right>.details-label {
	display: inline;
}

/** Ellipsis on hover **/

.monaco-editor .suggest-widget:not(.docs-side) .monaco-list .monaco-list-row:hover>.contents>.main>.right.can-expand-details>.details-label {
	width: calc(100% - 26px);
}

.monaco-editor .suggest-widget .monaco-list .monaco-list-row>.contents>.main>.left {
	flex-shrink: 1;
	flex-grow: 1;
	overflow: hidden;
}

.monaco-editor .suggest-widget .monaco-list .monaco-list-row>.contents>.main>.left>.monaco-icon-label {
	flex-shrink: 0;
}

.monaco-editor .suggest-widget .monaco-list .monaco-list-row:not(.string-label)>.contents>.main>.left>.monaco-icon-label {
	max-width: 100%;
}

.monaco-editor .suggest-widget .monaco-list .monaco-list-row.string-label>.contents>.main>.left>.monaco-icon-label {
	flex-shrink: 1;
}

.monaco-editor .suggest-widget .monaco-list .monaco-list-row>.contents>.main>.right {
	overflow: hidden;
	flex-shrink: 4;
	max-width: 70%;
}

.monaco-editor .suggest-widget .monaco-list .monaco-list-row>.contents>.main>.right>.readMore {
	display: inline-block;
	position: absolute;
	right: 10px;
	width: 18px;
	height: 18px;
	visibility: hidden;
}

/** Do NOT display ReadMore when docs is side/below **/

.monaco-editor .suggest-widget.docs-side .monaco-list .monaco-list-row>.contents>.main>.right>.readMore, .monaco-editor .suggest-widget.docs-below .monaco-list .monaco-list-row>.contents>.main>.right>.readMore {
	display: none !important;
}

/** Do NOT display ReadMore when using plain CompletionItemLabel (details/documentation might not be resolved) **/

.monaco-editor .suggest-widget .monaco-list .monaco-list-row.string-label>.contents>.main>.right>.readMore {
	display: none;
}

/** Focused item can show ReadMore, but can't when docs is side/below **/

.monaco-editor .suggest-widget .monaco-list .monaco-list-row.focused.string-label>.contents>.main>.right>.readMore {
	display: inline-block;
}

.monaco-editor .suggest-widget.docs-side .monaco-list .monaco-list-row>.contents>.main>.right>.readMore,
.monaco-editor .suggest-widget.docs-below .monaco-list .monaco-list-row>.contents>.main>.right>.readMore {
	display: none;
}

.monaco-editor .suggest-widget .monaco-list .monaco-list-row:hover>.contents>.main>.right>.readMore {
	visibility: visible;
}

/** Styles for each row in the list **/

.monaco-editor .suggest-widget .monaco-list .monaco-list-row .monaco-icon-label.deprecated {
	opacity: 0.66;
	text-decoration: unset;
}

.monaco-editor .suggest-widget .monaco-list .monaco-list-row .monaco-icon-label.deprecated>.monaco-icon-label-container>.monaco-icon-name-container {
	text-decoration: line-through;
}

.monaco-editor .suggest-widget .monaco-list .monaco-list-row .monaco-icon-label::before {
	height: 100%;
}

.monaco-editor .suggest-widget .monaco-list .monaco-list-row .icon {
	display: block;
	height: 16px;
	width: 16px;
	margin-left: 2px;
	background-repeat: no-repeat;
	background-size: 80%;
	background-position: center;
}

.monaco-editor .suggest-widget .monaco-list .monaco-list-row .icon.hide {
	display: none;
}

.monaco-editor .suggest-widget .monaco-list .monaco-list-row .suggest-icon {
	display: flex;
	align-items: center;
	margin-right: 4px;
}

.monaco-editor .suggest-widget.no-icons .monaco-list .monaco-list-row .icon, .monaco-editor .suggest-widget.no-icons .monaco-list .monaco-list-row .suggest-icon::before {
	display: none;
}

.monaco-editor .suggest-widget .monaco-list .monaco-list-row .icon.customcolor .colorspan {
	margin: 0 0 0 0.3em;
	border: 0.1em solid #000;
	width: 0.7em;
	height: 0.7em;
	display: inline-block;
}

/** Styles for the docs of the completion item in focus **/

.monaco-editor .suggest-details-container {
	z-index: 41;
}

.monaco-editor .suggest-details {
	display: flex;
	flex-direction: column;
	cursor: default;
}

.monaco-editor .suggest-details.no-docs {
	display: none;
}

.monaco-editor .suggest-details>.monaco-scrollable-element {
	flex: 1;
}

.monaco-editor .suggest-details>.monaco-scrollable-element>.body {
	box-sizing: border-box;
	height: 100%;
	width: 100%;
}

.monaco-editor .suggest-details>.monaco-scrollable-element>.body>.header>.type {
	flex: 2;
	overflow: hidden;
	text-overflow: ellipsis;
	opacity: 0.7;
	white-space: pre;
	margin: 0 24px 0 0;
	padding: 4px 0 12px 5px;
}

.monaco-editor .suggest-details>.monaco-scrollable-element>.body>.header>.type.auto-wrap {
	white-space: normal;
	word-break: break-all;
}


.monaco-editor .suggest-details>.monaco-scrollable-element>.body>.docs {
	margin: 0;
	padding: 4px 5px;
	white-space: pre-wrap;
}

.monaco-editor .suggest-details.no-type>.monaco-scrollable-element>.body>.docs {
	margin-right: 24px;
}

.monaco-editor .suggest-details>.monaco-scrollable-element>.body>.docs.markdown-docs {
	padding: 0;
	white-space: initial;
	min-height: calc(1rem + 8px);
}

.monaco-editor .suggest-details>.monaco-scrollable-element>.body>.docs.markdown-docs>div,
.monaco-editor .suggest-details>.monaco-scrollable-element>.body>.docs.markdown-docs>span:not(:empty) {
	padding: 4px 5px;
}

.monaco-editor .suggest-details>.monaco-scrollable-element>.body>.docs.markdown-docs>div>p:first-child {
	margin-top: 0;
}

.monaco-editor .suggest-details>.monaco-scrollable-element>.body>.docs.markdown-docs>div>p:last-child {
	margin-bottom: 0;
}

.monaco-editor .suggest-details>.monaco-scrollable-element>.body>.docs.markdown-docs .monaco-tokenized-source {
	white-space: pre;
}

.monaco-editor .suggest-details>.monaco-scrollable-element>.body>.docs .code {
	white-space: pre-wrap;
	word-wrap: break-word;
}

.monaco-editor .suggest-details>.monaco-scrollable-element>.body>.docs.markdown-docs .codicon {
	vertical-align: sub;
}

.monaco-editor .suggest-details>.monaco-scrollable-element>.body>p:empty {
	display: none;
}

.monaco-editor .suggest-details code {
	border-radius: 3px;
	padding: 0 0.4em;
}

.monaco-editor .suggest-details ul {
	padding-left: 20px;
}

.monaco-editor .suggest-details ol {
	padding-left: 20px;
}

.monaco-editor .suggest-details p code {
	font-family: var(--monaco-monospace-font);
}
</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

.monaco-editor .suggest-preview-additional-widget {
	white-space: nowrap;
}

.monaco-editor .suggest-preview-additional-widget .content-spacer {
	color: transparent;
	white-space: pre;
}

.monaco-editor .suggest-preview-additional-widget .button {
	display: inline-block;
	cursor: pointer;
	text-decoration: underline;
	text-underline-position: under;
}

.monaco-editor .ghost-text-hidden {
	opacity: 0;
	font-size: 0;
}

.monaco-editor .ghost-text-decoration {
	font-style: italic;
}

.monaco-editor .suggest-preview-text {
	font-style: italic;
}
</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

.monaco-editor.vs .dnd-target {
	border-right: 2px dotted black;
	color: white; /* opposite of black */
}
.monaco-editor.vs-dark .dnd-target {
	border-right: 2px dotted #AEAFAD;
	color: #51504f; /* opposite of #AEAFAD */
}
.monaco-editor.hc-black .dnd-target {
	border-right: 2px dotted #fff;
	color: #000; /* opposite of #fff */
}

.monaco-editor.mouse-default .view-lines,
.monaco-editor.vs-dark.mac.mouse-default .view-lines,
.monaco-editor.hc-black.mac.mouse-default .view-lines {
	cursor: default;
}
.monaco-editor.mouse-copy .view-lines,
.monaco-editor.vs-dark.mac.mouse-copy .view-lines,
.monaco-editor.hc-black.mac.mouse-copy .view-lines {
	cursor: copy;
}</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

.monaco-custom-checkbox {
	margin-left: 2px;
	float: left;
	cursor: pointer;
	overflow: hidden;
	opacity: 0.7;
	width: 20px;
	height: 20px;
	border: 1px solid transparent;
	padding: 1px;
	box-sizing:	border-box;
	user-select: none;
	-webkit-user-select: none;
	-ms-user-select: none;
}

.monaco-custom-checkbox:hover,
.monaco-custom-checkbox.checked {
	opacity: 1;
}

.hc-black .monaco-custom-checkbox {
	background: none;
}

.hc-black .monaco-custom-checkbox:hover {
	background: none;
}

.monaco-custom-checkbox.monaco-simple-checkbox {
	height: 18px;
	width: 18px;
	border: 1px solid transparent;
	border-radius: 3px;
	margin-right: 9px;
	margin-left: 0px;
	padding: 0px;
	opacity: 1;
	background-size: 16px !important;
}

/* hide check when unchecked */
.monaco-custom-checkbox.monaco-simple-checkbox:not(.checked)::before {
	visibility: hidden;
}
</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

/* Find widget */
.monaco-editor .find-widget {
	position: absolute;
	z-index: 35;
	height: 33px;
	overflow: hidden;
	line-height: 19px;
	transition: transform 200ms linear;
	padding: 0 4px;
	box-sizing: border-box;
	transform: translateY(calc(-100% - 10px)); /* shadow (10px) */
}

.monaco-editor .find-widget textarea {
	margin: 0px;
}

.monaco-editor .find-widget.hiddenEditor {
	display: none;
}

/* Find widget when replace is toggled on */
.monaco-editor .find-widget.replaceToggled > .replace-part {
	display: flex;
}

.monaco-editor .find-widget.visible  {
	transform: translateY(0);
}

.monaco-editor .find-widget .monaco-inputbox.synthetic-focus {
	outline: 1px solid -webkit-focus-ring-color;
	outline-offset: -1px;
}

.monaco-editor .find-widget .monaco-inputbox .input {
	background-color: transparent;
	min-height: 0;
}

.monaco-editor .find-widget .monaco-findInput .input {
	font-size: 13px;
}

.monaco-editor .find-widget > .find-part,
.monaco-editor .find-widget > .replace-part {
	margin: 4px 0 0 17px;
	font-size: 12px;
	display: flex;
}

.monaco-editor .find-widget > .find-part .monaco-inputbox,
.monaco-editor .find-widget > .replace-part .monaco-inputbox {
	min-height: 25px;
}


.monaco-editor .find-widget > .replace-part .monaco-inputbox > .ibwrapper > .mirror {
	padding-right: 22px;
}

.monaco-editor .find-widget > .find-part .monaco-inputbox > .ibwrapper > .input,
.monaco-editor .find-widget > .find-part .monaco-inputbox > .ibwrapper > .mirror,
.monaco-editor .find-widget > .replace-part .monaco-inputbox > .ibwrapper > .input,
.monaco-editor .find-widget > .replace-part .monaco-inputbox > .ibwrapper > .mirror {
	padding-top: 2px;
	padding-bottom: 2px;
}

.monaco-editor .find-widget > .find-part .find-actions {
	height: 25px;
	display: flex;
	align-items: center;
}

.monaco-editor .find-widget > .replace-part .replace-actions {
	height: 25px;
	display: flex;
	align-items: center;
}

.monaco-editor .find-widget .monaco-findInput {
	vertical-align: middle;
	display: flex;
	flex:1;
}

.monaco-editor .find-widget .monaco-findInput .monaco-scrollable-element {
	/* Make sure textarea inherits the width correctly */
	width: 100%;
}

.monaco-editor .find-widget .monaco-findInput .monaco-scrollable-element .scrollbar.vertical {
	/* Hide vertical scrollbar */
	opacity: 0;
}

.monaco-editor .find-widget .matchesCount {
	display: flex;
	flex: initial;
	margin: 0 0 0 3px;
	padding: 2px 0 0 2px;
	height: 25px;
	vertical-align: middle;
	box-sizing: border-box;
	text-align: center;
	line-height: 23px;
}

.monaco-editor .find-widget .button {
	width: 16px;
	height: 16px;
	padding: 3px;
	border-radius: 5px;
	display: flex;
	flex: initial;
	margin-left: 3px;
	background-position: center center;
	background-repeat: no-repeat;
	cursor: pointer;
	display: flex;
	align-items: center;
	justify-content: center;
}

/* find in selection button */
.monaco-editor .find-widget .codicon-find-selection {
	width: 22px;
	height: 22px;
	padding: 3px;
	border-radius: 5px;
}

.monaco-editor .find-widget .button.left {
	margin-left: 0;
	margin-right: 3px;
}

.monaco-editor .find-widget .button.wide {
	width: auto;
	padding: 1px 6px;
	top: -1px;
}

.monaco-editor .find-widget .button.toggle {
	position: absolute;
	top: 0;
	left: 3px;
	width: 18px;
	height: 100%;
	border-radius: 0;
	box-sizing: border-box;
}

.monaco-editor .find-widget .button.toggle.disabled {
	display: none;
}

.monaco-editor .find-widget .disabled {
	opacity: 0.3;
	cursor: default;
}

.monaco-editor .find-widget > .replace-part {
	display: none;
}

.monaco-editor .find-widget > .replace-part > .monaco-findInput {
	position: relative;
	display: flex;
	vertical-align: middle;
	flex: auto;
	flex-grow: 0;
	flex-shrink: 0;
}

.monaco-editor .find-widget > .replace-part > .monaco-findInput > .controls {
	position: absolute;
	top: 3px;
	right: 2px;
}

/* REDUCED */
.monaco-editor .find-widget.reduced-find-widget .matchesCount {
	display:none;
}

/* NARROW (SMALLER THAN REDUCED) */
.monaco-editor .find-widget.narrow-find-widget {
	max-width: 257px !important;
}

/* COLLAPSED (SMALLER THAN NARROW) */
.monaco-editor .find-widget.collapsed-find-widget {
	max-width: 170px !important;
}

.monaco-editor .find-widget.collapsed-find-widget .button.previous,
.monaco-editor .find-widget.collapsed-find-widget .button.next,
.monaco-editor .find-widget.collapsed-find-widget .button.replace,
.monaco-editor .find-widget.collapsed-find-widget .button.replace-all,
.monaco-editor .find-widget.collapsed-find-widget > .find-part .monaco-findInput .controls {
	display:none;
}

.monaco-editor .findMatch {
	animation-duration: 0;
	animation-name: inherit !important;
}

.monaco-editor .find-widget .monaco-sash {
	left: 0 !important;
}

.monaco-editor.hc-black .find-widget .button:before {
	position: relative;
	top: 1px;
	left: 2px;
}
</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

.monaco-inputbox {
	position: relative;
	display: block;
	padding: 0;
	box-sizing:	border-box;

	/* Customizable */
	font-size: inherit;
}

.monaco-inputbox.idle {
	border: 1px solid transparent;
}

.monaco-inputbox > .ibwrapper > .input,
.monaco-inputbox > .ibwrapper > .mirror {

	/* Customizable */
	padding: 4px;
}

.monaco-inputbox > .ibwrapper {
	position: relative;
	width: 100%;
	height: 100%;
}

.monaco-inputbox > .ibwrapper > .input {
	display: inline-block;
	box-sizing:	border-box;
	width: 100%;
	height: 100%;
	line-height: inherit;
	border: none;
	font-family: inherit;
	font-size: inherit;
	resize: none;
	color: inherit;
}

.monaco-inputbox > .ibwrapper > input {
	text-overflow: ellipsis;
}

.monaco-inputbox > .ibwrapper > textarea.input {
	display: block;
	-ms-overflow-style: none; /* IE 10+: hide scrollbars */
	scrollbar-width: none; /* Firefox: hide scrollbars */
	outline: none;
}

.monaco-inputbox > .ibwrapper > textarea.input::-webkit-scrollbar {
	display: none; /* Chrome + Safari: hide scrollbar */
}

.monaco-inputbox > .ibwrapper > textarea.input.empty {
	white-space: nowrap;
}

.monaco-inputbox > .ibwrapper > .mirror {
	position: absolute;
	display: inline-block;
	width: 100%;
	top: 0;
	left: 0;
	box-sizing: border-box;
	white-space: pre-wrap;
	visibility: hidden;
	word-wrap: break-word;
}

/* Context view */

.monaco-inputbox-container {
	text-align: right;
}

.monaco-inputbox-container .monaco-inputbox-message {
	display: inline-block;
	overflow: hidden;
	text-align: left;
	width: 100%;
	box-sizing:	border-box;
	padding: 0.4em;
	font-size: 12px;
	line-height: 17px;
	margin-top: -1px;
	word-wrap: break-word;
}

/* Action bar support */
.monaco-inputbox .monaco-action-bar {
	position: absolute;
	right: 2px;
	top: 4px;
}

.monaco-inputbox .monaco-action-bar .action-item {
	margin-left: 2px;
}

.monaco-inputbox .monaco-action-bar .action-item .codicon {
	background-repeat: no-repeat;
	width: 16px;
	height: 16px;
}
</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/
/* ---------- Find input ---------- */

.monaco-findInput {
	position: relative;
}

.monaco-findInput .monaco-inputbox {
	font-size: 13px;
	width: 100%;
}

.monaco-findInput > .controls {
	position: absolute;
	top: 3px;
	right: 2px;
}

.vs .monaco-findInput.disabled {
	background-color: #E1E1E1;
}

/* Theming */
.vs-dark .monaco-findInput.disabled {
	background-color: #333;
}

/* Highlighting */
.monaco-findInput.highlight-0 .controls {
	animation: monaco-findInput-highlight-0 100ms linear 0s;
}
.monaco-findInput.highlight-1 .controls {
	animation: monaco-findInput-highlight-1 100ms linear 0s;
}
.hc-black .monaco-findInput.highlight-0 .controls,
.vs-dark  .monaco-findInput.highlight-0 .controls {
	animation: monaco-findInput-highlight-dark-0 100ms linear 0s;
}
.hc-black .monaco-findInput.highlight-1 .controls,
.vs-dark  .monaco-findInput.highlight-1 .controls {
	animation: monaco-findInput-highlight-dark-1 100ms linear 0s;
}

@keyframes monaco-findInput-highlight-0 {
	0% { background: rgba(253, 255, 0, 0.8); }
	100% { background: transparent; }
}
@keyframes monaco-findInput-highlight-1 {
	0% { background: rgba(253, 255, 0, 0.8); }
	/* Made intentionally different such that the CSS minifier does not collapse the two animations into a single one*/
	99% { background: transparent; }
}

@keyframes monaco-findInput-highlight-dark-0 {
	0% { background: rgba(255, 255, 255, 0.44); }
	100% { background: transparent; }
}
@keyframes monaco-findInput-highlight-dark-1 {
	0% { background: rgba(255, 255, 255, 0.44); }
	/* Made intentionally different such that the CSS minifier does not collapse the two animations into a single one*/
	99% { background: transparent; }
}</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

.monaco-editor .margin-view-overlays .codicon-folding-expanded,
.monaco-editor .margin-view-overlays .codicon-folding-collapsed {
	cursor: pointer;
	opacity: 0;
	transition: opacity 0.5s;
	display: flex;
	align-items: center;
	justify-content: center;
	font-size: 140%;
	margin-left: 2px;
}

.monaco-editor .margin-view-overlays:hover .codicon,
.monaco-editor .margin-view-overlays .codicon.codicon-folding-collapsed,
.monaco-editor .margin-view-overlays .codicon.alwaysShowFoldIcons {
	opacity: 1;
}

.monaco-editor .inline-folded:after {
	color: grey;
	margin: 0.1em 0.2em 0 0.2em;
	content: "⋯";
	display: inline;
	line-height: 1em;
	cursor: pointer;
}
</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

.monaco-editor .iPadShowKeyboard {
	width: 58px;
	min-width: 0;
	height: 36px;
	min-height: 0;
	margin: 0;
	padding: 0;
	position: absolute;
	resize: none;
	overflow: hidden;
	background: url("data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iNTMiIGhlaWdodD0iMzYiIHZpZXdCb3g9IjAgMCA1MyAzNiIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPGcgY2xpcC1wYXRoPSJ1cmwoI2NsaXAwKSI+CjxwYXRoIGZpbGwtcnVsZT0iZXZlbm9kZCIgY2xpcC1ydWxlPSJldmVub2RkIiBkPSJNNDguMDM2NCA0LjAxMDQySDQuMDA3NzlMNC4wMDc3OSAzMi4wMjg2SDQ4LjAzNjRWNC4wMTA0MlpNNC4wMDc3OSAwLjAwNzgxMjVDMS43OTcyMSAwLjAwNzgxMjUgMC4wMDUxODc5OSAxLjc5OTg0IDAuMDA1MTg3OTkgNC4wMTA0MlYzMi4wMjg2QzAuMDA1MTg3OTkgMzQuMjM5MiAxLjc5NzIxIDM2LjAzMTIgNC4wMDc3OSAzNi4wMzEySDQ4LjAzNjRDNTAuMjQ3IDM2LjAzMTIgNTIuMDM5IDM0LjIzOTIgNTIuMDM5IDMyLjAyODZWNC4wMTA0MkM1Mi4wMzkgMS43OTk4NCA1MC4yNDcgMC4wMDc4MTI1IDQ4LjAzNjQgMC4wMDc4MTI1SDQuMDA3NzlaTTguMDEwNDIgOC4wMTMwMkgxMi4wMTNWMTIuMDE1Nkg4LjAxMDQyVjguMDEzMDJaTTIwLjAxODIgOC4wMTMwMkgxNi4wMTU2VjEyLjAxNTZIMjAuMDE4MlY4LjAxMzAyWk0yNC4wMjA4IDguMDEzMDJIMjguMDIzNFYxMi4wMTU2SDI0LjAyMDhWOC4wMTMwMlpNMzYuMDI4NiA4LjAxMzAySDMyLjAyNlYxMi4wMTU2SDM2LjAyODZWOC4wMTMwMlpNNDAuMDMxMiA4LjAxMzAySDQ0LjAzMzlWMTIuMDE1Nkg0MC4wMzEyVjguMDEzMDJaTTE2LjAxNTYgMTYuMDE4Mkg4LjAxMDQyVjIwLjAyMDhIMTYuMDE1NlYxNi4wMTgyWk0yMC4wMTgyIDE2LjAxODJIMjQuMDIwOFYyMC4wMjA4SDIwLjAxODJWMTYuMDE4MlpNMzIuMDI2IDE2LjAxODJIMjguMDIzNFYyMC4wMjA4SDMyLjAyNlYxNi4wMTgyWk00NC4wMzM5IDE2LjAxODJWMjAuMDIwOEgzNi4wMjg2VjE2LjAxODJINDQuMDMzOVpNMTIuMDEzIDI0LjAyMzRIOC4wMTA0MlYyOC4wMjZIMTIuMDEzVjI0LjAyMzRaTTE2LjAxNTYgMjQuMDIzNEgzNi4wMjg2VjI4LjAyNkgxNi4wMTU2VjI0LjAyMzRaTTQ0LjAzMzkgMjQuMDIzNEg0MC4wMzEyVjI4LjAyNkg0NC4wMzM5VjI0LjAyMzRaIiBmaWxsPSIjNDI0MjQyIi8+CjwvZz4KPGRlZnM+CjxjbGlwUGF0aCBpZD0iY2xpcDAiPgo8cmVjdCB3aWR0aD0iNTMiIGhlaWdodD0iMzYiIGZpbGw9IndoaXRlIi8+CjwvY2xpcFBhdGg+CjwvZGVmcz4KPC9zdmc+Cg==") center center no-repeat;
	border: 4px solid #F6F6F6;
	border-radius: 4px;
}

.monaco-editor.vs-dark .iPadShowKeyboard {
	background: url("data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iNTMiIGhlaWdodD0iMzYiIHZpZXdCb3g9IjAgMCA1MyAzNiIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPGcgY2xpcC1wYXRoPSJ1cmwoI2NsaXAwKSI+CjxwYXRoIGZpbGwtcnVsZT0iZXZlbm9kZCIgY2xpcC1ydWxlPSJldmVub2RkIiBkPSJNNDguMDM2NCA0LjAxMDQySDQuMDA3NzlMNC4wMDc3OSAzMi4wMjg2SDQ4LjAzNjRWNC4wMTA0MlpNNC4wMDc3OSAwLjAwNzgxMjVDMS43OTcyMSAwLjAwNzgxMjUgMC4wMDUxODc5OSAxLjc5OTg0IDAuMDA1MTg3OTkgNC4wMTA0MlYzMi4wMjg2QzAuMDA1MTg3OTkgMzQuMjM5MiAxLjc5NzIxIDM2LjAzMTIgNC4wMDc3OSAzNi4wMzEySDQ4LjAzNjRDNTAuMjQ3IDM2LjAzMTIgNTIuMDM5IDM0LjIzOTIgNTIuMDM5IDMyLjAyODZWNC4wMTA0MkM1Mi4wMzkgMS43OTk4NCA1MC4yNDcgMC4wMDc4MTI1IDQ4LjAzNjQgMC4wMDc4MTI1SDQuMDA3NzlaTTguMDEwNDIgOC4wMTMwMkgxMi4wMTNWMTIuMDE1Nkg4LjAxMDQyVjguMDEzMDJaTTIwLjAxODIgOC4wMTMwMkgxNi4wMTU2VjEyLjAxNTZIMjAuMDE4MlY4LjAxMzAyWk0yNC4wMjA4IDguMDEzMDJIMjguMDIzNFYxMi4wMTU2SDI0LjAyMDhWOC4wMTMwMlpNMzYuMDI4NiA4LjAxMzAySDMyLjAyNlYxMi4wMTU2SDM2LjAyODZWOC4wMTMwMlpNNDAuMDMxMiA4LjAxMzAySDQ0LjAzMzlWMTIuMDE1Nkg0MC4wMzEyVjguMDEzMDJaTTE2LjAxNTYgMTYuMDE4Mkg4LjAxMDQyVjIwLjAyMDhIMTYuMDE1NlYxNi4wMTgyWk0yMC4wMTgyIDE2LjAxODJIMjQuMDIwOFYyMC4wMjA4SDIwLjAxODJWMTYuMDE4MlpNMzIuMDI2IDE2LjAxODJIMjguMDIzNFYyMC4wMjA4SDMyLjAyNlYxNi4wMTgyWk00NC4wMzM5IDE2LjAxODJWMjAuMDIwOEgzNi4wMjg2VjE2LjAxODJINDQuMDMzOVpNMTIuMDEzIDI0LjAyMzRIOC4wMTA0MlYyOC4wMjZIMTIuMDEzVjI0LjAyMzRaTTE2LjAxNTYgMjQuMDIzNEgzNi4wMjg2VjI4LjAyNkgxNi4wMTU2VjI0LjAyMzRaTTQ0LjAzMzkgMjQuMDIzNEg0MC4wMzEyVjI4LjAyNkg0NC4wMzM5VjI0LjAyMzRaIiBmaWxsPSIjQzVDNUM1Ii8+CjwvZz4KPGRlZnM+CjxjbGlwUGF0aCBpZD0iY2xpcDAiPgo8cmVjdCB3aWR0aD0iNTMiIGhlaWdodD0iMzYiIGZpbGw9IndoaXRlIi8+CjwvY2xpcFBhdGg+CjwvZGVmcz4KPC9zdmc+Cg==") center center no-repeat;
	border: 4px solid #252526;
}</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

.monaco-editor .tokens-inspect-widget {
	z-index: 50;
	user-select: text;
	-webkit-user-select: text;
	-ms-user-select: text;
	padding: 10px;
}

.tokens-inspect-separator {
	height: 1px;
	border: 0;
}

.monaco-editor .tokens-inspect-widget .tm-token {
	font-family: var(--monaco-monospace-font);
}

.monaco-editor .tokens-inspect-widget .tm-token-length {
	font-weight: normal;
	font-size: 60%;
	float: right;
}

.monaco-editor .tokens-inspect-widget .tm-metadata-table {
	width: 100%;
}

.monaco-editor .tokens-inspect-widget .tm-metadata-value {
	font-family: var(--monaco-monospace-font);
	text-align: right;
}

.monaco-editor .tokens-inspect-widget .tm-token-type {
	font-family: var(--monaco-monospace-font);
}
</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/
.monaco-editor .detected-link,
.monaco-editor .detected-link-active {
	text-decoration: underline;
	text-underline-position: under;
}

.monaco-editor .detected-link-active {
	cursor: pointer;
}
</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

.monaco-editor .parameter-hints-widget {
	z-index: 10;
	display: flex;
	flex-direction: column;
	line-height: 1.5em;
}

.monaco-editor .parameter-hints-widget > .phwrapper {
	max-width: 440px;
	display: flex;
	flex-direction: row;
}

.monaco-editor .parameter-hints-widget.multiple {
	min-height: 3.3em;
	padding: 0;
}

.monaco-editor .parameter-hints-widget.visible {
	transition: left .05s ease-in-out;
}

.monaco-editor .parameter-hints-widget p,
.monaco-editor .parameter-hints-widget ul {
	margin: 8px 0;
}

.monaco-editor .parameter-hints-widget .monaco-scrollable-element,
.monaco-editor .parameter-hints-widget .body {
	display: flex;
	flex: 1;
	flex-direction: column;
	min-height: 100%;
}

.monaco-editor .parameter-hints-widget .signature {
	padding: 4px 5px;
}

.monaco-editor .parameter-hints-widget .docs {
	padding: 0 10px 0 5px;
	white-space: pre-wrap;
}

.monaco-editor .parameter-hints-widget .docs.empty {
	display: none;
}

.monaco-editor .parameter-hints-widget .docs .markdown-docs {
	white-space: initial;
}

.monaco-editor .parameter-hints-widget .docs .markdown-docs code {
	font-family: var(--monaco-monospace-font);
}

.monaco-editor .parameter-hints-widget .docs .code {
	white-space: pre-wrap;
}

.monaco-editor .parameter-hints-widget .docs code {
	border-radius: 3px;
	padding: 0 0.4em;
}

.monaco-editor .parameter-hints-widget .controls {
	display: none;
	flex-direction: column;
	align-items: center;
	min-width: 22px;
	justify-content: flex-end;
}

.monaco-editor .parameter-hints-widget.multiple .controls {
	display: flex;
	padding: 0 2px;
}

.monaco-editor .parameter-hints-widget.multiple .button {
	width: 16px;
	height: 16px;
	background-repeat: no-repeat;
	cursor: pointer;
}

.monaco-editor .parameter-hints-widget .button.previous {
	bottom: 24px;
}

.monaco-editor .parameter-hints-widget .overloads {
	text-align: center;
	height: 12px;
	line-height: 12px;
	opacity: 0.5;
	font-family: var(--monaco-monospace-font);
}

.monaco-editor .parameter-hints-widget .signature .parameter.active {
	font-weight: bold;
}

.monaco-editor .parameter-hints-widget .documentation-parameter > .parameter {
	font-weight: bold;
	margin-right: 0.5em;
}
</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

.monaco-editor .rename-box {
	z-index: 100;
	color: inherit;
}

.monaco-editor .rename-box.preview {
	padding: 3px 3px 0 3px;
}

.monaco-editor .rename-box .rename-input {
	padding: 3px;
	width: calc(100% - 6px);
}

.monaco-editor .rename-box .rename-label {
	display: none;
	opacity: .8;
}

.monaco-editor .rename-box.preview .rename-label {
	display: inherit;
}
</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/


/* Default standalone editor fonts */
.monaco-editor {
	font-family: -apple-system, BlinkMacSystemFont, "Segoe WPC", "Segoe UI", "HelveticaNeue-Light", system-ui, "Ubuntu", "Droid Sans", sans-serif;
	--monaco-monospace-font: "SF Mono", Monaco, Menlo, Consolas, "Ubuntu Mono", "Liberation Mono", "DejaVu Sans Mono", "Courier New", monospace;
}

.monaco-menu .monaco-action-bar.vertical .action-item .action-menu-item:focus .action-label {
	stroke-width: 1.2px;
}

.monaco-editor.vs-dark .monaco-menu .monaco-action-bar.vertical .action-menu-item:focus .action-label,
.monaco-editor.hc-black .monaco-menu .monaco-action-bar.vertical .action-menu-item:focus .action-label {
	stroke-width: 1.2px;
}

.monaco-hover p {
	margin: 0;
}

/* See https://github.com/microsoft/monaco-editor/issues/2168#issuecomment-780078600 */
.monaco-aria-container {
	position: absolute !important;
	top: 0; /* avoid being placed underneath a sibling element */
	height: 1px;
	width: 1px;
	margin: -1px;
	overflow: hidden;
	padding: 0;
	clip: rect(1px, 1px, 1px, 1px);
	clip-path: inset(50%);
}

/* The hc-black theme is already high contrast optimized */
.monaco-editor.hc-black {
	-ms-high-contrast-adjust: none;
}
/* In case the browser goes into high contrast mode and the editor is not configured with the hc-black theme */
@media screen and (-ms-high-contrast:active) {

	/* current line highlight */
	.monaco-editor.vs .view-overlays .current-line,
	.monaco-editor.vs-dark .view-overlays .current-line {
		border-color: windowtext !important;
		border-left: 0;
		border-right: 0;
	}

	/* view cursors */
	.monaco-editor.vs .cursor,
	.monaco-editor.vs-dark .cursor {
		background-color: windowtext !important;
	}
	/* dnd target */
	.monaco-editor.vs .dnd-target,
	.monaco-editor.vs-dark .dnd-target {
		border-color: windowtext !important;
	}

	/* selected text background */
	.monaco-editor.vs .selected-text,
	.monaco-editor.vs-dark .selected-text {
		background-color: highlight !important;
	}

	/* allow the text to have a transparent background. */
	.monaco-editor.vs .view-line,
	.monaco-editor.vs-dark .view-line {
		-ms-high-contrast-adjust: none;
	}

	/* text color */
	.monaco-editor.vs .view-line span,
	.monaco-editor.vs-dark .view-line span {
		color: windowtext !important;
	}
	/* selected text color */
	.monaco-editor.vs .view-line span.inline-selected-text,
	.monaco-editor.vs-dark .view-line span.inline-selected-text {
		color: highlighttext !important;
	}

	/* allow decorations */
	.monaco-editor.vs .view-overlays,
	.monaco-editor.vs-dark .view-overlays {
		-ms-high-contrast-adjust: none;
	}

	/* various decorations */
	.monaco-editor.vs .selectionHighlight,
	.monaco-editor.vs-dark .selectionHighlight,
	.monaco-editor.vs .wordHighlight,
	.monaco-editor.vs-dark .wordHighlight,
	.monaco-editor.vs .wordHighlightStrong,
	.monaco-editor.vs-dark .wordHighlightStrong,
	.monaco-editor.vs .reference-decoration,
	.monaco-editor.vs-dark .reference-decoration {
		border: 2px dotted highlight !important;
		background: transparent !important;
		box-sizing: border-box;
	}
	.monaco-editor.vs .rangeHighlight,
	.monaco-editor.vs-dark .rangeHighlight {
		background: transparent !important;
		border: 1px dotted activeborder !important;
		box-sizing: border-box;
	}
	.monaco-editor.vs .bracket-match,
	.monaco-editor.vs-dark .bracket-match {
		border-color: windowtext !important;
		background: transparent !important;
	}

	/* find widget */
	.monaco-editor.vs .findMatch,
	.monaco-editor.vs-dark .findMatch,
	.monaco-editor.vs .currentFindMatch,
	.monaco-editor.vs-dark .currentFindMatch {
		border: 2px dotted activeborder !important;
		background: transparent !important;
		box-sizing: border-box;
	}
	.monaco-editor.vs .find-widget,
	.monaco-editor.vs-dark .find-widget {
		border: 1px solid windowtext;
	}

	/* list - used by suggest widget */
	.monaco-editor.vs .monaco-list .monaco-list-row,
	.monaco-editor.vs-dark .monaco-list .monaco-list-row {
		-ms-high-contrast-adjust: none;
		color: windowtext !important;
	}
	.monaco-editor.vs .monaco-list .monaco-list-row.focused,
	.monaco-editor.vs-dark .monaco-list .monaco-list-row.focused {
		color: highlighttext !important;
		background-color: highlight !important;
	}
	.monaco-editor.vs .monaco-list .monaco-list-row:hover,
	.monaco-editor.vs-dark .monaco-list .monaco-list-row:hover {
		background: transparent !important;
		border: 1px solid highlight;
		box-sizing: border-box;
	}

	/* scrollbars */
	.monaco-editor.vs .monaco-scrollable-element > .scrollbar,
	.monaco-editor.vs-dark .monaco-scrollable-element > .scrollbar {
		-ms-high-contrast-adjust: none;
		background: background !important;
		border: 1px solid windowtext;
		box-sizing: border-box;
	}
	.monaco-editor.vs .monaco-scrollable-element > .scrollbar > .slider,
	.monaco-editor.vs-dark .monaco-scrollable-element > .scrollbar > .slider {
		background: windowtext !important;
	}
	.monaco-editor.vs .monaco-scrollable-element > .scrollbar > .slider:hover,
	.monaco-editor.vs-dark .monaco-scrollable-element > .scrollbar > .slider:hover {
		background: highlight !important;
	}
	.monaco-editor.vs .monaco-scrollable-element > .scrollbar > .slider.active,
	.monaco-editor.vs-dark .monaco-scrollable-element > .scrollbar > .slider.active {
		background: highlight !important;
	}

	/* overview ruler */
	.monaco-editor.vs .decorationsOverviewRuler,
	.monaco-editor.vs-dark .decorationsOverviewRuler {
		opacity: 0;
	}

	/* minimap */
	.monaco-editor.vs .minimap,
	.monaco-editor.vs-dark .minimap {
		display: none;
	}

	/* squiggles */
	.monaco-editor.vs .squiggly-d-error,
	.monaco-editor.vs-dark .squiggly-d-error {
		background: transparent !important;
		border-bottom: 4px double #E47777;
	}
	.monaco-editor.vs .squiggly-c-warning,
	.monaco-editor.vs-dark .squiggly-c-warning {
		border-bottom: 4px double #71B771;
	}
	.monaco-editor.vs .squiggly-b-info,
	.monaco-editor.vs-dark .squiggly-b-info {
		border-bottom: 4px double #71B771;
	}
	.monaco-editor.vs .squiggly-a-hint,
	.monaco-editor.vs-dark .squiggly-a-hint {
		border-bottom: 4px double #6c6c6c;
	}

	/* contextmenu */
	.monaco-editor.vs .monaco-menu .monaco-action-bar.vertical .action-menu-item:focus .action-label,
	.monaco-editor.vs-dark .monaco-menu .monaco-action-bar.vertical .action-menu-item:focus .action-label {
		-ms-high-contrast-adjust: none;
		color: highlighttext !important;
		background-color: highlight !important;
	}
	.monaco-editor.vs .monaco-menu .monaco-action-bar.vertical .action-menu-item:hover .action-label,
	.monaco-editor.vs-dark .monaco-menu .monaco-action-bar.vertical .action-menu-item:hover .action-label {
		-ms-high-contrast-adjust: none;
		background: transparent !important;
		border: 1px solid highlight;
		box-sizing: border-box;
	}

	/* diff editor */
	.monaco-diff-editor.vs .diffOverviewRuler,
	.monaco-diff-editor.vs-dark .diffOverviewRuler {
		display: none;
	}
	.monaco-editor.vs .line-insert,
	.monaco-editor.vs-dark .line-insert,
	.monaco-editor.vs .line-delete,
	.monaco-editor.vs-dark .line-delete {
		background: transparent !important;
		border: 1px solid highlight !important;
		box-sizing: border-box;
	}
	.monaco-editor.vs .char-insert,
	.monaco-editor.vs-dark .char-insert,
	.monaco-editor.vs .char-delete,
	.monaco-editor.vs-dark .char-delete {
		background: transparent !important;
	}
}

/*.monaco-editor.vs [tabindex="0"]:focus {
	outline: 1px solid rgba(0, 122, 204, 0.4);
	outline-offset: -1px;
	opacity: 1 !important;
}

.monaco-editor.vs-dark [tabindex="0"]:focus {
	outline: 1px solid rgba(14, 99, 156, 0.6);
	outline-offset: -1px;
	opacity: 1 !important;
}*/
</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/
/* ---------- DiffEditor ---------- */

.monaco-diff-editor .diffOverview {
	z-index: 9;
}

.monaco-diff-editor .diffOverview .diffViewport {
	z-index: 10;
}

/* colors not externalized: using transparancy on background */
.monaco-diff-editor.vs			.diffOverview { background: rgba(0, 0, 0, 0.03); }
.monaco-diff-editor.vs-dark		.diffOverview { background: rgba(255, 255, 255, 0.01); }

.monaco-scrollable-element.modified-in-monaco-diff-editor.vs		.scrollbar { background: rgba(0,0,0,0); }
.monaco-scrollable-element.modified-in-monaco-diff-editor.vs-dark	.scrollbar { background: rgba(0,0,0,0); }
.monaco-scrollable-element.modified-in-monaco-diff-editor.hc-black	.scrollbar { background: none; }

.monaco-scrollable-element.modified-in-monaco-diff-editor .slider {
	z-index: 10;
}
.modified-in-monaco-diff-editor				.slider.active { background: rgba(171, 171, 171, .4); }
.modified-in-monaco-diff-editor.hc-black	.slider.active { background: none; }

/* ---------- Diff ---------- */

.monaco-editor .insert-sign,
.monaco-diff-editor .insert-sign,
.monaco-editor .delete-sign,
.monaco-diff-editor .delete-sign {
	font-size: 11px !important;
	opacity: 0.7 !important;
	display: flex !important;
	align-items: center;
}
.monaco-editor.hc-black .insert-sign,
.monaco-diff-editor.hc-black .insert-sign,
.monaco-editor.hc-black .delete-sign,
.monaco-diff-editor.hc-black .delete-sign {
	opacity: 1;
}

.monaco-editor .inline-deleted-margin-view-zone {
	text-align: right;
}
.monaco-editor .inline-added-margin-view-zone {
	text-align: right;
}

/* ---------- Inline Diff ---------- */

.monaco-editor .view-zones .view-lines .view-line span {
	display: inline-block;
}

.monaco-editor .margin-view-zones .lightbulb-glyph:hover {
	cursor: pointer;
}
</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

.monaco-diff-editor .diff-review-line-number {
	text-align: right;
	display: inline-block;
}

.monaco-diff-editor .diff-review {
	position: absolute;
	user-select: none;
	-webkit-user-select: none;
	-ms-user-select: none;
}

.monaco-diff-editor .diff-review-summary {
	padding-left: 10px;
}

.monaco-diff-editor .diff-review-shadow {
	position: absolute;
}

.monaco-diff-editor .diff-review-row {
	white-space: pre;
}

.monaco-diff-editor .diff-review-table {
	display: table;
	min-width: 100%;
}

.monaco-diff-editor .diff-review-row {
	display: table-row;
	width: 100%;
}

.monaco-diff-editor .diff-review-spacer {
	display: inline-block;
	width: 10px;
	vertical-align: middle;
}

.monaco-diff-editor .diff-review-spacer > .codicon {
	font-size: 9px !important;
}

.monaco-diff-editor .diff-review-actions {
	display: inline-block;
	position: absolute;
	right: 10px;
	top: 2px;
}

.monaco-diff-editor .diff-review-actions .action-label {
	width: 16px;
	height: 16px;
	margin: 2px 0;
}
</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

.context-view {
	position: absolute;
	z-index: 2500;
}

.context-view.fixed {
	all: initial;
	font-family: inherit;
	font-size: 13px;
	position: fixed;
	z-index: 2500;
	color: inherit;
}
</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

.context-view .monaco-menu {
	min-width: 130px;
}

</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

.quick-input-widget {
	font-size: 13px;
}

.quick-input-widget .monaco-highlighted-label .highlight,
.quick-input-widget .monaco-highlighted-label .highlight {
	color: #0066BF;
}

.vs .quick-input-widget .monaco-list-row.focused .monaco-highlighted-label .highlight,
.vs .quick-input-widget .monaco-list-row.focused .monaco-highlighted-label .highlight {
	color: #9DDDFF;
}

.vs-dark .quick-input-widget .monaco-highlighted-label .highlight,
.vs-dark .quick-input-widget .monaco-highlighted-label .highlight {
	color: #0097fb;
}

.hc-black .quick-input-widget .monaco-highlighted-label .highlight,
.hc-black .quick-input-widget .monaco-highlighted-label .highlight {
	color: #F38518;
}

.monaco-keybinding > .monaco-keybinding-key {
	background-color: rgba(221, 221, 221, 0.4);
	border: solid 1px rgba(204, 204, 204, 0.4);
	border-bottom-color: rgba(187, 187, 187, 0.4);
	box-shadow: inset 0 -1px 0 rgba(187, 187, 187, 0.4);
	color: #555;
}

.hc-black .monaco-keybinding > .monaco-keybinding-key {
	background-color: transparent;
	border: solid 1px rgb(111, 195, 223);
	box-shadow: none;
	color: #fff;
}

.vs-dark .monaco-keybinding > .monaco-keybinding-key {
	background-color: rgba(128, 128, 128, 0.17);
	border: solid 1px rgba(51, 51, 51, 0.6);
	border-bottom-color: rgba(68, 68, 68, 0.6);
	box-shadow: inset 0 -1px 0 rgba(68, 68, 68, 0.6);
	color: #ccc;
}
</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

.monaco-text-button {
	box-sizing: border-box;
	display: flex;
	width: 100%;
	padding: 4px;
	text-align: center;
	cursor: pointer;
	justify-content: center;
	align-items: center;
}

.monaco-text-button:focus {
	outline-offset: 2px !important;
}

.monaco-text-button:hover {
	text-decoration: none !important;
}

.monaco-button.disabled:focus,
.monaco-button.disabled {
	opacity: 0.4 !important;
	cursor: default;
}

.monaco-text-button > .codicon {
	margin: 0 0.2em;
	color: inherit !important;
}

.monaco-button-dropdown {
	display: flex;
	cursor: pointer;
}

.monaco-button-dropdown > .monaco-dropdown-button {
	margin-left: 1px;
}

.monaco-description-button {
	flex-direction: column;
}

.monaco-description-button .monaco-button-label {
	font-weight: 500;
}

.monaco-description-button .monaco-button-description {
	font-style: italic;
}
</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

.monaco-progress-container {
	width: 100%;
	height: 5px;
	overflow: hidden; /* keep progress bit in bounds */
}

.monaco-progress-container .progress-bit {
	width: 2%;
	height: 5px;
	position: absolute;
	left: 0;
	display: none;
}

.monaco-progress-container.active .progress-bit {
	display: inherit;
}

.monaco-progress-container.discrete .progress-bit {
	left: 0;
	transition: width 100ms linear;
}

.monaco-progress-container.discrete.done .progress-bit {
	width: 100%;
}

.monaco-progress-container.infinite .progress-bit {
	animation-name: progress;
	animation-duration: 4s;
	animation-iteration-count: infinite;
	animation-timing-function: linear;
	transform: translate3d(0px, 0px, 0px);
}

/**
 * The progress bit has a width: 2% (1/50) of the parent container. The animation moves it from 0% to 100% of
 * that container. Since translateX is relative to the progress bit size, we have to multiple it with
 * its relative size to the parent container:
 * parent width: 5000%
 *    bit width: 100%
 * translateX should be as follow:
 *  50%: 5000% * 50% - 50% (set to center) = 2450%
 * 100%: 5000% * 100% - 100% (do not overflow) = 4900%
 */
@keyframes progress { from { transform: translateX(0%) scaleX(1) } 50% { transform: translateX(2500%) scaleX(3) } to { transform: translateX(4900%) scaleX(1) } }
</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

.quick-input-widget {
	position: absolute;
	width: 600px;
	z-index: 2000;
	padding: 0 1px 1px 1px;
	left: 50%;
	margin-left: -300px;
}

.quick-input-titlebar {
	display: flex;
	align-items: center;
}

.quick-input-left-action-bar {
	display: flex;
	margin-left: 4px;
	flex: 1;
}

.quick-input-title {
	padding: 3px 0px;
	text-align: center;
	text-overflow: ellipsis;
	overflow: hidden;
}

.quick-input-right-action-bar {
	display: flex;
	margin-right: 4px;
	flex: 1;
}

.quick-input-right-action-bar > .actions-container {
	justify-content: flex-end;
}

.quick-input-titlebar .monaco-action-bar .action-label.codicon {
	background-position: center;
	background-repeat: no-repeat;
	padding: 2px;
}

.quick-input-description {
	margin: 6px;
}

.quick-input-header .quick-input-description {
	margin: 4px 2px;
}

.quick-input-header {
	display: flex;
	padding: 6px 6px 0px 6px;
	margin-bottom: -2px;
}

.quick-input-widget.hidden-input .quick-input-header {
	/* reduce margins and paddings when input box hidden */
	padding: 0;
	margin-bottom: 0;
}

.quick-input-and-message {
	display: flex;
	flex-direction: column;
	flex-grow: 1;
	min-width: 0;
	position: relative;
}

.quick-input-check-all {
	align-self: center;
	margin: 0;
}

.quick-input-filter {
	flex-grow: 1;
	display: flex;
	position: relative;
}

.quick-input-box {
	flex-grow: 1;
}

.quick-input-widget.show-checkboxes .quick-input-box,
.quick-input-widget.show-checkboxes .quick-input-message {
	margin-left: 5px;
}

.quick-input-visible-count {
	position: absolute;
	left: -10000px;
}

.quick-input-count {
	align-self: center;
	position: absolute;
	right: 4px;
	display: flex;
	align-items: center;
}

.quick-input-count .monaco-count-badge {
	vertical-align: middle;
	padding: 2px 4px;
	border-radius: 2px;
	min-height: auto;
	line-height: normal;
}

.quick-input-action {
	margin-left: 6px;
}

.quick-input-action .monaco-text-button {
	font-size: 11px;
	padding: 0 6px;
	display: flex;
	height: 27.5px;
	align-items: center;
}

.quick-input-message {
	margin-top: -1px;
	padding: 5px 5px 2px 5px;
	overflow-wrap: break-word;
}

.quick-input-message > .codicon {
	margin: 0 0.2em;
	vertical-align: text-bottom;
}

.quick-input-progress.monaco-progress-container {
	position: relative;
}

.quick-input-progress.monaco-progress-container,
.quick-input-progress.monaco-progress-container .progress-bit {
	height: 2px;
}

.quick-input-list {
	line-height: 22px;
	margin-top: 6px;
}

.quick-input-widget.hidden-input .quick-input-list {
	margin-top: 0; /* reduce margins when input box hidden */
}

.quick-input-list .monaco-list {
	overflow: hidden;
	max-height: calc(20 * 22px);
}

.quick-input-list .quick-input-list-entry {
	box-sizing: border-box;
	overflow: hidden;
	display: flex;
	height: 100%;
	padding: 0 6px;
}

.quick-input-list .quick-input-list-entry.quick-input-list-separator-border {
	border-top-width: 1px;
	border-top-style: solid;
}

.quick-input-list .monaco-list-row[data-index="0"] .quick-input-list-entry.quick-input-list-separator-border {
	border-top-style: none;
}

.quick-input-list .quick-input-list-label {
	overflow: hidden;
	display: flex;
	height: 100%;
	flex: 1;
}

.quick-input-list .quick-input-list-checkbox {
	align-self: center;
	margin: 0;
}

.quick-input-list .quick-input-list-rows {
	overflow: hidden;
	text-overflow: ellipsis;
	display: flex;
	flex-direction: column;
	height: 100%;
	flex: 1;
	margin-left: 5px;
}

.quick-input-widget.show-checkboxes .quick-input-list .quick-input-list-rows {
	margin-left: 10px;
}

.quick-input-widget .quick-input-list .quick-input-list-checkbox {
	display: none;
}
.quick-input-widget.show-checkboxes .quick-input-list .quick-input-list-checkbox {
	display: inline;
}

.quick-input-list .quick-input-list-rows > .quick-input-list-row {
	display: flex;
	align-items: center;
}

.quick-input-list .quick-input-list-rows > .quick-input-list-row .monaco-icon-label,
.quick-input-list .quick-input-list-rows > .quick-input-list-row .monaco-icon-label .monaco-icon-label-container > .monaco-icon-name-container {
	flex: 1; /* make sure the icon label grows within the row */
}

.quick-input-list .quick-input-list-rows > .quick-input-list-row .codicon[class*='codicon-'] {
	vertical-align: text-bottom;
}

.quick-input-list .quick-input-list-rows .monaco-highlighted-label span {
	opacity: 1;
}

.quick-input-list .quick-input-list-entry .quick-input-list-entry-keybinding {
	margin-right: 8px; /* separate from the separator label or scrollbar if any */
}

.quick-input-list .quick-input-list-label-meta {
	opacity: 0.7;
	line-height: normal;
	text-overflow: ellipsis;
	overflow: hidden;
}

.quick-input-list .monaco-highlighted-label .highlight {
	font-weight: bold;
}

.quick-input-list .quick-input-list-entry .quick-input-list-separator {
	margin-right: 8px; /* separate from keybindings or actions */
}

.quick-input-list .quick-input-list-entry-action-bar {
	display: flex;
	flex: 0;
	overflow: visible;
}

.quick-input-list .quick-input-list-entry-action-bar .action-label {
	/*
	 * By default, actions in the quick input action bar are hidden
	 * until hovered over them or selected.
	 */
	display: none;
}

.quick-input-list .quick-input-list-entry-action-bar .action-label.codicon {
	margin-right: 4px;
	padding: 0px 2px 2px 2px;
}

.quick-input-list .quick-input-list-entry-action-bar {
	margin-top: 1px;
}

.quick-input-list .quick-input-list-entry-action-bar {
	margin-right: 4px; /* separate from scrollbar */
}

.quick-input-list .quick-input-list-entry .quick-input-list-entry-action-bar .action-label.always-visible,
.quick-input-list .quick-input-list-entry:hover .quick-input-list-entry-action-bar .action-label,
.quick-input-list .monaco-list-row.focused .quick-input-list-entry-action-bar .action-label {
	display: flex;
}

/* focused items in quick pick */
.quick-input-list .monaco-list-row.focused .monaco-keybinding-key,
.quick-input-list .monaco-list-row.focused .quick-input-list-entry .quick-input-list-separator {
	color: inherit
}
.quick-input-list .monaco-list-row.focused .monaco-keybinding-key {
	background: none;
}
</style><style>/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

.monaco-keybinding {
	display: flex;
	align-items: center;
	line-height: 10px;
}

.monaco-keybinding > .monaco-keybinding-key {
	display: inline-block;
	border-style: solid;
	border-width: 1px;
	border-radius: 3px;
	vertical-align: middle;
	font-size: 11px;
	padding: 3px 5px;
	margin: 0 2px;
}

.monaco-keybinding > .monaco-keybinding-key:first-child {
	margin-left: 0;
}

.monaco-keybinding > .monaco-keybinding-key:last-child {
	margin-right: 0;
}

.monaco-keybinding > .monaco-keybinding-key-separator {
	display: inline-block;
}

.monaco-keybinding > .monaco-keybinding-key-chord-separator {
	width: 6px;
}
</style><style data-styled="active" data-styled-version="5.1.1"></style><style data-styled="active" data-styled-version="5.1.1"></style><style>.splitter-layout {
  position: absolute;
  display: flex;
  flex-direction: row;
  width: 100%;
  height: 100%;
  overflow: hidden;
}

.splitter-layout .layout-pane {
  position: relative;
  flex: 0 0 auto;
  overflow: auto;
}

.splitter-layout .layout-pane.layout-pane-primary {
  flex: 1 1 auto;
}

.splitter-layout > .layout-splitter {
  flex: 0 0 auto;
  width: 4px;
  height: 100%;
  cursor: col-resize;
  background-color: #ccc;
}

.splitter-layout .layout-splitter:hover {
  background-color: #bbb;
}

.splitter-layout.layout-changing {
  cursor: col-resize;
}

.splitter-layout.layout-changing > .layout-splitter {
  background-color: #aaa;
}

.splitter-layout.splitter-layout-vertical {
  flex-direction: column;
}

.splitter-layout.splitter-layout-vertical.layout-changing {
  cursor: row-resize;
}

.splitter-layout.splitter-layout-vertical > .layout-splitter {
  width: 100%;
  height: 4px;
  cursor: row-resize;
}
</style><style data-emotion="css"></style><style type="text/css" media="screen" class="monaco-colors">.codicon-add:before { content: '\ea60'; }
.codicon-plus:before { content: '\ea60'; }
.codicon-gist-new:before { content: '\ea60'; }
.codicon-repo-create:before { content: '\ea60'; }
.codicon-lightbulb:before { content: '\ea61'; }
.codicon-light-bulb:before { content: '\ea61'; }
.codicon-repo:before { content: '\ea62'; }
.codicon-repo-delete:before { content: '\ea62'; }
.codicon-gist-fork:before { content: '\ea63'; }
.codicon-repo-forked:before { content: '\ea63'; }
.codicon-git-pull-request:before { content: '\ea64'; }
.codicon-git-pull-request-abandoned:before { content: '\ea64'; }
.codicon-record-keys:before { content: '\ea65'; }
.codicon-keyboard:before { content: '\ea65'; }
.codicon-tag:before { content: '\ea66'; }
.codicon-tag-add:before { content: '\ea66'; }
.codicon-tag-remove:before { content: '\ea66'; }
.codicon-person:before { content: '\ea67'; }
.codicon-person-follow:before { content: '\ea67'; }
.codicon-person-outline:before { content: '\ea67'; }
.codicon-person-filled:before { content: '\ea67'; }
.codicon-git-branch:before { content: '\ea68'; }
.codicon-git-branch-create:before { content: '\ea68'; }
.codicon-git-branch-delete:before { content: '\ea68'; }
.codicon-source-control:before { content: '\ea68'; }
.codicon-mirror:before { content: '\ea69'; }
.codicon-mirror-public:before { content: '\ea69'; }
.codicon-star:before { content: '\ea6a'; }
.codicon-star-add:before { content: '\ea6a'; }
.codicon-star-delete:before { content: '\ea6a'; }
.codicon-star-empty:before { content: '\ea6a'; }
.codicon-comment:before { content: '\ea6b'; }
.codicon-comment-add:before { content: '\ea6b'; }
.codicon-alert:before { content: '\ea6c'; }
.codicon-warning:before { content: '\ea6c'; }
.codicon-search:before { content: '\ea6d'; }
.codicon-search-save:before { content: '\ea6d'; }
.codicon-log-out:before { content: '\ea6e'; }
.codicon-sign-out:before { content: '\ea6e'; }
.codicon-log-in:before { content: '\ea6f'; }
.codicon-sign-in:before { content: '\ea6f'; }
.codicon-eye:before { content: '\ea70'; }
.codicon-eye-unwatch:before { content: '\ea70'; }
.codicon-eye-watch:before { content: '\ea70'; }
.codicon-circle-filled:before { content: '\ea71'; }
.codicon-primitive-dot:before { content: '\ea71'; }
.codicon-close-dirty:before { content: '\ea71'; }
.codicon-debug-breakpoint:before { content: '\ea71'; }
.codicon-debug-breakpoint-disabled:before { content: '\ea71'; }
.codicon-debug-hint:before { content: '\ea71'; }
.codicon-primitive-square:before { content: '\ea72'; }
.codicon-edit:before { content: '\ea73'; }
.codicon-pencil:before { content: '\ea73'; }
.codicon-info:before { content: '\ea74'; }
.codicon-issue-opened:before { content: '\ea74'; }
.codicon-gist-private:before { content: '\ea75'; }
.codicon-git-fork-private:before { content: '\ea75'; }
.codicon-lock:before { content: '\ea75'; }
.codicon-mirror-private:before { content: '\ea75'; }
.codicon-close:before { content: '\ea76'; }
.codicon-remove-close:before { content: '\ea76'; }
.codicon-x:before { content: '\ea76'; }
.codicon-repo-sync:before { content: '\ea77'; }
.codicon-sync:before { content: '\ea77'; }
.codicon-clone:before { content: '\ea78'; }
.codicon-desktop-download:before { content: '\ea78'; }
.codicon-beaker:before { content: '\ea79'; }
.codicon-microscope:before { content: '\ea79'; }
.codicon-vm:before { content: '\ea7a'; }
.codicon-device-desktop:before { content: '\ea7a'; }
.codicon-file:before { content: '\ea7b'; }
.codicon-file-text:before { content: '\ea7b'; }
.codicon-more:before { content: '\ea7c'; }
.codicon-ellipsis:before { content: '\ea7c'; }
.codicon-kebab-horizontal:before { content: '\ea7c'; }
.codicon-mail-reply:before { content: '\ea7d'; }
.codicon-reply:before { content: '\ea7d'; }
.codicon-organization:before { content: '\ea7e'; }
.codicon-organization-filled:before { content: '\ea7e'; }
.codicon-organization-outline:before { content: '\ea7e'; }
.codicon-new-file:before { content: '\ea7f'; }
.codicon-file-add:before { content: '\ea7f'; }
.codicon-new-folder:before { content: '\ea80'; }
.codicon-file-directory-create:before { content: '\ea80'; }
.codicon-trash:before { content: '\ea81'; }
.codicon-trashcan:before { content: '\ea81'; }
.codicon-history:before { content: '\ea82'; }
.codicon-clock:before { content: '\ea82'; }
.codicon-folder:before { content: '\ea83'; }
.codicon-file-directory:before { content: '\ea83'; }
.codicon-symbol-folder:before { content: '\ea83'; }
.codicon-logo-github:before { content: '\ea84'; }
.codicon-mark-github:before { content: '\ea84'; }
.codicon-github:before { content: '\ea84'; }
.codicon-terminal:before { content: '\ea85'; }
.codicon-console:before { content: '\ea85'; }
.codicon-repl:before { content: '\ea85'; }
.codicon-zap:before { content: '\ea86'; }
.codicon-symbol-event:before { content: '\ea86'; }
.codicon-error:before { content: '\ea87'; }
.codicon-stop:before { content: '\ea87'; }
.codicon-variable:before { content: '\ea88'; }
.codicon-symbol-variable:before { content: '\ea88'; }
.codicon-array:before { content: '\ea8a'; }
.codicon-symbol-array:before { content: '\ea8a'; }
.codicon-symbol-module:before { content: '\ea8b'; }
.codicon-symbol-package:before { content: '\ea8b'; }
.codicon-symbol-namespace:before { content: '\ea8b'; }
.codicon-symbol-object:before { content: '\ea8b'; }
.codicon-symbol-method:before { content: '\ea8c'; }
.codicon-symbol-function:before { content: '\ea8c'; }
.codicon-symbol-constructor:before { content: '\ea8c'; }
.codicon-symbol-boolean:before { content: '\ea8f'; }
.codicon-symbol-null:before { content: '\ea8f'; }
.codicon-symbol-numeric:before { content: '\ea90'; }
.codicon-symbol-number:before { content: '\ea90'; }
.codicon-symbol-structure:before { content: '\ea91'; }
.codicon-symbol-struct:before { content: '\ea91'; }
.codicon-symbol-parameter:before { content: '\ea92'; }
.codicon-symbol-type-parameter:before { content: '\ea92'; }
.codicon-symbol-key:before { content: '\ea93'; }
.codicon-symbol-text:before { content: '\ea93'; }
.codicon-symbol-reference:before { content: '\ea94'; }
.codicon-go-to-file:before { content: '\ea94'; }
.codicon-symbol-enum:before { content: '\ea95'; }
.codicon-symbol-value:before { content: '\ea95'; }
.codicon-symbol-ruler:before { content: '\ea96'; }
.codicon-symbol-unit:before { content: '\ea96'; }
.codicon-activate-breakpoints:before { content: '\ea97'; }
.codicon-archive:before { content: '\ea98'; }
.codicon-arrow-both:before { content: '\ea99'; }
.codicon-arrow-down:before { content: '\ea9a'; }
.codicon-arrow-left:before { content: '\ea9b'; }
.codicon-arrow-right:before { content: '\ea9c'; }
.codicon-arrow-small-down:before { content: '\ea9d'; }
.codicon-arrow-small-left:before { content: '\ea9e'; }
.codicon-arrow-small-right:before { content: '\ea9f'; }
.codicon-arrow-small-up:before { content: '\eaa0'; }
.codicon-arrow-up:before { content: '\eaa1'; }
.codicon-bell:before { content: '\eaa2'; }
.codicon-bold:before { content: '\eaa3'; }
.codicon-book:before { content: '\eaa4'; }
.codicon-bookmark:before { content: '\eaa5'; }
.codicon-debug-breakpoint-conditional-unverified:before { content: '\eaa6'; }
.codicon-debug-breakpoint-conditional:before { content: '\eaa7'; }
.codicon-debug-breakpoint-conditional-disabled:before { content: '\eaa7'; }
.codicon-debug-breakpoint-data-unverified:before { content: '\eaa8'; }
.codicon-debug-breakpoint-data:before { content: '\eaa9'; }
.codicon-debug-breakpoint-data-disabled:before { content: '\eaa9'; }
.codicon-debug-breakpoint-log-unverified:before { content: '\eaaa'; }
.codicon-debug-breakpoint-log:before { content: '\eaab'; }
.codicon-debug-breakpoint-log-disabled:before { content: '\eaab'; }
.codicon-briefcase:before { content: '\eaac'; }
.codicon-broadcast:before { content: '\eaad'; }
.codicon-browser:before { content: '\eaae'; }
.codicon-bug:before { content: '\eaaf'; }
.codicon-calendar:before { content: '\eab0'; }
.codicon-case-sensitive:before { content: '\eab1'; }
.codicon-check:before { content: '\eab2'; }
.codicon-checklist:before { content: '\eab3'; }
.codicon-chevron-down:before { content: '\eab4'; }
.codicon-drop-down-button:before { content: '\eab4'; }
.codicon-chevron-left:before { content: '\eab5'; }
.codicon-chevron-right:before { content: '\eab6'; }
.codicon-chevron-up:before { content: '\eab7'; }
.codicon-chrome-close:before { content: '\eab8'; }
.codicon-chrome-maximize:before { content: '\eab9'; }
.codicon-chrome-minimize:before { content: '\eaba'; }
.codicon-chrome-restore:before { content: '\eabb'; }
.codicon-circle-outline:before { content: '\eabc'; }
.codicon-debug-breakpoint-unverified:before { content: '\eabc'; }
.codicon-circle-slash:before { content: '\eabd'; }
.codicon-circuit-board:before { content: '\eabe'; }
.codicon-clear-all:before { content: '\eabf'; }
.codicon-clippy:before { content: '\eac0'; }
.codicon-close-all:before { content: '\eac1'; }
.codicon-cloud-download:before { content: '\eac2'; }
.codicon-cloud-upload:before { content: '\eac3'; }
.codicon-code:before { content: '\eac4'; }
.codicon-collapse-all:before { content: '\eac5'; }
.codicon-color-mode:before { content: '\eac6'; }
.codicon-comment-discussion:before { content: '\eac7'; }
.codicon-compare-changes:before { content: '\eafd'; }
.codicon-credit-card:before { content: '\eac9'; }
.codicon-dash:before { content: '\eacc'; }
.codicon-dashboard:before { content: '\eacd'; }
.codicon-database:before { content: '\eace'; }
.codicon-debug-continue:before { content: '\eacf'; }
.codicon-debug-disconnect:before { content: '\ead0'; }
.codicon-debug-pause:before { content: '\ead1'; }
.codicon-debug-restart:before { content: '\ead2'; }
.codicon-debug-start:before { content: '\ead3'; }
.codicon-debug-step-into:before { content: '\ead4'; }
.codicon-debug-step-out:before { content: '\ead5'; }
.codicon-debug-step-over:before { content: '\ead6'; }
.codicon-debug-stop:before { content: '\ead7'; }
.codicon-debug:before { content: '\ead8'; }
.codicon-device-camera-video:before { content: '\ead9'; }
.codicon-device-camera:before { content: '\eada'; }
.codicon-device-mobile:before { content: '\eadb'; }
.codicon-diff-added:before { content: '\eadc'; }
.codicon-diff-ignored:before { content: '\eadd'; }
.codicon-diff-modified:before { content: '\eade'; }
.codicon-diff-removed:before { content: '\eadf'; }
.codicon-diff-renamed:before { content: '\eae0'; }
.codicon-diff:before { content: '\eae1'; }
.codicon-discard:before { content: '\eae2'; }
.codicon-editor-layout:before { content: '\eae3'; }
.codicon-empty-window:before { content: '\eae4'; }
.codicon-exclude:before { content: '\eae5'; }
.codicon-extensions:before { content: '\eae6'; }
.codicon-eye-closed:before { content: '\eae7'; }
.codicon-file-binary:before { content: '\eae8'; }
.codicon-file-code:before { content: '\eae9'; }
.codicon-file-media:before { content: '\eaea'; }
.codicon-file-pdf:before { content: '\eaeb'; }
.codicon-file-submodule:before { content: '\eaec'; }
.codicon-file-symlink-directory:before { content: '\eaed'; }
.codicon-file-symlink-file:before { content: '\eaee'; }
.codicon-file-zip:before { content: '\eaef'; }
.codicon-files:before { content: '\eaf0'; }
.codicon-filter:before { content: '\eaf1'; }
.codicon-flame:before { content: '\eaf2'; }
.codicon-fold-down:before { content: '\eaf3'; }
.codicon-fold-up:before { content: '\eaf4'; }
.codicon-fold:before { content: '\eaf5'; }
.codicon-folder-active:before { content: '\eaf6'; }
.codicon-folder-opened:before { content: '\eaf7'; }
.codicon-gear:before { content: '\eaf8'; }
.codicon-gift:before { content: '\eaf9'; }
.codicon-gist-secret:before { content: '\eafa'; }
.codicon-gist:before { content: '\eafb'; }
.codicon-git-commit:before { content: '\eafc'; }
.codicon-git-compare:before { content: '\eafd'; }
.codicon-git-merge:before { content: '\eafe'; }
.codicon-github-action:before { content: '\eaff'; }
.codicon-github-alt:before { content: '\eb00'; }
.codicon-globe:before { content: '\eb01'; }
.codicon-grabber:before { content: '\eb02'; }
.codicon-graph:before { content: '\eb03'; }
.codicon-gripper:before { content: '\eb04'; }
.codicon-heart:before { content: '\eb05'; }
.codicon-home:before { content: '\eb06'; }
.codicon-horizontal-rule:before { content: '\eb07'; }
.codicon-hubot:before { content: '\eb08'; }
.codicon-inbox:before { content: '\eb09'; }
.codicon-issue-closed:before { content: '\eba4'; }
.codicon-issue-reopened:before { content: '\eb0b'; }
.codicon-issues:before { content: '\eb0c'; }
.codicon-italic:before { content: '\eb0d'; }
.codicon-jersey:before { content: '\eb0e'; }
.codicon-json:before { content: '\eb0f'; }
.codicon-kebab-vertical:before { content: '\eb10'; }
.codicon-key:before { content: '\eb11'; }
.codicon-law:before { content: '\eb12'; }
.codicon-lightbulb-autofix:before { content: '\eb13'; }
.codicon-link-external:before { content: '\eb14'; }
.codicon-link:before { content: '\eb15'; }
.codicon-list-ordered:before { content: '\eb16'; }
.codicon-list-unordered:before { content: '\eb17'; }
.codicon-live-share:before { content: '\eb18'; }
.codicon-loading:before { content: '\eb19'; }
.codicon-location:before { content: '\eb1a'; }
.codicon-mail-read:before { content: '\eb1b'; }
.codicon-mail:before { content: '\eb1c'; }
.codicon-markdown:before { content: '\eb1d'; }
.codicon-megaphone:before { content: '\eb1e'; }
.codicon-mention:before { content: '\eb1f'; }
.codicon-milestone:before { content: '\eb20'; }
.codicon-mortar-board:before { content: '\eb21'; }
.codicon-move:before { content: '\eb22'; }
.codicon-multiple-windows:before { content: '\eb23'; }
.codicon-mute:before { content: '\eb24'; }
.codicon-no-newline:before { content: '\eb25'; }
.codicon-note:before { content: '\eb26'; }
.codicon-octoface:before { content: '\eb27'; }
.codicon-open-preview:before { content: '\eb28'; }
.codicon-package:before { content: '\eb29'; }
.codicon-paintcan:before { content: '\eb2a'; }
.codicon-pin:before { content: '\eb2b'; }
.codicon-play:before { content: '\eb2c'; }
.codicon-run:before { content: '\eb2c'; }
.codicon-plug:before { content: '\eb2d'; }
.codicon-preserve-case:before { content: '\eb2e'; }
.codicon-preview:before { content: '\eb2f'; }
.codicon-project:before { content: '\eb30'; }
.codicon-pulse:before { content: '\eb31'; }
.codicon-question:before { content: '\eb32'; }
.codicon-quote:before { content: '\eb33'; }
.codicon-radio-tower:before { content: '\eb34'; }
.codicon-reactions:before { content: '\eb35'; }
.codicon-references:before { content: '\eb36'; }
.codicon-refresh:before { content: '\eb37'; }
.codicon-regex:before { content: '\eb38'; }
.codicon-remote-explorer:before { content: '\eb39'; }
.codicon-remote:before { content: '\eb3a'; }
.codicon-remove:before { content: '\eb3b'; }
.codicon-replace-all:before { content: '\eb3c'; }
.codicon-replace:before { content: '\eb3d'; }
.codicon-repo-clone:before { content: '\eb3e'; }
.codicon-repo-force-push:before { content: '\eb3f'; }
.codicon-repo-pull:before { content: '\eb40'; }
.codicon-repo-push:before { content: '\eb41'; }
.codicon-report:before { content: '\eb42'; }
.codicon-request-changes:before { content: '\eb43'; }
.codicon-rocket:before { content: '\eb44'; }
.codicon-root-folder-opened:before { content: '\eb45'; }
.codicon-root-folder:before { content: '\eb46'; }
.codicon-rss:before { content: '\eb47'; }
.codicon-ruby:before { content: '\eb48'; }
.codicon-save-all:before { content: '\eb49'; }
.codicon-save-as:before { content: '\eb4a'; }
.codicon-save:before { content: '\eb4b'; }
.codicon-screen-full:before { content: '\eb4c'; }
.codicon-screen-normal:before { content: '\eb4d'; }
.codicon-search-stop:before { content: '\eb4e'; }
.codicon-server:before { content: '\eb50'; }
.codicon-settings-gear:before { content: '\eb51'; }
.codicon-settings:before { content: '\eb52'; }
.codicon-shield:before { content: '\eb53'; }
.codicon-smiley:before { content: '\eb54'; }
.codicon-sort-precedence:before { content: '\eb55'; }
.codicon-split-horizontal:before { content: '\eb56'; }
.codicon-split-vertical:before { content: '\eb57'; }
.codicon-squirrel:before { content: '\eb58'; }
.codicon-star-full:before { content: '\eb59'; }
.codicon-star-half:before { content: '\eb5a'; }
.codicon-symbol-class:before { content: '\eb5b'; }
.codicon-symbol-color:before { content: '\eb5c'; }
.codicon-symbol-constant:before { content: '\eb5d'; }
.codicon-symbol-enum-member:before { content: '\eb5e'; }
.codicon-symbol-field:before { content: '\eb5f'; }
.codicon-symbol-file:before { content: '\eb60'; }
.codicon-symbol-interface:before { content: '\eb61'; }
.codicon-symbol-keyword:before { content: '\eb62'; }
.codicon-symbol-misc:before { content: '\eb63'; }
.codicon-symbol-operator:before { content: '\eb64'; }
.codicon-symbol-property:before { content: '\eb65'; }
.codicon-wrench:before { content: '\eb65'; }
.codicon-wrench-subaction:before { content: '\eb65'; }
.codicon-symbol-snippet:before { content: '\eb66'; }
.codicon-tasklist:before { content: '\eb67'; }
.codicon-telescope:before { content: '\eb68'; }
.codicon-text-size:before { content: '\eb69'; }
.codicon-three-bars:before { content: '\eb6a'; }
.codicon-thumbsdown:before { content: '\eb6b'; }
.codicon-thumbsup:before { content: '\eb6c'; }
.codicon-tools:before { content: '\eb6d'; }
.codicon-triangle-down:before { content: '\eb6e'; }
.codicon-triangle-left:before { content: '\eb6f'; }
.codicon-triangle-right:before { content: '\eb70'; }
.codicon-triangle-up:before { content: '\eb71'; }
.codicon-twitter:before { content: '\eb72'; }
.codicon-unfold:before { content: '\eb73'; }
.codicon-unlock:before { content: '\eb74'; }
.codicon-unmute:before { content: '\eb75'; }
.codicon-unverified:before { content: '\eb76'; }
.codicon-verified:before { content: '\eb77'; }
.codicon-versions:before { content: '\eb78'; }
.codicon-vm-active:before { content: '\eb79'; }
.codicon-vm-outline:before { content: '\eb7a'; }
.codicon-vm-running:before { content: '\eb7b'; }
.codicon-watch:before { content: '\eb7c'; }
.codicon-whitespace:before { content: '\eb7d'; }
.codicon-whole-word:before { content: '\eb7e'; }
.codicon-window:before { content: '\eb7f'; }
.codicon-word-wrap:before { content: '\eb80'; }
.codicon-zoom-in:before { content: '\eb81'; }
.codicon-zoom-out:before { content: '\eb82'; }
.codicon-list-filter:before { content: '\eb83'; }
.codicon-list-flat:before { content: '\eb84'; }
.codicon-list-selection:before { content: '\eb85'; }
.codicon-selection:before { content: '\eb85'; }
.codicon-list-tree:before { content: '\eb86'; }
.codicon-debug-breakpoint-function-unverified:before { content: '\eb87'; }
.codicon-debug-breakpoint-function:before { content: '\eb88'; }
.codicon-debug-breakpoint-function-disabled:before { content: '\eb88'; }
.codicon-debug-stackframe-active:before { content: '\eb89'; }
.codicon-debug-stackframe-dot:before { content: '\eb8a'; }
.codicon-debug-stackframe:before { content: '\eb8b'; }
.codicon-debug-stackframe-focused:before { content: '\eb8b'; }
.codicon-debug-breakpoint-unsupported:before { content: '\eb8c'; }
.codicon-symbol-string:before { content: '\eb8d'; }
.codicon-debug-reverse-continue:before { content: '\eb8e'; }
.codicon-debug-step-back:before { content: '\eb8f'; }
.codicon-debug-restart-frame:before { content: '\eb90'; }
.codicon-call-incoming:before { content: '\eb92'; }
.codicon-call-outgoing:before { content: '\eb93'; }
.codicon-menu:before { content: '\eb94'; }
.codicon-expand-all:before { content: '\eb95'; }
.codicon-feedback:before { content: '\eb96'; }
.codicon-group-by-ref-type:before { content: '\eb97'; }
.codicon-ungroup-by-ref-type:before { content: '\eb98'; }
.codicon-account:before { content: '\eb99'; }
.codicon-bell-dot:before { content: '\eb9a'; }
.codicon-debug-console:before { content: '\eb9b'; }
.codicon-library:before { content: '\eb9c'; }
.codicon-output:before { content: '\eb9d'; }
.codicon-run-all:before { content: '\eb9e'; }
.codicon-sync-ignored:before { content: '\eb9f'; }
.codicon-pinned:before { content: '\eba0'; }
.codicon-github-inverted:before { content: '\eba1'; }
.codicon-debug-alt:before { content: '\eb91'; }
.codicon-server-process:before { content: '\eba2'; }
.codicon-server-environment:before { content: '\eba3'; }
.codicon-pass:before { content: '\eba4'; }
.codicon-stop-circle:before { content: '\eba5'; }
.codicon-play-circle:before { content: '\eba6'; }
.codicon-record:before { content: '\eba7'; }
.codicon-debug-alt-small:before { content: '\eba8'; }
.codicon-vm-connect:before { content: '\eba9'; }
.codicon-cloud:before { content: '\ebaa'; }
.codicon-merge:before { content: '\ebab'; }
.codicon-export:before { content: '\ebac'; }
.codicon-graph-left:before { content: '\ebad'; }
.codicon-magnet:before { content: '\ebae'; }
.codicon-notebook:before { content: '\ebaf'; }
.codicon-redo:before { content: '\ebb0'; }
.codicon-check-all:before { content: '\ebb1'; }
.codicon-pinned-dirty:before { content: '\ebb2'; }
.codicon-pass-filled:before { content: '\ebb3'; }
.codicon-circle-large-filled:before { content: '\ebb4'; }
.codicon-circle-large-outline:before { content: '\ebb5'; }
.codicon-combine:before { content: '\ebb6'; }
.codicon-gather:before { content: '\ebb6'; }
.codicon-table:before { content: '\ebb7'; }
.codicon-variable-group:before { content: '\ebb8'; }
.codicon-type-hierarchy:before { content: '\ebb9'; }
.codicon-type-hierarchy-sub:before { content: '\ebba'; }
.codicon-type-hierarchy-super:before { content: '\ebbb'; }
.codicon-git-pull-request-create:before { content: '\ebbc'; }
.codicon-run-above:before { content: '\ebbd'; }
.codicon-run-below:before { content: '\ebbe'; }
.codicon-notebook-template:before { content: '\ebbf'; }
.codicon-debug-rerun:before { content: '\ebc0'; }
.codicon-workspace-trusted:before { content: '\ebc1'; }
.codicon-workspace-untrusted:before { content: '\ebc2'; }
.codicon-workspace-unspecified:before { content: '\ebc3'; }
.codicon-terminal-cmd:before { content: '\ebc4'; }
.codicon-terminal-debian:before { content: '\ebc5'; }
.codicon-terminal-linux:before { content: '\ebc6'; }
.codicon-terminal-powershell:before { content: '\ebc7'; }
.codicon-terminal-tmux:before { content: '\ebc8'; }
.codicon-terminal-ubuntu:before { content: '\ebc9'; }
.codicon-terminal-bash:before { content: '\ebca'; }
.codicon-arrow-swap:before { content: '\ebcb'; }
.codicon-copy:before { content: '\ebcc'; }
.codicon-person-add:before { content: '\ebcd'; }
.codicon-filter-filled:before { content: '\ebce'; }
.codicon-wand:before { content: '\ebcf'; }
.codicon-debug-line-by-line:before { content: '\ebd0'; }
.codicon-inspect:before { content: '\ebd1'; }
.codicon-layers:before { content: '\ebd2'; }
.codicon-layers-dot:before { content: '\ebd3'; }
.codicon-layers-active:before { content: '\ebd4'; }
.codicon-compass:before { content: '\ebd5'; }
.codicon-compass-dot:before { content: '\ebd6'; }
.codicon-compass-active:before { content: '\ebd7'; }
.codicon-azure:before { content: '\ebd8'; }
.codicon-issue-draft:before { content: '\ebd9'; }
.codicon-git-pull-request-closed:before { content: '\ebda'; }
.codicon-git-pull-request-draft:before { content: '\ebdb'; }
.codicon-debug-all:before { content: '\ebdc'; }
.codicon-debug-coverage:before { content: '\ebdd'; }
.codicon-run-errors:before { content: '\ebde'; }
.codicon-folder-library:before { content: '\ebdf'; }
.codicon-debug-continue-small:before { content: '\ebe0'; }
.codicon-beaker-stop:before { content: '\ebe1'; }
.codicon-graph-line:before { content: '\ebe2'; }
.codicon-graph-scatter:before { content: '\ebe3'; }
.codicon-pie-chart:before { content: '\ebe4'; }
.codicon-bracket:before { content: '\eb0f'; }
.codicon-bracket-dot:before { content: '\ebe5'; }
.codicon-bracket-error:before { content: '\ebe6'; }
.codicon-lock-small:before { content: '\ebe7'; }
.codicon-azure-devops:before { content: '\ebe8'; }
.codicon-verified-filled:before { content: '\ebe9'; }
.codicon-scrollbar-button-left:before { content: '\eb6f'; }
.codicon-scrollbar-button-right:before { content: '\eb70'; }
.codicon-scrollbar-button-up:before { content: '\eb71'; }
.codicon-scrollbar-button-down:before { content: '\eb6e'; }
.codicon-tree-item-expanded:before { content: '\eab4'; }
.codicon-tree-filter-on-type-on:before { content: '\eb83'; }
.codicon-tree-filter-on-type-off:before { content: '\eb85'; }
.codicon-tree-filter-clear:before { content: '\ea76'; }
.codicon-tree-item-loading:before { content: '\eb19'; }
.codicon-widget-close:before { content: '\ea76'; }
.codicon-marker-navigation-next:before { content: '\ea9a'; }
.codicon-marker-navigation-previous:before { content: '\eaa1'; }
.codicon-suggest-more-info:before { content: '\eab6'; }
.codicon-find-selection:before { content: '\eb85'; }
.codicon-find-collapsed:before { content: '\eab6'; }
.codicon-find-expanded:before { content: '\eab4'; }
.codicon-find-replace:before { content: '\eb3d'; }
.codicon-find-replace-all:before { content: '\eb3c'; }
.codicon-find-previous-match:before { content: '\eaa1'; }
.codicon-find-next-match:before { content: '\ea9a'; }
.codicon-folding-expanded:before { content: '\eab4'; }
.codicon-folding-collapsed:before { content: '\eab6'; }
.codicon-parameter-hints-next:before { content: '\eab4'; }
.codicon-parameter-hints-previous:before { content: '\eab7'; }
.codicon-diff-review-insert:before { content: '\ea60'; }
.codicon-diff-review-remove:before { content: '\eb3b'; }
.codicon-diff-review-close:before { content: '\ea76'; }
.codicon-diff-insert:before { content: '\ea60'; }
.codicon-diff-remove:before { content: '\eb3b'; }
.codicon-menu-selection:before { content: '\eab2'; }
.codicon-menu-submenu:before { content: '\eab6'; }
.codicon-quick-input-back:before { content: '\ea9b'; }
.monaco-editor .accessibilityHelpWidget { background-color: #0c141f; }
.monaco-editor .accessibilityHelpWidget { color: #ffffff; }
.monaco-editor .accessibilityHelpWidget { border: 2px solid #6fc3df; }
.monaco-editor, .monaco-editor-background, .monaco-editor .inputarea.ime-input { background-color: #0f1c2c; }
.monaco-editor, .monaco-editor .inputarea.ime-input { color: #ffffff; }
.monaco-editor .margin { background-color: #0f1c2c; }
.monaco-editor .rangeHighlight { border: 1px dotted #f38518; }
.monaco-editor .symbolHighlight { border: 1px dotted #f38518; }
.monaco-editor .mtkw { color: rgba(227, 228, 226, 0.16) !important; }
.monaco-editor .mtkz { color: rgba(227, 228, 226, 0.16) !important; }
.monaco-editor .unexpected-closing-bracket { color: #ff3232; }
.monaco-editor .bracket-highlighting-0 { color: #ffd700; }
.monaco-editor .bracket-highlighting-1 { color: #da70d6; }
.monaco-editor .bracket-highlighting-2 { color: #87cefa; }
.monaco-editor .bracket-highlighting-3 { color: #ffd700; }
.monaco-editor .bracket-highlighting-4 { color: #da70d6; }
.monaco-editor .bracket-highlighting-5 { color: #87cefa; }
.monaco-editor .bracket-highlighting-6 { color: #ffd700; }
.monaco-editor .bracket-highlighting-7 { color: #da70d6; }
.monaco-editor .bracket-highlighting-8 { color: #87cefa; }
.monaco-editor .bracket-highlighting-9 { color: #ffd700; }
.monaco-editor .bracket-highlighting-10 { color: #da70d6; }
.monaco-editor .bracket-highlighting-11 { color: #87cefa; }
.monaco-editor .bracket-highlighting-12 { color: #ffd700; }
.monaco-editor .bracket-highlighting-13 { color: #da70d6; }
.monaco-editor .bracket-highlighting-14 { color: #87cefa; }
.monaco-editor .bracket-highlighting-15 { color: #ffd700; }
.monaco-editor .bracket-highlighting-16 { color: #da70d6; }
.monaco-editor .bracket-highlighting-17 { color: #87cefa; }
.monaco-editor .bracket-highlighting-18 { color: #ffd700; }
.monaco-editor .bracket-highlighting-19 { color: #da70d6; }
.monaco-editor .bracket-highlighting-20 { color: #87cefa; }
.monaco-editor .bracket-highlighting-21 { color: #ffd700; }
.monaco-editor .bracket-highlighting-22 { color: #da70d6; }
.monaco-editor .bracket-highlighting-23 { color: #87cefa; }
.monaco-editor .bracket-highlighting-24 { color: #ffd700; }
.monaco-editor .bracket-highlighting-25 { color: #da70d6; }
.monaco-editor .bracket-highlighting-26 { color: #87cefa; }
.monaco-editor .bracket-highlighting-27 { color: #ffd700; }
.monaco-editor .bracket-highlighting-28 { color: #da70d6; }
.monaco-editor .bracket-highlighting-29 { color: #87cefa; }
.monaco-editor .bracket-match { background-color: rgba(0, 100, 0, 0.1); }
.monaco-editor .bracket-match { border: 1px solid #6fc3df; }
.monaco-editor .monaco-editor-overlaymessage .anchor.below { border-top-color: #6fc3df; }
.monaco-editor .monaco-editor-overlaymessage .anchor.top { border-bottom-color: #6fc3df; }
.monaco-editor .monaco-editor-overlaymessage .message { border: 2px solid #6fc3df; }
.monaco-editor .monaco-editor-overlaymessage .message { background-color: #000000; }

		.monaco-editor .contentWidgets .codicon.codicon-light-bulb {
			color: #ffcc00;
			background-color: rgba(15, 28, 44, 0.7);
		}

		.monaco-editor .contentWidgets .codicon.codicon-lightbulb-autofix {
			color: #75beff;
			background-color: rgba(15, 28, 44, 0.7);
		}
.monaco-editor .codelens-decoration { color: #999999; }
.monaco-editor .codelens-decoration .codicon { color: #999999; }
.monaco-editor .codelens-decoration > a:hover { color: #00ffff !important; }
.monaco-editor .codelens-decoration > a:hover .codicon { color: #00ffff !important; }
.monaco-editor .line-numbers { color: #ffffff; }
.monaco-editor .line-numbers.active-line-number { color: #f38518; }
.monaco-editor .view-overlays .current-line { background-color: #1b324f; }
.monaco-editor .margin-view-overlays .current-line-margin { background-color: #1b324f; border: none; }

			.monaco-scrollable-element > .scrollbar > .slider {
				background: #1b324f;
			}
		

			.monaco-scrollable-element > .scrollbar > .slider:hover {
				background: #1b324f;
			}
		

			.monaco-scrollable-element > .scrollbar > .slider.active {
				background: #1b324f;
			}
		
.monaco-editor .lines-content .core-guide-indent { box-shadow: 1px 0 0 0 #ffffff inset; }
.monaco-editor .lines-content .core-guide-indent-active { box-shadow: 1px 0 0 0 #ffffff inset; }
.monaco-editor .bracket-indent-guide.lvl-0 { --guide-color: rgba(255, 215, 0, 0.3); --guide-color-active: #ffd700; }
.monaco-editor .bracket-indent-guide.lvl-1 { --guide-color: rgba(218, 112, 214, 0.3); --guide-color-active: #da70d6; }
.monaco-editor .bracket-indent-guide.lvl-2 { --guide-color: rgba(135, 206, 250, 0.3); --guide-color-active: #87cefa; }
.monaco-editor .bracket-indent-guide.lvl-3 { --guide-color: rgba(255, 215, 0, 0.3); --guide-color-active: #ffd700; }
.monaco-editor .bracket-indent-guide.lvl-4 { --guide-color: rgba(218, 112, 214, 0.3); --guide-color-active: #da70d6; }
.monaco-editor .bracket-indent-guide.lvl-5 { --guide-color: rgba(135, 206, 250, 0.3); --guide-color-active: #87cefa; }
.monaco-editor .bracket-indent-guide.lvl-6 { --guide-color: rgba(255, 215, 0, 0.3); --guide-color-active: #ffd700; }
.monaco-editor .bracket-indent-guide.lvl-7 { --guide-color: rgba(218, 112, 214, 0.3); --guide-color-active: #da70d6; }
.monaco-editor .bracket-indent-guide.lvl-8 { --guide-color: rgba(135, 206, 250, 0.3); --guide-color-active: #87cefa; }
.monaco-editor .bracket-indent-guide.lvl-9 { --guide-color: rgba(255, 215, 0, 0.3); --guide-color-active: #ffd700; }
.monaco-editor .bracket-indent-guide.lvl-10 { --guide-color: rgba(218, 112, 214, 0.3); --guide-color-active: #da70d6; }
.monaco-editor .bracket-indent-guide.lvl-11 { --guide-color: rgba(135, 206, 250, 0.3); --guide-color-active: #87cefa; }
.monaco-editor .bracket-indent-guide.lvl-12 { --guide-color: rgba(255, 215, 0, 0.3); --guide-color-active: #ffd700; }
.monaco-editor .bracket-indent-guide.lvl-13 { --guide-color: rgba(218, 112, 214, 0.3); --guide-color-active: #da70d6; }
.monaco-editor .bracket-indent-guide.lvl-14 { --guide-color: rgba(135, 206, 250, 0.3); --guide-color-active: #87cefa; }
.monaco-editor .bracket-indent-guide.lvl-15 { --guide-color: rgba(255, 215, 0, 0.3); --guide-color-active: #ffd700; }
.monaco-editor .bracket-indent-guide.lvl-16 { --guide-color: rgba(218, 112, 214, 0.3); --guide-color-active: #da70d6; }
.monaco-editor .bracket-indent-guide.lvl-17 { --guide-color: rgba(135, 206, 250, 0.3); --guide-color-active: #87cefa; }
.monaco-editor .bracket-indent-guide.lvl-18 { --guide-color: rgba(255, 215, 0, 0.3); --guide-color-active: #ffd700; }
.monaco-editor .bracket-indent-guide.lvl-19 { --guide-color: rgba(218, 112, 214, 0.3); --guide-color-active: #da70d6; }
.monaco-editor .bracket-indent-guide.lvl-20 { --guide-color: rgba(135, 206, 250, 0.3); --guide-color-active: #87cefa; }
.monaco-editor .bracket-indent-guide.lvl-21 { --guide-color: rgba(255, 215, 0, 0.3); --guide-color-active: #ffd700; }
.monaco-editor .bracket-indent-guide.lvl-22 { --guide-color: rgba(218, 112, 214, 0.3); --guide-color-active: #da70d6; }
.monaco-editor .bracket-indent-guide.lvl-23 { --guide-color: rgba(135, 206, 250, 0.3); --guide-color-active: #87cefa; }
.monaco-editor .bracket-indent-guide.lvl-24 { --guide-color: rgba(255, 215, 0, 0.3); --guide-color-active: #ffd700; }
.monaco-editor .bracket-indent-guide.lvl-25 { --guide-color: rgba(218, 112, 214, 0.3); --guide-color-active: #da70d6; }
.monaco-editor .bracket-indent-guide.lvl-26 { --guide-color: rgba(135, 206, 250, 0.3); --guide-color-active: #87cefa; }
.monaco-editor .bracket-indent-guide.lvl-27 { --guide-color: rgba(255, 215, 0, 0.3); --guide-color-active: #ffd700; }
.monaco-editor .bracket-indent-guide.lvl-28 { --guide-color: rgba(218, 112, 214, 0.3); --guide-color-active: #da70d6; }
.monaco-editor .bracket-indent-guide.lvl-29 { --guide-color: rgba(135, 206, 250, 0.3); --guide-color-active: #87cefa; }
.monaco-editor .vertical { box-shadow: 1px 0 0 0 var(--guide-color) inset; }
.monaco-editor .horizontal-top { border-top: 1px solid var(--guide-color); }
.monaco-editor .horizontal-bottom { border-bottom: 1px solid var(--guide-color); }
.monaco-editor .vertical.indent-active { box-shadow: 1px 0 0 0 var(--guide-color-active) inset; }
.monaco-editor .horizontal-top.indent-active { border-top: 1px solid var(--guide-color-active); }
.monaco-editor .horizontal-bottom.indent-active { border-bottom: 1px solid var(--guide-color-active); }
.monaco-editor .minimap-slider .minimap-slider-horizontal { background: rgba(27, 50, 79, 0.5); }
.monaco-editor .minimap-slider:hover .minimap-slider-horizontal { background: rgba(27, 50, 79, 0.5); }
.monaco-editor .minimap-slider.active .minimap-slider-horizontal { background: rgba(27, 50, 79, 0.5); }
.monaco-editor .view-ruler { box-shadow: 1px 0 0 0 #ffffff inset; }
.monaco-editor .focused .selected-text { background-color: #f3f518; }
.monaco-editor .selected-text { background-color: rgba(243, 245, 24, 0.5); }
.monaco-editor .view-line span.inline-selected-text { color: #000000; }
.monaco-editor .cursors-layer .cursor { background-color: #833ae0; border-color: #833ae0; color: #7cc51f; }
.monaco-editor .cursors-layer.has-selection .cursor { border-left: 1px solid #7cc51f; border-right: 1px solid #7cc51f; }
.monaco-editor .squiggly-error { border-bottom: 4px double rgba(228, 119, 119, 0.8); }
.monaco-editor .squiggly-warning { border-bottom: 4px double rgba(255, 204, 0, 0.8); }
.monaco-editor .squiggly-info { border-bottom: 4px double rgba(55, 148, 255, 0.8); }
.monaco-editor .squiggly-info { background: url("data:image/svg+xml,%3Csvg%20xmlns%3D'http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg'%20viewBox%3D'0%200%206%203'%20enable-background%3D'new%200%200%206%203'%20height%3D'3'%20width%3D'6'%3E%3Cg%20fill%3D'%233794ff'%3E%3Cpolygon%20points%3D'5.5%2C0%202.5%2C3%201.1%2C3%204.1%2C0'%2F%3E%3Cpolygon%20points%3D'4%2C0%206%2C2%206%2C0.6%205.4%2C0'%2F%3E%3Cpolygon%20points%3D'0%2C2%201%2C3%202.4%2C3%200%2C0.6'%2F%3E%3C%2Fg%3E%3C%2Fsvg%3E") repeat-x bottom left; }
.monaco-editor .squiggly-hint { border-bottom: 2px dotted rgba(238, 238, 238, 0.8); }
.monaco-editor.showUnused .squiggly-unnecessary { border-bottom: 2px dashed rgba(255, 255, 255, 0.8); }
.monaco-editor.showDeprecated .squiggly-inline-deprecated { text-decoration: line-through; text-decoration-color: #ffffff}
.monaco-editor .reference-zone-widget .preview .reference-decoration { border: 2px solid #f38518; box-sizing: border-box; }
.monaco-editor .reference-zone-widget .ref-tree .referenceMatch .highlight { border: 1px dotted #f38518; box-sizing: border-box; }
.monaco-editor .reference-zone-widget .ref-tree { background-color: #000000; }
.monaco-editor .reference-zone-widget .ref-tree { color: #ffffff; }
.monaco-editor .reference-zone-widget .ref-tree .reference-file { color: #ffffff; }
.monaco-editor .reference-zone-widget .ref-tree .monaco-list:focus .monaco-list-rows > .monaco-list-row.selected:not(.highlighted) { color: #ffffff !important; }
.monaco-editor .reference-zone-widget .preview .monaco-editor .monaco-editor-background,.monaco-editor .reference-zone-widget .preview .monaco-editor .inputarea.ime-input {	background-color: #000000;}
.monaco-editor .reference-zone-widget .preview .monaco-editor .margin {	background-color: #000000;}
.monaco-editor .goto-definition-link { color: #00ffff !important; }

			.monaco-editor .zone-widget .codicon.codicon-info,
			.markers-panel .marker-icon.codicon.codicon-info,
			.extensions-viewlet > .extensions .codicon.codicon-info,
			.text-search-provider-messages .providerMessage .codicon.codicon-info,
			.extension-editor .codicon.codicon-info {
				color: #3794ff;
			}
		
.monaco-editor .marker-widget a.code-link span { color: #3794ff; }
.monaco-editor .marker-widget a.code-link span:hover { color: #3794ff; }
.monaco-hover .hover-contents a.code-link span { color: #3794ff; }
.monaco-hover .hover-contents a.code-link span:hover { color: #3794ff; }
.monaco-editor .snippet-placeholder { background-color: rgba(124, 124, 124, 0.3); outline-color: transparent; }
.monaco-editor .finish-snippet-placeholder { background-color: transparent; outline-color: #525252; }
.codicon.codicon-symbol-array { color: #ffffff; }
.codicon.codicon-symbol-boolean { color: #ffffff; }
.codicon.codicon-symbol-class { color: #ee9d28; }
.codicon.codicon-symbol-method { color: #b180d7; }
.codicon.codicon-symbol-color { color: #ffffff; }
.codicon.codicon-symbol-constant { color: #ffffff; }
.codicon.codicon-symbol-constructor { color: #b180d7; }

			.codicon.codicon-symbol-value,.codicon.codicon-symbol-enum { color: #ee9d28; }
.codicon.codicon-symbol-enum-member { color: #75beff; }
.codicon.codicon-symbol-event { color: #ee9d28; }
.codicon.codicon-symbol-field { color: #75beff; }
.codicon.codicon-symbol-file { color: #ffffff; }
.codicon.codicon-symbol-folder { color: #ffffff; }
.codicon.codicon-symbol-function { color: #b180d7; }
.codicon.codicon-symbol-interface { color: #75beff; }
.codicon.codicon-symbol-key { color: #ffffff; }
.codicon.codicon-symbol-keyword { color: #ffffff; }
.codicon.codicon-symbol-module { color: #ffffff; }
.codicon.codicon-symbol-namespace { color: #ffffff; }
.codicon.codicon-symbol-null { color: #ffffff; }
.codicon.codicon-symbol-number { color: #ffffff; }
.codicon.codicon-symbol-object { color: #ffffff; }
.codicon.codicon-symbol-operator { color: #ffffff; }
.codicon.codicon-symbol-package { color: #ffffff; }
.codicon.codicon-symbol-property { color: #ffffff; }
.codicon.codicon-symbol-reference { color: #ffffff; }
.codicon.codicon-symbol-snippet { color: #ffffff; }
.codicon.codicon-symbol-string { color: #ffffff; }
.codicon.codicon-symbol-struct { color: #ffffff; }
.codicon.codicon-symbol-text { color: #ffffff; }
.codicon.codicon-symbol-type-parameter { color: #ffffff; }
.codicon.codicon-symbol-unit { color: #ffffff; }
.codicon.codicon-symbol-variable { color: #75beff; }
.monaco-editor .suggest-widget .monaco-list .monaco-list-row .monaco-highlighted-label .highlight { color: #f38518; }
.monaco-editor .suggest-widget .monaco-list .monaco-list-row.focused .monaco-highlighted-label .highlight { color: #f38518; }
.monaco-editor .suggest-widget, .monaco-editor .suggest-details { color: #ffffff; }
.monaco-editor .suggest-details a { color: #3794ff; }
.monaco-editor .suggest-details a:hover { color: #3794ff; }
.monaco-editor .suggest-details code { background-color: #000000; }
.monaco-editor .suggest-preview-text .ghost-text { border: 1px solid rgba(255, 255, 255, 0.8); }
.monaco-editor .ghost-text-decoration { border: 1px solid rgba(255, 255, 255, 0.8); }
.monaco-editor .ghost-text-decoration-preview { border: 1px solid rgba(255, 255, 255, 0.8); }
.monaco-editor .hoverHighlight { background-color: rgba(173, 214, 255, 0.15); }
.monaco-editor .monaco-hover { background-color: #0c141f; }
.monaco-editor .monaco-hover { border: 1px solid #6fc3df; }
.monaco-editor .monaco-hover .hover-row:not(:first-child):not(:empty) { border-top: 1px solid rgba(111, 195, 223, 0.5); }
.monaco-editor .monaco-hover hr { border-top: 1px solid rgba(111, 195, 223, 0.5); }
.monaco-editor .monaco-hover hr { border-bottom: 0px solid rgba(111, 195, 223, 0.5); }
.monaco-editor .monaco-hover a { color: #3794ff; }
.monaco-editor .monaco-hover a:hover { color: #3794ff; }
.monaco-editor .monaco-hover { color: #ffffff; }
.monaco-editor .monaco-hover .hover-row .actions { background-color: #0c141f; }
.monaco-editor .monaco-hover code { background-color: #000000; }
.monaco-editor .findOptionsWidget { background-color: #0c141f; }
.monaco-editor .findOptionsWidget { color: #ffffff; }
.monaco-editor .findOptionsWidget { border: 2px solid #6fc3df; }
.monaco-editor .find-widget { background-color: #0c141f; }
.monaco-editor .findMatch { border: 1px dotted #f38518; box-sizing: border-box; }
.monaco-editor .currentFindMatch { border: 2px solid #f38518; padding: 1px; box-sizing: border-box; }
.monaco-editor .findScope { border: 1px dashed rgba(243, 133, 24, 0.4); }
.monaco-editor .find-widget { border: 1px solid #6fc3df; }
.monaco-editor .find-widget { color: #ffffff; }
.monaco-editor .find-widget.no-results .matchesCount { color: #f48771; }
.monaco-editor .find-widget .monaco-sash { background-color: #6fc3df; }
.monaco-editor .find-widget .monaco-inputbox.synthetic-focus { outline-color: #f38518; }

		.monaco-editor .cldr.codicon.codicon-folding-expanded,
		.monaco-editor .cldr.codicon.codicon-folding-collapsed {
			color: #ffffff !important;
		}
		
.monaco-editor.vs .valueSetReplacement { outline: solid 2px #6fc3df; }
.monaco-editor .tokens-inspect-widget { border: 2px solid #6fc3df; }
.monaco-editor .tokens-inspect-widget .tokens-inspect-separator { background-color: #6fc3df; }
.monaco-editor .tokens-inspect-widget { background-color: #0c141f; }
.monaco-editor .tokens-inspect-widget { color: #ffffff; }
.monaco-editor .linked-editing-decoration { background: rgba(255, 0, 0, 0.3); border-left-color: rgba(255, 0, 0, 0.3); }
.monaco-editor .detected-link-active { color: #00ffff !important; }
.monaco-editor .parameter-hints-widget { border: 2px solid #6fc3df; }
.monaco-editor .parameter-hints-widget.multiple .body { border-left: 1px solid rgba(111, 195, 223, 0.5); }
.monaco-editor .parameter-hints-widget .signature.has-docs { border-bottom: 1px solid rgba(111, 195, 223, 0.5); }
.monaco-editor .parameter-hints-widget { background-color: #0c141f; }
.monaco-editor .parameter-hints-widget a { color: #3794ff; }
.monaco-editor .parameter-hints-widget a:hover { color: #3794ff; }
.monaco-editor .parameter-hints-widget { color: #ffffff; }
.monaco-editor .parameter-hints-widget code { background-color: #000000; }
.monaco-editor .parameter-hints-widget .parameter.active { color: #f38518}
.monaco-editor .selectionHighlight { border: 1px dotted #f38518; box-sizing: border-box; }
.monaco-editor .wordHighlight { border: 1px dashed #f38518; box-sizing: border-box; }
.monaco-editor .wordHighlightStrong { border: 1px dashed #f38518; box-sizing: border-box; }
.monaco-diff-editor .diff-review-line-number { color: #ffffff; }
.monaco-editor .line-insert, .monaco-editor .char-insert { border: 1px dashed #33ff2e; }
.monaco-editor .line-delete, .monaco-editor .char-delete { border: 1px dashed #ff008f; }
.monaco-diff-editor.side-by-side .editor.modified { border-left: 1px solid #6fc3df; }

			.monaco-diff-editor .diffViewport {
				background: #1b324f;
			}
		

			.monaco-diff-editor .diffViewport:hover {
				background: #1b324f;
			}
		

			.monaco-diff-editor .diffViewport:active {
				background: #1b324f;
			}
		

	.monaco-editor .diagonal-fill {
		background-image: linear-gradient(
			-45deg,
			undefined 12.5%,
			#0000 12.5%, #0000 50%,
			undefined 50%, undefined 62.5%,
			#0000 62.5%, #0000 100%
		);
		background-size: 8px 8px;
	}
	

.mtk1 { color: #ffffff; }
.mtk2 { color: #0f1c2c; }
.mtk3 { color: #569cd6; }
.mtk4 { color: #3ff23f; }
.mtk5 { color: #608b4e; }
.mtk6 { color: #ffff00; }
.mtk7 { color: #f44747; }
.mtk8 { color: #9cdcfe; }
.mtk9 { color: #c586c0; }
.mtk10 { color: #d4d4d4; }
.mtk11 { color: #ce9178; }
.mtk12 { color: #1aebff; }
.mtk13 { color: #778899; }
.mtk14 { color: #909090; }
.mtk15 { color: #ff00ff; }
.mtk16 { color: #c0c0c0; }
.mtk17 { color: #ff0000; }
.mtk18 { color: #4f76ac; }
.mtk19 { color: #3dc9b0; }
.mtki { font-style: italic; }
.mtkb { font-weight: bold; }
.mtku { text-decoration: underline; text-underline-position: under; }</style><style type="text/css" media="screen"></style><link rel="shortcut icon" href="https://learn.logikaschool.com/uploads/2021/11/favicon_ukr_1_1635800618.svg?t=1635800618" data-react-helmet="true"><style type="text/css" media="screen">
		.monaco-editor .codelens-decoration._1cd5ccef { line-height: 19px; font-size: 12px; padding-right: 6px; font-feature-settings: var(--codelens-font-features_1cd5ccef) }
		.monaco-editor .codelens-decoration._1cd5ccef span.codicon { line-height: 19px; font-size: 12px; }
		</style><style type="text/css" media="screen">
		.monaco-editor .codelens-decoration._1cd5ccf0 { line-height: 19px; font-size: 12px; padding-right: 6px; font-feature-settings: var(--codelens-font-features_1cd5ccf0) }
		.monaco-editor .codelens-decoration._1cd5ccf0 span.codicon { line-height: 19px; font-size: 12px; }
		</style><style type="text/css" media="screen">
		.monaco-editor .codelens-decoration._1cd5ccf1 { line-height: 19px; font-size: 12px; padding-right: 6px; font-feature-settings: var(--codelens-font-features_1cd5ccf1) }
		.monaco-editor .codelens-decoration._1cd5ccf1 span.codicon { line-height: 19px; font-size: 12px; }
		</style></head><body class="notranslate"><noscript>You need to enable JavaScript to run this app.</noscript><noscript><iframe src="https://www.googletagmanager.com/ns.html?id=GTM-K7488WV" height="0" width="0" style="display:none;visibility:hidden"></iframe></noscript><div id="root"><div class="Container__Wrapper-sc-n9rvj1 hERApw"><div class="Container__Container-sc-ceq6gi jwISbR"><div class="LogoWrapper__LogoWrapper-sc-fqd6fh eGLdts"><img src="./lesson_files/ukr_logo_sign_inverse_0_1635840263.svg" alt="" class="Image__Image-sc-1fpogts hZdkST"><button class="Button__Button-sc-1q1rcy1 xKOtJ"><svg width="36" height="36" viewBox="0 0 37 36" fill="none" xmlns="http://www.w3.org/2000/svg"><rect x="0.631" width="36" height="36" rx="6" fill="#fff"></rect><path d="M24.643 16.382h-9.746l4.248-4.248a1.25 1.25 0 00-1.768-1.768l-6.38 6.381a1.259 1.259 0 000 1.77l6.38 6.38c.244.244.563.366.884.366a1.25 1.25 0 00.884-2.134l-4.248-4.247h9.746a1.25 1.25 0 000-2.5z" fill="#292929"></path></svg></button></div><div class="Wrapper__Wrapper-sc-1yifxxs hEuepV"><div class="Wrapper__Wrapper-sc-10kodht bGXubZ"><span class="Text__Text-sc-76hp2j ELqyw">Відео на сайті</span><svg width="7" height="5" xmlns="http://www.w3.org/2000/svg" x="0" y="0" viewBox="0 0 6 5" xml:space="preserve" class="TriangleIcon__TriangleIcon-sc-bsty49 lcWsGK"><path fill="#FFF" d="M5.1 0H1C.2 0-.3.9.2 1.6l2 2.8c.4.5 1.2.5 1.6 0l2-2.8C6.4.9 5.9 0 5.1 0z"></path></svg></div></div><div class="styles__LevelsWrapper-sc-2tiv95 eOVDhw"><div class="CarouselProvider__Wrapper-sc-oynoox gOJOaS"><div class="Slider__Wrapper-sc-1csluuf dzuFre"><div class="Slider__VisibleSlidesWrapper-sc-1sjy6xj jOgAPN"><div class="Slider__AnimatedWrapper-sc-1tr05af gVghHk"><div class="Slide__Wrapper-sc-8ntm9q kvwGmb"></div><div class="Slide__Wrapper-sc-8ntm9q jHzXOC"><div id="1" data-qa-level-status="complete" data-qa-is-bonus-level="false" data-qa-is-active-level="false" data-qa-level-type="comics" class="Wrapper__Wrapper-sc-t3p8sk esdExu"><a class="Link__Link-sc-1k1sgz0 dCgXtm" href="https://learn.logikaschool.com/lesson?lesson=14857&amp;level=1&amp;task=34109"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 22 22" height="22px" width="22px" style="color: rgb(15, 28, 44);"><path fill="currentColor" d="M16.686 4.787h-12c-.55 0-1 .45-1 1v10.008h.002a1 1 0 00.998.992h12c.547 0 .994-.446.998-.992h.002V5.787c0-.55-.45-1-1-1zM14.5 10.921a.829.829 0 00-1.224 0l-1.367 1.494-2.987-3.437a.909.909 0 00-1.368 0l-2.87 3.282V5.787h12v7.53L14.5 10.921z"></path></svg></a></div></div><div class="Slide__Wrapper-sc-8ntm9q jHzXOC"><div id="2" data-qa-level-status="attempted" data-qa-is-bonus-level="false" data-qa-is-active-level="true" data-qa-level-type="js" class="Wrapper__Wrapper-sc-t3p8sk eYMlUG"><a class="Link__Link-sc-1k1sgz0 bgqfwG" href="https://learn.logikaschool.com/lesson?lesson=14857&amp;level=2&amp;task=34109">1</a></div></div><div class="Slide__Wrapper-sc-8ntm9q jHzXOC"><div id="3" data-qa-level-status="complete" data-qa-is-bonus-level="false" data-qa-is-active-level="false" data-qa-level-type="html" class="Wrapper__Wrapper-sc-t3p8sk esdExu"><a class="Link__Link-sc-1k1sgz0 dCgXtm" href="https://learn.logikaschool.com/lesson?lesson=14857&amp;level=3&amp;task=34109"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 22 22" height="22px" width="22px" style="color: rgb(15, 28, 44);"><path fill="currentColor" d="M15.973 6.08l-1.586-1.586c-.389-.389-1.157-.707-1.707-.707h-7c-.55 0-1 .45-1 1v12c0 .55.45 1 1 1h10c.55 0 1-.45 1-1v-9c0-.55-.318-1.318-.707-1.707zm-5.293 8.207H6.812v-1h3.868v1zm3.868-2.342H6.812v-1h7.736v1zm0-2.342H6.812v-1h7.736v1z"></path></svg></a></div></div><div class="Slide__Wrapper-sc-8ntm9q jHzXOC"><div id="4" data-qa-level-status="complete" data-qa-is-bonus-level="false" data-qa-is-active-level="false" data-qa-level-type="html" class="Wrapper__Wrapper-sc-t3p8sk esdExu"><a class="Link__Link-sc-1k1sgz0 dCgXtm" href="https://learn.logikaschool.com/lesson?lesson=14857&amp;level=4&amp;task=34109"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 22 22" height="22px" width="22px" style="color: rgb(15, 28, 44);"><path fill="currentColor" d="M15.973 6.08l-1.586-1.586c-.389-.389-1.157-.707-1.707-.707h-7c-.55 0-1 .45-1 1v12c0 .55.45 1 1 1h10c.55 0 1-.45 1-1v-9c0-.55-.318-1.318-.707-1.707zm-5.293 8.207H6.812v-1h3.868v1zm3.868-2.342H6.812v-1h7.736v1zm0-2.342H6.812v-1h7.736v1z"></path></svg></a></div></div><div class="Slide__Wrapper-sc-8ntm9q jHzXOC"><div id="5" data-qa-level-status="complete" data-qa-is-bonus-level="false" data-qa-is-active-level="false" data-qa-level-type="html" class="Wrapper__Wrapper-sc-t3p8sk esdExu"><a class="Link__Link-sc-1k1sgz0 dCgXtm" href="https://learn.logikaschool.com/lesson?lesson=14857&amp;level=5&amp;task=34109"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 22 22" height="22px" width="22px" style="color: rgb(15, 28, 44);"><path fill="currentColor" d="M15.973 6.08l-1.586-1.586c-.389-.389-1.157-.707-1.707-.707h-7c-.55 0-1 .45-1 1v12c0 .55.45 1 1 1h10c.55 0 1-.45 1-1v-9c0-.55-.318-1.318-.707-1.707zm-5.293 8.207H6.812v-1h3.868v1zm3.868-2.342H6.812v-1h7.736v1zm0-2.342H6.812v-1h7.736v1z"></path></svg></a></div></div><div class="Slide__Wrapper-sc-8ntm9q jHzXOC"><div id="6" data-qa-level-status="complete" data-qa-is-bonus-level="false" data-qa-is-active-level="false" data-qa-level-type="html" class="Wrapper__Wrapper-sc-t3p8sk esdExu"><a class="Link__Link-sc-1k1sgz0 dCgXtm" href="https://learn.logikaschool.com/lesson?lesson=14857&amp;level=6&amp;task=34109"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 22 22" height="22px" width="22px" style="color: rgb(15, 28, 44);"><path fill="currentColor" d="M15.973 6.08l-1.586-1.586c-.389-.389-1.157-.707-1.707-.707h-7c-.55 0-1 .45-1 1v12c0 .55.45 1 1 1h10c.55 0 1-.45 1-1v-9c0-.55-.318-1.318-.707-1.707zm-5.293 8.207H6.812v-1h3.868v1zm3.868-2.342H6.812v-1h7.736v1zm0-2.342H6.812v-1h7.736v1z"></path></svg></a></div></div><div class="Slide__Wrapper-sc-8ntm9q jHzXOC"><div id="7" data-qa-level-status="complete" data-qa-is-bonus-level="false" data-qa-is-active-level="false" data-qa-level-type="html" class="Wrapper__Wrapper-sc-t3p8sk esdExu"><a class="Link__Link-sc-1k1sgz0 dCgXtm" href="https://learn.logikaschool.com/lesson?lesson=14857&amp;level=7&amp;task=34109"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 22 22" height="22px" width="22px" style="color: rgb(15, 28, 44);"><path fill="currentColor" d="M15.973 6.08l-1.586-1.586c-.389-.389-1.157-.707-1.707-.707h-7c-.55 0-1 .45-1 1v12c0 .55.45 1 1 1h10c.55 0 1-.45 1-1v-9c0-.55-.318-1.318-.707-1.707zm-5.293 8.207H6.812v-1h3.868v1zm3.868-2.342H6.812v-1h7.736v1zm0-2.342H6.812v-1h7.736v1z"></path></svg></a></div></div><div class="Slide__Wrapper-sc-8ntm9q jHzXOC"><div id="8" data-qa-level-status="student_success" data-qa-is-bonus-level="false" data-qa-is-active-level="false" data-qa-level-type="js" class="Wrapper__Wrapper-sc-t3p8sk esdExu"><a class="Link__Link-sc-1k1sgz0 dCgXtm" href="https://learn.logikaschool.com/lesson?lesson=14857&amp;level=8&amp;task=34109">2</a></div></div><div class="Slide__Wrapper-sc-8ntm9q jHzXOC"><div id="9" data-qa-level-status="complete" data-qa-is-bonus-level="false" data-qa-is-active-level="false" data-qa-level-type="rating" class="Wrapper__Wrapper-sc-t3p8sk esdExu"><a class="Link__Link-sc-1k1sgz0 dCgXtm" href="https://learn.logikaschool.com/lesson?lesson=14857&amp;level=9&amp;task=34109"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 22 22" height="22px" width="22px" style="color: rgb(15, 28, 44);"><path fill="currentColor" d="M11.431 2.787a8 8 0 10.001 16 8 8 0 000-16zm2.377 5.376a.867.867 0 110 1.734.867.867 0 010-1.734zm-4.855 0a.867.867 0 110 1.734.867.867 0 010-1.734zm6.406 4.655a5.106 5.106 0 01-4.03 1.965 5.106 5.106 0 01-3.804-1.694.52.52 0 01.774-.695 4.062 4.062 0 003.03 1.35c1.27 0 2.443-.584 3.211-1.566a.52.52 0 01.82.64z"></path></svg></a></div></div><div class="Slide__Wrapper-sc-8ntm9q jHzXOC"><div id="10" data-qa-level-status="complete" data-qa-is-bonus-level="true" data-qa-is-active-level="false" data-qa-level-type="finish" class="Wrapper__Wrapper-sc-t3p8sk esdExu"><a class="Link__Link-sc-1k1sgz0 dOVbVN" href="https://learn.logikaschool.com/lesson?lesson=14857&amp;level=10&amp;task=34109"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 22 22" height="22px" width="22px" style="color: rgb(15, 28, 44);"><path fill="currentColor" d="M4.578 5.787a1 1 0 011-1h2a1 1 0 011 1v3h-3a1 1 0 01-1-1v-2zm4 3h4v4h-4v-4zm4-3a1 1 0 011-1h2a1 1 0 011 1v2a1 1 0 01-1 1h-3v-3zm-8 8a1 1 0 011-1h3v3a1 1 0 01-1 1h-2a1 1 0 01-1-1v-2zm8-1h3a1 1 0 011 1v2a1 1 0 01-1 1h-2a1 1 0 01-1-1v-3z"></path></svg></a></div></div><div class="Slide__Wrapper-sc-8ntm9q kvwGmb"></div></div><div class="ButtonBase__ButtonBase-sc-ekd08w ButtonPrev__Button-sc-1jdygwt dsJmaK"><svg width="26" height="27" viewBox="0 0 26 27" fill="none" xmlns="http://www.w3.org/2000/svg"><rect x="26" y="26.25" width="26" height="26" rx="13" transform="rotate(-180 26 26.25)"></rect><path d="M16.125 17.286V9.214a1 1 0 00-1.588-.809l-5.55 4.036a1 1 0 000 1.618l5.55 4.036a1 1 0 001.588-.809z" fill="#fff"></path></svg></div><div class="ButtonBase__ButtonBase-sc-ekd08w gaAvQI"><svg width="26" height="27" viewBox="0 0 26 27" fill="none" xmlns="http://www.w3.org/2000/svg"><rect y="0.25" width="26" height="26" rx="13"></rect><path d="M9.875 9.214v8.072a1 1 0 001.588.809l5.55-4.036a1 1 0 000-1.618l-5.55-4.036a1 1 0 00-1.588.809z" fill="#fff"></path></svg></div></div></div></div></div><div class="Wrapper__Wrapper-sc-1sc76em fdLLVx"></div><div class="styles__MashHelpWrapper-sc-hflh9m bWdfCs"></div><div class="styles__MarsogramWrapper-sc-iujcxh bYOOUM"><div class="Marsogram__Wrapper-sc-14a6eed hwzKnN"><button type="button" class="styles__StyledButton-sc-14qfyw1 ihiscp Button__StyledButton-sc-1y2g5eb bCVdoH" data-qa-id="marsogram-button" kind="technical"><svg viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" height="24px" width="24px"><mask id="chat_svg__a" maskUnits="userSpaceOnUse" x="0" y="0" width="24" height="24" fill="#000"><path fill="#fff" d="M0 0h24v24H0z"></path><path d="M20.08 4.03C18.968 3.06 16.3 2.02 12.16 2h-.146c-.973 0-5.94.101-8.13 2.107C2.663 5.33 2.068 7.151 2.013 9.845l-.008.264c-.052 2.303.304 6.648 4.278 7.997-.005.867-.474 2.779-.474 3 0 .23.099.703.473.85A.65.65 0 006.52 22c.216 0 .437-.101.622-.29.562-.57 2.104-2.433 2.618-3.058.32.014.667.024 1.04.024 2.701 0 6.183-.418 6.495-.52.046-.014.113-.028.197-.05.942-.222 3.804-.895 4.318-5.086.54-4.36-.077-7.553-1.729-8.99z"></path></mask><path d="M20.08 4.03C18.968 3.06 16.3 2.02 12.16 2h-.146c-.973 0-5.94.101-8.13 2.107C2.663 5.33 2.068 7.151 2.013 9.845l-.008.264c-.052 2.303.304 6.648 4.278 7.997-.005.867-.474 2.779-.474 3 0 .23.099.703.473.85A.65.65 0 006.52 22c.216 0 .437-.101.622-.29.562-.57 2.104-2.433 2.618-3.058.32.014.667.024 1.04.024 2.701 0 6.183-.418 6.495-.52.046-.014.113-.028.197-.05.942-.222 3.804-.895 4.318-5.086.54-4.36-.077-7.553-1.729-8.99z" stroke="currentColor" stroke-width="3" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round" mask="url(#chat_svg__a)"></path><path d="M7 8h10M7 10.5h10M7 13h6.429" stroke="currentColor" stroke-width="1.5" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"></path></svg></button></div></div><div class="styles__Wrapper-sc-1or50x2 ckQnqd"><div class="styles__Content-sc-u0vbn8 loRtzv"><div data-qa-userinfo-avatar="true" class="styles__Wrapper-sc-1kcpt6z fjmoNf"><img src="./lesson_files/1215051.svg" class="styles__Image-sc-f4cqpr hfyrcE"></div><div class="styles__Info-sc-1y0y0my iWQKSQ"><span class="styles__UserName-sc-11ebil7 ipRoUA">Кузик Богдан</span></div><div class="styles__Arrow-sc-jn5a9e cHRmsn"><svg width="16" height="16" viewBox="0 0 16 16" fill="currentColor" stroke="currentColor" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" clip-rule="evenodd" d="M14.783 5.216c.29.288.29.756 0 1.044l-5.732 5.697-1.05 1.044-6.784-6.74a.734.734 0 010-1.044.747.747 0 011.052 0L8 10.912l5.732-5.695a.747.747 0 011.051 0z" stroke="none"></path></svg></div></div></div></div><div class="Wrapper__Wrapper-sc-1kvwfj kQVJuZ"><div class="Toolbar__Wrapper-sc-11yl07x bDMOOb"><div class="Buttons__Button-sc-kk39lf hrPWyE"><svg viewBox="1 0 19 19" xmlns="http://www.w3.org/2000/svg" height="22px" width="22px" style="color: rgb(255, 255, 255);"><path fill="currentColor" d="M9.245 16.267l7.823-5.223a2 2 0 000-3.327L9.245 2.494c-1.329-.887-3.11.066-3.11 1.664v10.445c0 1.598 1.781 2.55 3.11 1.664z"></path></svg></div><div class="Buttons__Button-sc-kk39lf hrPWyE"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 22 22" height="22px" width="22px" style="color: rgb(255, 255, 255);"><path fill="currentColor" fill-rule="evenodd" d="M11.292 8.22a3.078 3.078 0 100 6.155 3.078 3.078 0 000-6.156zm-5.378 3.077a5.378 5.378 0 1110.756 0 5.378 5.378 0 01-10.756 0zM11.293.798c.635 0 1.15.515 1.15 1.15v1.809a1.15 1.15 0 11-2.3 0V1.948c0-.635.514-1.15 1.15-1.15zm0 16.891c.635 0 1.15.514 1.15 1.15v1.808a1.15 1.15 0 11-2.3 0v-1.809c0-.635.514-1.15 1.15-1.15zm-10.5-6.391c0-.635.515-1.15 1.15-1.15h1.81a1.15 1.15 0 110 2.3h-1.81a1.15 1.15 0 01-1.15-1.15zm16.89 0c0-.635.515-1.15 1.15-1.15h1.81a1.15 1.15 0 010 2.3h-1.81a1.15 1.15 0 01-1.15-1.15zM3.868 3.874a1.15 1.15 0 011.626 0l1.28 1.278a1.15 1.15 0 01-1.626 1.627L3.868 5.5a1.15 1.15 0 010-1.626zm11.943 11.943a1.15 1.15 0 011.626 0l1.28 1.28a1.15 1.15 0 11-1.626 1.626l-1.28-1.28a1.15 1.15 0 010-1.626zm-9.037-.001a1.15 1.15 0 010 1.626l-1.28 1.28a1.15 1.15 0 01-1.625-1.626l1.28-1.28a1.15 1.15 0 011.625 0zM18.717 3.874a1.15 1.15 0 010 1.626l-1.28 1.279a1.15 1.15 0 01-1.626-1.627l1.28-1.279a1.15 1.15 0 011.626 0z" clip-rule="evenodd"></path></svg></div></div><div class="Layout__Wrapper-sc-13ruc5r fmoIbV"><div class="splitter-layout"><div class="layout-pane layout-pane-primary"><div class="Layout__Tabs-sc-ptgudx jFZfth"><div id="html" class="Layout__Tab-sc-x9wnbn Layout__EditorTab-sc-df4hmh dxuEMO algo-tab">HTML</div><div id="css" class="Layout__Tab-sc-x9wnbn Layout__EditorTab-sc-df4hmh SmfkH algo-tab">CSS</div></div><div class="Layout__Pane-sc-nh0up0 hnXvzm"><div class="Layout__MonacoWrapper-sc-1vrgfzp kTVSQC"><div class=" monaco-break-points-disabled monaco-editor-wrapper" style="height: 100%; width: 100%; --codelens-font-features_1cd5ccef:&quot;liga&quot; off, &quot;calt&quot; off;" data-keybinding-context="10" data-mode-id="html"><div class="monaco-editor no-user-select  showUnused showDeprecated hc-black" role="code" data-uri="inmemory://model/10" style="width: 708px; height: 588px;"><div data-mprt="3" class="overflow-guard" style="width: 708px; height: 588px;"><div class="margin" role="presentation" aria-hidden="true" style="position: absolute; transform: translate3d(0px, 0px, 0px); contain: strict; top: 0px; height: 588px; width: 83px;"><div class="glyph-margin" style="left: 0px; width: 19px; height: 588px;"></div><div class="margin-view-zones" role="presentation" aria-hidden="true" style="position: absolute;"></div><div class="margin-view-overlays" role="presentation" aria-hidden="true" style="position: absolute; width: 83px; font-family: Consolas, &quot;Courier New&quot;, monospace; font-weight: normal; font-size: 14px; font-feature-settings: &quot;liga&quot; 0, &quot;calt&quot; 0; line-height: 19px; letter-spacing: 0px; height: 683px;"><div style="position:absolute;top:0px;width:100%;height:19px;"><div class="current-line" style="width:83px; height:19px;"></div><div class="cldr codicon codicon-folding-expanded" style="left:57px;width:26px;"></div><div class="active-line-number line-numbers" style="left:19px;width:38px;">1</div></div><div style="position:absolute;top:19px;width:100%;height:19px;"><div class="line-numbers" style="left:19px;width:38px;">2</div></div><div style="position:absolute;top:38px;width:100%;height:19px;"><div class="line-numbers" style="left:19px;width:38px;">3</div></div><div style="position:absolute;top:57px;width:100%;height:19px;"><div class="line-numbers" style="left:19px;width:38px;">4</div></div><div style="position:absolute;top:76px;width:100%;height:19px;"><div class="line-numbers" style="left:19px;width:38px;">5</div></div><div style="position:absolute;top:95px;width:100%;height:19px;"><div class="line-numbers" style="left:19px;width:38px;">6</div></div></div></div><div class="monaco-scrollable-element editor-scrollable hc-black" role="presentation" data-mprt="5" style="position: absolute; overflow: hidden; left: 83px; width: 625px; height: 588px;"><div class="lines-content monaco-editor-background" style="position: absolute; overflow: hidden; width: 1e+06px; height: 1e+06px; transform: translate3d(0px, 0px, 0px); contain: strict; top: 0px; left: 0px;"><div class="view-overlays" role="presentation" aria-hidden="true" style="position: absolute; height: 0px; width: 625px;"><div style="position:absolute;top:0px;width:100%;height:19px;"></div><div style="position:absolute;top:19px;width:100%;height:19px;"><div class="core-guide core-guide-indent-active vertical" style="left:0px;height:19px;width:7.69921875px"></div></div><div style="position:absolute;top:38px;width:100%;height:19px;"><div class="core-guide core-guide-indent-active vertical" style="left:0px;height:19px;width:7.69921875px"></div></div><div style="position:absolute;top:57px;width:100%;height:19px;"><div class="core-guide core-guide-indent-active vertical" style="left:0px;height:19px;width:7.69921875px"></div></div><div style="position:absolute;top:76px;width:100%;height:19px;"><div class="core-guide core-guide-indent-active vertical" style="left:0px;height:19px;width:7.69921875px"></div></div><div style="position:absolute;top:95px;width:100%;height:19px;"></div></div><div role="presentation" aria-hidden="true" class="view-rulers"></div><div class="view-zones" role="presentation" aria-hidden="true" style="position: absolute;"></div><div class="view-lines monaco-mouse-cursor-text" role="presentation" aria-hidden="true" data-mprt="7" style="position: absolute; font-family: Consolas, &quot;Courier New&quot;, monospace; font-weight: normal; font-size: 14px; font-feature-settings: &quot;liga&quot; 0, &quot;calt&quot; 0; line-height: 19px; letter-spacing: 0px; width: 625px; height: 683px;"><div style="top:0px;height:19px;" class="view-line"><span><span class="mtk6">&lt;</span><span class="mtk3">html</span><span class="mtk6">&gt;</span></span></div><div style="top:19px;height:19px;" class="view-line"><span><span class="mtk1">&nbsp;&nbsp;&nbsp;&nbsp;</span><span class="mtk6">&lt;</span><span class="mtk3">h1</span><span class="mtk6">&gt;</span><span class="mtk1">Новини&nbsp;веб-дизайну</span><span class="mtk6">&lt;/</span><span class="mtk3">h1</span><span class="mtk6">&gt;</span></span></div><div style="top:38px;height:19px;" class="view-line"><span><span class="mtk1">&nbsp;&nbsp;&nbsp;&nbsp;</span><span class="mtk6">&lt;</span><span class="mtk3">iframe</span><span class="mtk1">&nbsp;</span><span class="mtk3">width</span><span class="mtk6">=</span><span class="mtk4">"700"</span><span class="mtk1">&nbsp;</span><span class="mtk3">src</span><span class="mtk6">=</span><span class="mtk4">"</span><span class="mtk4 detected-link">https://youtu.be/Y8neXkaNdPo</span><span class="mtk4">"</span><span class="mtk6">&gt;</span><span class="mtk1">&nbsp;</span><span class="mtk6">&lt;/</span><span class="mtk3">iframe</span><span class="mtk6">&gt;</span></span></div><div style="top:57px;height:19px;" class="view-line"><span><span class="mtk1">&nbsp;&nbsp;&nbsp;&nbsp;</span><span class="mtk6">&lt;</span><span class="mtk3">a</span><span class="mtk1">&nbsp;</span><span class="mtk3">href</span><span class="mtk6">=</span><span class="mtk4">"</span><span class="mtk4 detected-link">https://youtu.be/Y8neXkaNdPo</span><span class="mtk4">"</span><span class="mtk6">&gt;</span><span class="mtk1">iuhpuh&nbsp;</span><span class="mtk6">&lt;/</span><span class="mtk3">a</span><span class="mtk6">&gt;</span></span></div><div style="top:76px;height:19px;" class="view-line"><span><span></span></span></div><div style="top:95px;height:19px;" class="view-line"><span><span class="mtk6">&lt;/</span><span class="mtk3">html</span><span class="mtk6">&gt;</span></span></div></div><div data-mprt="1" class="contentWidgets" style="position: absolute; top: 0px;"></div><div role="presentation" aria-hidden="true" class="cursors-layer cursor-line-style cursor-solid"><div class="cursor monaco-mouse-cursor-text " style="height: 19px; top: 0px; left: 0px; font-family: Consolas, &quot;Courier New&quot;, monospace; font-weight: normal; font-size: 14px; font-feature-settings: &quot;liga&quot; 0, &quot;calt&quot; 0; line-height: 19px; letter-spacing: 0px; display: block; visibility: hidden; width: 1.6px;"></div></div></div><div role="presentation" aria-hidden="true" class="invisible scrollbar horizontal" style="position: absolute; width: 621px; height: 4px; left: 0px; bottom: 0px;"><div class="slider" style="position: absolute; top: 0px; left: 0px; height: 4px; transform: translate3d(0px, 0px, 0px); contain: strict; width: 621px;"></div></div><canvas class="decorationsOverviewRuler" aria-hidden="true" width="5" height="735" style="position: absolute; transform: translate3d(0px, 0px, 0px); contain: strict; top: 0px; right: 0px; width: 4px; height: 588px;"></canvas><div role="presentation" aria-hidden="true" class="invisible scrollbar vertical fade" style="position: absolute; width: 4px; height: 588px; right: 0px; top: 0px;"><div class="slider" style="position: absolute; top: 0px; left: 0px; width: 4px; transform: translate3d(0px, 0px, 0px); contain: strict; height: 506px;"></div></div></div><div role="presentation" aria-hidden="true" style="width: 708px;"></div><textarea data-mprt="6" class="inputarea monaco-mouse-cursor-text" wrap="off" autocorrect="off" autocapitalize="off" autocomplete="off" spellcheck="false" aria-label="Editor content;Press Alt+F1 for Accessibility Options." tabindex="0" role="textbox" aria-roledescription="editor" aria-multiline="true" aria-haspopup="false" aria-autocomplete="both" style="font-family: Consolas, &quot;Courier New&quot;, monospace; font-weight: normal; font-size: 14px; font-feature-settings: &quot;liga&quot; 0, &quot;calt&quot; 0; line-height: 19px; letter-spacing: 0px; top: 0px; left: 83px; width: 1px; height: 1px;"></textarea><div style="position: absolute; top: 0px; left: 0px; width: 0px; height: 0px;"></div><div data-mprt="4" class="overlayWidgets" style="width: 708px;"><div class="accessibilityHelpWidget" role="dialog" aria-hidden="true" widgetid="editor.contrib.accessibilityHelpWidget" style="display: none; position: absolute;"><div role="document"></div></div><div widgetid="editor.contrib.quickInputWidget" style="position: absolute; top: 0px; right: 50%;"></div></div><div data-mprt="8" class="minimap slider-mouseover" role="presentation" aria-hidden="true" style="position: absolute; left: 0px; width: 0px; height: 588px;"><div class="minimap-shadow-hidden" style="height: 588px;"></div><canvas width="0" height="735" style="position: absolute; left: 0px; width: 0px; height: 588px;"></canvas><canvas class="minimap-decorations-layer" width="0" height="735" style="position: absolute; left: 0px; width: 0px; height: 588px;"></canvas><div class="minimap-slider" style="position: absolute; transform: translate3d(0px, 0px, 0px); contain: strict; width: 0px;"><div class="minimap-slider-horizontal" style="position: absolute; width: 0px; height: 0px;"></div></div></div></div><div data-mprt="2" class="overflowingContentWidgets"><div class="monaco-editor rename-box" widgetid="__renameInputWidget" style="background-color: rgb(12, 20, 31); color: rgb(255, 255, 255); position: absolute; visibility: hidden; max-width: 1536px;"><input class="rename-input" type="text" aria-label="Rename input. Type new name and press Enter to commit." style="font-family: Consolas, &quot;Courier New&quot;, monospace; font-weight: normal; font-size: 14px; background-color: rgb(0, 0, 0); border-width: 1px; border-style: solid; border-color: rgb(111, 195, 223);"><div class="rename-label" style="font-size: 11.2px;">Enter to Rename, Shift+Enter to Preview</div></div><div class="monaco-hover hidden" tabindex="0" role="tooltip" widgetid="editor.contrib.modesContentHoverWidget" style="position: absolute; visibility: hidden; max-width: 1536px;"><div class="monaco-scrollable-element " role="presentation" style="position: relative; overflow: hidden;"><div class="monaco-hover-content" style="overflow: hidden; font-size: 14px; line-height: 1.35714; max-height: 250px; max-width: 500px;"></div><div role="presentation" aria-hidden="true" class="invisible scrollbar horizontal" style="position: absolute;"><div class="slider" style="position: absolute; top: 0px; left: 0px; height: 10px; transform: translate3d(0px, 0px, 0px); contain: strict;"></div></div><div role="presentation" aria-hidden="true" class="invisible scrollbar vertical" style="position: absolute;"><div class="slider" style="position: absolute; top: 0px; left: 0px; width: 10px; transform: translate3d(0px, 0px, 0px); contain: strict;"></div></div><div class="shadow"></div><div class="shadow"></div><div class="shadow"></div></div></div></div><div class="context-view" aria-hidden="true" style="display: none;"></div></div></div></div></div><div class="Layout__Pane-sc-nh0up0 hnQGIf"><div class="Layout__MonacoWrapper-sc-1vrgfzp kTVSQC"><div class=" monaco-break-points-disabled monaco-editor-wrapper" data-keybinding-context="11" data-mode-id="javascript" style="height: 100%; width: 100%; --codelens-font-features_1cd5ccf0:&quot;liga&quot; off, &quot;calt&quot; off; --code-editorInlayHintsFontFamily:Consolas, &quot;Courier New&quot;, monospace;"><div class="monaco-editor no-user-select  showUnused showDeprecated hc-black" role="code" data-uri="inmemory://model/11" style="width: 5px; height: 5px;"><div data-mprt="3" class="overflow-guard" style="width: 5px; height: 5px;"><div class="margin" role="presentation" aria-hidden="true" style="position: absolute; transform: translate3d(0px, 0px, 0px); contain: strict; top: 0px; height: 19px; width: 83px;"><div class="glyph-margin" style="left: 0px; width: 19px; height: 19px;"></div><div class="margin-view-zones" role="presentation" aria-hidden="true" style="position: absolute;"></div><div class="margin-view-overlays" role="presentation" aria-hidden="true" style="position: absolute; width: 83px; font-family: Consolas, &quot;Courier New&quot;, monospace; font-weight: normal; font-size: 14px; font-feature-settings: &quot;liga&quot; 0, &quot;calt&quot; 0; line-height: 19px; letter-spacing: 0px; height: 19px;"><div style="position:absolute;top:0px;width:100%;height:19px;"><div class="current-line" style="width:83px; height:19px;"></div><div class="active-line-number line-numbers" style="left:19px;width:38px;">1</div></div></div></div><div class="monaco-scrollable-element editor-scrollable hc-black" role="presentation" data-mprt="5" style="position: absolute; overflow: hidden; left: 83px; height: 5px;"><div class="lines-content monaco-editor-background" style="position: absolute; overflow: hidden; width: 1e+06px; height: 1e+06px; transform: translate3d(0px, 0px, 0px); contain: strict; top: 0px; left: 0px;"><div class="view-overlays" role="presentation" aria-hidden="true" style="position: absolute; height: 0px; width: 39px;"><div style="position:absolute;top:0px;width:100%;height:19px;"></div></div><div role="presentation" aria-hidden="true" class="view-rulers"></div><div class="view-zones" role="presentation" aria-hidden="true" style="position: absolute;"></div><div class="view-lines monaco-mouse-cursor-text" role="presentation" aria-hidden="true" data-mprt="7" style="position: absolute; font-family: Consolas, &quot;Courier New&quot;, monospace; font-weight: normal; font-size: 14px; font-feature-settings: &quot;liga&quot; 0, &quot;calt&quot; 0; line-height: 19px; letter-spacing: 0px; width: 39px; height: 19px;"><div style="top:0px;height:19px;" class="view-line"><span><span></span></span></div></div><div data-mprt="1" class="contentWidgets" style="position: absolute; top: 0px;"></div><div role="presentation" aria-hidden="true" class="cursors-layer cursor-line-style cursor-solid"><div class="cursor monaco-mouse-cursor-text " style="height: 19px; top: 0px; left: 0px; font-family: Consolas, &quot;Courier New&quot;, monospace; font-weight: normal; font-size: 14px; font-feature-settings: &quot;liga&quot; 0, &quot;calt&quot; 0; line-height: 19px; letter-spacing: 0px; display: block; visibility: hidden; width: 1.6px;"></div></div></div><div role="presentation" aria-hidden="true" class="invisible scrollbar horizontal fade" style="position: absolute; width: 0px; height: 4px; left: 0px; bottom: 0px;"><div class="slider" style="position: absolute; top: 0px; left: 0px; height: 4px; transform: translate3d(0px, 0px, 0px); contain: strict; width: 20px;"></div></div><canvas class="decorationsOverviewRuler" aria-hidden="true" width="5" height="6" style="position: absolute; transform: translate3d(0px, 0px, 0px); contain: strict; top: 0px; right: 0px; width: 4px; height: 5px;"></canvas><div role="presentation" aria-hidden="true" class="invisible scrollbar vertical fade" style="position: absolute; width: 4px; height: 5px; right: 0px; top: 0px;"><div class="slider" style="position: absolute; top: 0px; left: 0px; width: 4px; transform: translate3d(0px, 0px, 0px); contain: strict; height: 20px;"></div></div></div><div role="presentation" aria-hidden="true" style="width: 5px;"></div><textarea data-mprt="6" class="inputarea monaco-mouse-cursor-text" wrap="off" autocorrect="off" autocapitalize="off" autocomplete="off" spellcheck="false" aria-label="Editor content;Press Alt+F1 for Accessibility Options." tabindex="0" role="textbox" aria-roledescription="editor" aria-multiline="true" aria-haspopup="false" aria-autocomplete="both" style="font-family: Consolas, &quot;Courier New&quot;, monospace; font-weight: normal; font-size: 14px; font-feature-settings: &quot;liga&quot; 0, &quot;calt&quot; 0; line-height: 19px; letter-spacing: 0px; top: 0px; left: 0px; width: 1px; height: 1px;"></textarea><div class="monaco-editor-background textAreaCover margin" style="position: absolute; top: 0px; left: 0px; width: 1px; height: 1px;"></div><div data-mprt="4" class="overlayWidgets" style="width: 5px;"><div class="accessibilityHelpWidget" role="dialog" aria-hidden="true" widgetid="editor.contrib.accessibilityHelpWidget" style="display: none; position: absolute;"><div role="document"></div></div><div widgetid="editor.contrib.quickInputWidget" style="position: absolute; top: 0px; right: 50%;"></div></div><div data-mprt="8" class="minimap slider-mouseover" role="presentation" aria-hidden="true" style="position: absolute; left: 0px; width: 0px; height: 5px;"><div class="minimap-shadow-hidden" style="height: 5px;"></div><canvas width="0" height="6" style="position: absolute; left: 0px; width: 0px; height: 5px;"></canvas><canvas class="minimap-decorations-layer" width="0" height="6" style="position: absolute; left: 0px; width: 0px; height: 5px;"></canvas><div class="minimap-slider" style="position: absolute; transform: translate3d(0px, 0px, 0px); contain: strict; width: 0px;"><div class="minimap-slider-horizontal" style="position: absolute; width: 0px; height: 0px;"></div></div></div></div><div data-mprt="2" class="overflowingContentWidgets"><div class="monaco-editor rename-box" widgetid="__renameInputWidget" style="background-color: rgb(12, 20, 31); color: rgb(255, 255, 255); position: absolute; visibility: hidden; max-width: 1536px;"><input class="rename-input" type="text" aria-label="Rename input. Type new name and press Enter to commit." style="font-family: Consolas, &quot;Courier New&quot;, monospace; font-weight: normal; font-size: 14px; background-color: rgb(0, 0, 0); border-width: 1px; border-style: solid; border-color: rgb(111, 195, 223);"><div class="rename-label" style="font-size: 11.2px;">Enter to Rename, Shift+Enter to Preview</div></div></div><div class="context-view" aria-hidden="true" style="display: none;"></div></div></div></div></div><div class="Layout__Pane-sc-nh0up0 hnQGIf"><div class="Layout__MonacoWrapper-sc-1vrgfzp kTVSQC"><div class=" monaco-break-points-disabled monaco-editor-wrapper" data-keybinding-context="12" data-mode-id="css" style="height: 100%; width: 100%; --codelens-font-features_1cd5ccf1:&quot;liga&quot; off, &quot;calt&quot; off;"><div class="monaco-editor no-user-select  showUnused showDeprecated hc-black" role="code" data-uri="inmemory://model/12" style="width: 5px; height: 5px;"><div data-mprt="3" class="overflow-guard" style="width: 5px; height: 5px;"><div class="margin" role="presentation" aria-hidden="true" style="position: absolute; transform: translate3d(0px, 0px, 0px); contain: strict; top: 0px; height: 133px; width: 83px;"><div class="glyph-margin" style="left: 0px; width: 19px; height: 133px;"></div><div class="margin-view-zones" role="presentation" aria-hidden="true" style="position: absolute;"></div><div class="margin-view-overlays" role="presentation" aria-hidden="true" style="position: absolute; width: 83px; font-family: Consolas, &quot;Courier New&quot;, monospace; font-weight: normal; font-size: 14px; font-feature-settings: &quot;liga&quot; 0, &quot;calt&quot; 0; line-height: 19px; letter-spacing: 0px; height: 133px;"><div style="position:absolute;top:0px;width:100%;height:19px;"><div class="current-line" style="width:83px; height:19px;"></div><div class="cldr codicon codicon-folding-expanded" style="left:57px;width:26px;"></div><div class="active-line-number line-numbers" style="left:19px;width:38px;">1</div></div></div></div><div class="monaco-scrollable-element editor-scrollable hc-black" role="presentation" data-mprt="5" style="position: absolute; overflow: hidden; left: 83px; height: 5px;"><div class="lines-content monaco-editor-background" style="position: absolute; overflow: hidden; width: 1e+06px; height: 1e+06px; transform: translate3d(0px, 0px, 0px); contain: strict; top: 0px; left: 0px;"><div class="view-overlays" role="presentation" aria-hidden="true" style="position: absolute; height: 0px; width: 84px;"><div style="position:absolute;top:0px;width:100%;height:19px;"></div></div><div role="presentation" aria-hidden="true" class="view-rulers"></div><div class="view-zones" role="presentation" aria-hidden="true" style="position: absolute;"></div><div class="view-lines monaco-mouse-cursor-text" role="presentation" aria-hidden="true" data-mprt="7" style="position: absolute; font-family: Consolas, &quot;Courier New&quot;, monospace; font-weight: normal; font-size: 14px; font-feature-settings: &quot;liga&quot; 0, &quot;calt&quot; 0; line-height: 19px; letter-spacing: 0px; width: 84px; height: 133px;"><div style="top:0px;height:19px;" class="view-line"><span><span class="mtk3">body</span><span class="mtk1">&nbsp;</span><span class="mtk6">{</span></span></div></div><div data-mprt="1" class="contentWidgets" style="position: absolute; top: 0px;"></div><div role="presentation" aria-hidden="true" class="cursors-layer cursor-line-style cursor-solid"><div class="cursor monaco-mouse-cursor-text " style="height: 19px; top: 0px; left: 0px; font-family: Consolas, &quot;Courier New&quot;, monospace; font-weight: normal; font-size: 14px; font-feature-settings: &quot;liga&quot; 0, &quot;calt&quot; 0; line-height: 19px; letter-spacing: 0px; display: block; visibility: hidden; width: 1.6px;"></div></div></div><div role="presentation" aria-hidden="true" class="invisible scrollbar horizontal fade" style="position: absolute; width: 0px; height: 4px; left: 0px; bottom: 0px;"><div class="slider" style="position: absolute; top: 0px; left: 0px; height: 4px; transform: translate3d(0px, 0px, 0px); contain: strict; width: 20px;"></div></div><canvas class="decorationsOverviewRuler" aria-hidden="true" width="5" height="6" style="position: absolute; transform: translate3d(0px, 0px, 0px); contain: strict; top: 0px; right: 0px; width: 4px; height: 5px;"></canvas><div role="presentation" aria-hidden="true" class="invisible scrollbar vertical fade" style="position: absolute; width: 4px; height: 5px; right: 0px; top: 0px;"><div class="slider" style="position: absolute; top: 0px; left: 0px; width: 4px; transform: translate3d(0px, 0px, 0px); contain: strict; height: 20px;"></div></div></div><div role="presentation" aria-hidden="true" style="width: 5px;"></div><textarea data-mprt="6" class="inputarea monaco-mouse-cursor-text" wrap="off" autocorrect="off" autocapitalize="off" autocomplete="off" spellcheck="false" aria-label="Editor content;Press Alt+F1 for Accessibility Options." tabindex="0" role="textbox" aria-roledescription="editor" aria-multiline="true" aria-haspopup="false" aria-autocomplete="both" style="font-family: Consolas, &quot;Courier New&quot;, monospace; font-weight: normal; font-size: 14px; font-feature-settings: &quot;liga&quot; 0, &quot;calt&quot; 0; line-height: 19px; letter-spacing: 0px; top: 0px; left: 0px; width: 1px; height: 1px;"></textarea><div class="monaco-editor-background textAreaCover margin" style="position: absolute; top: 0px; left: 0px; width: 1px; height: 1px;"></div><div data-mprt="4" class="overlayWidgets" style="width: 5px;"><div class="accessibilityHelpWidget" role="dialog" aria-hidden="true" widgetid="editor.contrib.accessibilityHelpWidget" style="display: none; position: absolute;"><div role="document"></div></div><div widgetid="editor.contrib.quickInputWidget" style="position: absolute; top: 0px; right: 50%;"></div></div><div data-mprt="8" class="minimap slider-mouseover" role="presentation" aria-hidden="true" style="position: absolute; left: 0px; width: 0px; height: 5px;"><div class="minimap-shadow-hidden" style="height: 5px;"></div><canvas width="0" height="6" style="position: absolute; left: 0px; width: 0px; height: 5px;"></canvas><canvas class="minimap-decorations-layer" width="0" height="6" style="position: absolute; left: 0px; width: 0px; height: 5px;"></canvas><div class="minimap-slider" style="position: absolute; transform: translate3d(0px, 0px, 0px); contain: strict; width: 0px;"><div class="minimap-slider-horizontal" style="position: absolute; width: 0px; height: 0px;"></div></div></div></div><div data-mprt="2" class="overflowingContentWidgets"><div class="monaco-editor rename-box" widgetid="__renameInputWidget" style="background-color: rgb(12, 20, 31); color: rgb(255, 255, 255); position: absolute; visibility: hidden; max-width: 1536px;"><input class="rename-input" type="text" aria-label="Rename input. Type new name and press Enter to commit." style="font-family: Consolas, &quot;Courier New&quot;, monospace; font-weight: normal; font-size: 14px; background-color: rgb(0, 0, 0); border-width: 1px; border-style: solid; border-color: rgb(111, 195, 223);"><div class="rename-label" style="font-size: 11.2px;">Enter to Rename, Shift+Enter to Preview</div></div></div><div class="context-view" aria-hidden="true" style="display: none;"></div></div></div></div></div></div><div role="separator" class="layout-splitter"></div><div class="layout-pane" style="width: 724.612px;"><div class="Layout__ResultsWrapper-sc-7hcgdk iYaNkc"><div class="splitter-layout splitter-layout-vertical"><div class="layout-pane layout-pane-primary"><div class="Layout__Tabs-sc-ptgudx jFZfth"><div id="jsLevel---Reference" class="Layout__Tab-sc-x9wnbn Layout__ResultsTab-sc-46naeo guMRrC algo-tab"><span>jsLevel---Reference</span></div><div id="jsLevel---Result" class="Layout__Tab-sc-x9wnbn Layout__ResultsTab-sc-46naeo hsZmWE algo-tab"><span>jsLevel---Result</span></div><div id="jsLevel---Overlay" class="Layout__Tab-sc-x9wnbn Layout__ResultsTab-sc-46naeo hsZmWE algo-tab"><span>jsLevel---Overlay</span></div></div><div class="Layout__Pane-sc-nh0up0 hnXvzm"><div class="Layout__Preview-sc-1qm1m2o iQtqbl"><div class="Layout__SandboxWrapper-sc-1opocmu hjZsHx"><iframe title="sandbox" frameborder="0" width="100%" height="100%" src="./lesson_files/saved_resource.html"></iframe></div></div><div class="Layout__Overlay-sc-j5cxwn foWEii"><iframe frameborder="0" width="100%" height="100%" class="Layout__ReferenceCode-sc-v8p8ti imDGfZ" src="./lesson_files/saved_resource(1).html"></iframe></div></div></div><div role="separator" class="layout-splitter"></div><div class="layout-pane" style="height: 218px;"><div class="Layout__Pane-sc-nh0up0 hnXvzm"><div class="Layout__ConsoleWrapper-sc-1bxauf1 hAXZvV"><div class="css-dnj0yz"></div></div></div></div></div></div></div></div></div><div class="Layout__FixedPanel-sc-18o9bae nKhnE"><div class="Layout__Wrapper-sc-1jrlffn htuJRb"><div class="Layout__MovingPanel-sc-874jb7 cPpFZJ"><div class="Layout__ArrowWrapper-sc-1f0uia1 fGFbmE"><svg width="6" height="7" viewBox="0 0 6 7" fill="none" xmlns="http://www.w3.org/2000/svg" class="Layout__Arrow-sc-pzssva kRbjNo"><path d="M.638 1.363v4.073a1 1 0 001.588.808l2.8-2.036a1 1 0 000-1.617L2.226.555a1 1 0 00-1.588.808z" fill="#833AE0"></path></svg></div></div><div width="488" class="Layout__Panel-sc-1k5wscy cSHxow"><div class="Layout__Wrapper-sc-vm964p DJA-Dz"><div class="Layout__Navigation-sc-6e5gbl ebrBmk"><button class="Layout__NextLevelButton-sc-yijgdp hCyPnc"><span>Наступний рівень</span></button></div></div><div class="Layout__Content-sc-1hydqjf gOiwCj"><div class="styles__Wrapper-sc-14qqkbh ezOYve"><div class="ExpansionPanel__Wrapper-sc-d38wa4 kUmvnY"><div class="ExpansionPanel__Header-sc-10m7ec0 ToOQs"><div class="styles__Header-sc-pnrzj5 hkLumK"><span class="styles__LevelType-sc-huq23j cpQKyH"><span>Перевір сам</span></span><div class="styles__Title-sc-fallc4 cmzFGe"><bdi>Додай відео. Розміри фрейму</bdi></div></div></div></div></div><div class="styles__WrapperHints-sc-exavc7 gNDYc"><div class="styles__ProgressBar-sc-wdmcxl btIsKQ"></div><div class="styles__TitleHints-sc-1wmilot jsdDIE"><span>Основні задачі</span></div><div class="styles__Wrapper-sc-wq4958 fdFmOK"><div class="ExpansionPanel__Wrapper-sc-d38wa4 kUmvnY"><div class="ExpansionPanel__Header-sc-10m7ec0 ijdquA"><div class="styles__Header-sc-fvc2oh lgyMUg"><label class="Checkbox__StyledLabel-sc-xur1fe dBvBgN"><span data-qa-id="sidebarTaskListCheckbox" data-qa-checked="false" class="Checkbox__Check-sc-xq78s7 dwvpCO"></span></label><div class="styles__Title-sc-1o9fqkq drterL"><bdi>Додай відео</bdi></div></div><span class="ExpansionPanel__IconWrapper-sc-1rwkon2 bbYsTu"><svg width="13" height="8" viewBox="0 0 13 8" fill="#CCC" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" clip-rule="evenodd" d="M12.134.366a1.25 1.25 0 010 1.768l-5 5a1.25 1.25 0 01-1.768 0l-5-5A1.25 1.25 0 112.134.366L6.25 4.482 10.366.366a1.25 1.25 0 011.768 0z"></path></svg></span></div><div class="ExpansionPanel__Content-sc-uychjo HrHFm"><div class="styles__Content-sc-18b4ljb cgrueh"><bdi>Відкрий посилання на відео https://youtu.be/Y8neXkaNdPo та скопіюй із YouTube HTML-код.
Встав після заголовка.</bdi></div></div></div></div><div class="styles__Wrapper-sc-wq4958 fdFmOK"><div class="ExpansionPanel__Wrapper-sc-d38wa4 kUmvnY"><div class="ExpansionPanel__Header-sc-10m7ec0 ijdquA"><div class="styles__Header-sc-fvc2oh lgyMUg"><label class="Checkbox__StyledLabel-sc-xur1fe dBvBgN"><span data-qa-id="sidebarTaskListCheckbox" data-qa-checked="false" class="Checkbox__Check-sc-xq78s7 dwvpCO"></span></label><div class="styles__Title-sc-1o9fqkq hVYQhN"><bdi>Розміри фрейму</bdi></div></div><span class="ExpansionPanel__IconWrapper-sc-1rwkon2 CAlBa"><svg width="13" height="8" viewBox="0 0 13 8" fill="#CCC" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" clip-rule="evenodd" d="M12.134.366a1.25 1.25 0 010 1.768l-5 5a1.25 1.25 0 01-1.768 0l-5-5A1.25 1.25 0 112.134.366L6.25 4.482 10.366.366a1.25 1.25 0 011.768 0z"></path></svg></span></div><div class="ExpansionPanel__Content-sc-uychjo cvRLiy"><div class="styles__Content-sc-18b4ljb cgrueh"><bdi>Зміни розміри фрейму: ширина 400, висота 300.</bdi></div></div></div></div></div></div></div></div></div></div></div></div><div class="monaco-aria-container"><div class="monaco-alert" role="alert" aria-atomic="true"></div><div class="monaco-alert" role="alert" aria-atomic="true"></div><div class="monaco-status" role="complementary" aria-live="polite" aria-atomic="true"></div><div class="monaco-status" role="complementary" aria-live="polite" aria-atomic="true"></div></div></body></html>
