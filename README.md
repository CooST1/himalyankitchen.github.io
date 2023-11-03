<!doctype html >
<html xmlns="http://www.w3.org/1999/xhtml" lang="en"
      class="">
<head>
    


































<script type="text/javascript">
    window._currentDevice = 'desktop';
    window.Parameters = window.Parameters || {
        AjaxContainer: 'div.dmBody',
        WrappingContainer: 'div.dmOuter',
        HomeUrl: 'https://www.mitaskitchen.com/',
        AccountUUID: '3edc0732515d4a9fafd137f8d46f5f39',
        SystemID: 'US_DIRECT_PRODUCTION',
        SiteAlias: 'e384b44b',
        SiteType: atob('RFVEQU9ORQ=='),
        PublicationDate: 'Wed Oct 11 03:52:23 UTC 2023',
        ExternalUid: null,
        IsSiteMultilingual: false,
        InitialPostAlias: '',
        InitialDynamicItem: '',
        DynamicPageInfo: {
            isDynamicPage: false,
            base64JsonRowData: 'null',
        },
        InitialPageAlias: 'home',
        InitialPageUuid: '59c7fdfb911a4cde9020f96c13d72885',
        InitialPageId: '1135069826',
        InitialEncodedPageAlias: 'aG9tZQ==',
        CurrentPageUrl: '',
        IsCurrentHomePage: true,
        AllowAjax: false,
        AfterAjaxCommand: null,
        HomeLinkText: 'Back To Home',
        UseGalleryModule: false,
        CurrentThemeName: 'Layout Theme',
        ThemeVersion: '38260',
        DefaultPageAlias: '',
        RemoveDID: true,
        WidgetStyleID: null,
        IsHeaderFixed: false,
        IsHeaderSkinny: false,
        IsBfs: true,
        StorePageAlias: 'null',
        StorePagesUrls: 'eyJTVE9SRV9QUk9EVUNUX1BBR0UiOiJwcm9kdWN0IiwiU1RPUkVfQ0FURUdPUllfUEFHRSI6ImNhdGVnb3J5In0=',
        IsNewStore: 'false',
        StorePath: '',
        StoreId: 'null',
        StoreVersion: 0,
        StoreBaseUrl: '',
        StoreCleanUrl: true,
        StoreDisableScrolling: true,
        IsStoreSuspended: false,
        NotificationSubDomain: 'mitaskitchen',
        HasCustomDomain: true,
        showCookieNotification: false,
        cookiesNotificationMarkup: 'null',
        translatedPageUrl: '',
        isFastMigrationSite: false,
        sidebarPosition: 'NA',
        currentLanguage: 'en',
        currentLocale: 'en',
        NavItems: '{}',
        errors: {
            general: 'There was an error connecting to the page.<br/> Make sure you are not offline.',
            password: 'Incorrect name/password combination',
            tryAgain: 'Try again'
        },
        NavigationAreaParams: {
            ShowBackToHomeOnInnerPages: true,
            NavbarSize: -1,
            NavbarLiveHomePage: 'https://www.mitaskitchen.com/',
            BlockContainerSelector: '.dmBody',
            NavbarSelector: '#dmNav:has(a)',
            SubNavbarSelector: '#subnav_main'
        },
        hasCustomCode: true,
        planID: '7',
        customTemplateId: 'null',
        siteTemplateId: 'null',
        productId: 'DM_DIRECT',
        disableTracking: false,
        pageType: 'FROM_SCRATCH',
        isRuntimeServer: true,
        isInEditor: false,
    };

    window.Parameters.LayoutID = {};
    window.Parameters.LayoutID[window._currentDevice] = 6;
    window.Parameters.LayoutVariationID = {};
    window.Parameters.LayoutVariationID[window._currentDevice] = 5;
</script>























<!-- Injecting site-wide to the head -->




<!-- End Injecting site-wide to the head -->

<!-- Inject secured cdn script -->


<!-- ========= Meta Tags ========= -->
<!-- PWA settings -->
<script>
    function toHash(str) {
        var hash = 5381, i = str.length;
        while (i) {
            hash = hash * 33 ^ str.charCodeAt(--i)
        }
        return hash >>> 0
    }
</script>
<script>
    (function (global) {
    //const cacheKey = global.cacheKey;
    const isOffline = 'onLine' in navigator && navigator.onLine === false;
    const hasServiceWorkerSupport = 'serviceWorker' in navigator;
    if (isOffline) {
        console.log('offline mode');
    }
    if (!hasServiceWorkerSupport) {
        console.log('service worker is not supported');
    }
    if (hasServiceWorkerSupport && !isOffline) {
        window.addEventListener('load', function () {
            const serviceWorkerPath = '/runtime-service-worker.js?v=3';
            navigator.serviceWorker
                .register(serviceWorkerPath, { scope: './' })
                .then(
                    function (registration) {
                        // Registration was successful
                        console.log(
                            'ServiceWorker registration successful with scope: ',
                            registration.scope
                        );
                    },
                    function (err) {
                        // registration failed :(
                        console.log('ServiceWorker registration failed: ', err);
                    }
                )
                .catch(function (err) {
                    console.log(err);
                });
        });

        // helper function to refresh the page
        var refreshPage = (function () {
            var refreshing;
            return function () {
                if (refreshing) return;
                // prevent multiple refreshes
                var refreshkey = 'refreshed' + location.href;
                var prevRefresh = localStorage.getItem(refreshkey);
                if (prevRefresh) {
                    localStorage.removeItem(refreshkey);
                    if (Date.now() - prevRefresh < 30000) {
                        return; // dont go into a refresh loop
                    }
                }
                refreshing = true;
                localStorage.setItem(refreshkey, Date.now());
                console.log('refereshing page');
                window.location.reload();
            };
        })();

        function messageServiceWorker(data) {
            return new Promise(function (resolve, reject) {
                if (navigator.serviceWorker.controller) {
                    var worker = navigator.serviceWorker.controller;
                    var messageChannel = new MessageChannel();
                    messageChannel.port1.onmessage = replyHandler;
                    worker.postMessage(data, [messageChannel.port2]);
                    function replyHandler(event) {
                        resolve(event.data);
                    }
                } else {
                    resolve();
                }
            });
        }
    }
})(window);
</script>
<!-- Add manifest -->
<!-- End PWA settings -->


<meta http-equiv="Content-type" content="text/html;charset=utf-8">
<meta charset="utf-8">

<link rel="canonical" href="https://www.mitaskitchen.com/">

<meta id="view" name="viewport" content="initial-scale=1, minimum-scale=1, maximum-scale=5, viewport-fit=cover">
<meta name="apple-mobile-web-app-capable" content="yes">

<!--Add favorites icons-->

<link rel="apple-touch-icon" href="https://irp.cdn-website.com/e384b44b/dms3rep/multi/Favicon+57x57.png"/>

<link rel="icon" type="image/x-icon" href="https://irp.cdn-website.com/e384b44b/site_favicon_16_1682564125075.ico"/>

<!-- End favorite icons -->

<link rel="preconnect" href="https://lirp.cdn-website.com/" crossorigin />



<!-- render the required CSS and JS in the head section -->
<script>
    window.SystemID = 'US_DIRECT_PRODUCTION';

    if(!window.dmAPI) {
        window.dmAPI = {
            registerExternalRuntimeComponent: function() {
            },
            getCurrentDeviceType: function() {
                return window._currentDevice;
            }
        };
    }

    if (!window.requestIdleCallback) {
        window.requestIdleCallback = function (fn) {
            setTimeout(fn, 0);
        }
    }
</script>
<!-- loadCSS function -->



<script id="d-js-load-css">
/**
 * There are a few <link> tags with CSS resource in them that are preloaded in the page
 * in each of those there is a "onload" handler which invokes the loadCSS callback
 * defined here.
 * We are monitoring 3 main CSS files - the runtime, the global and the page.
 * When each load we check to see if we can append them all in a batch. If threre
 * is no page css (which may happen on inner pages) then we do not wait for it
 */
(function () {
  let cssLinks = {};
  function loadCssLink(link) {
    link.onload = null;
    link.rel = "stylesheet";
    link.type = "text/css";
  }
  
    function checkCss() {
      const pageCssLink = document.querySelector("[id*='CssLink']");

        if (cssLinks && cssLinks.runtime && cssLinks.global && (!pageCssLink || cssLinks.page)) {
            const storedRuntimeCssLink = cssLinks.runtime;
            const storedPageCssLink = cssLinks.page;
            const storedGlobalCssLink = cssLinks.global;

            storedGlobalCssLink.disabled = true;
            loadCssLink(storedGlobalCssLink);

            if (storedPageCssLink) {
                storedPageCssLink.disabled = true;
                loadCssLink(storedPageCssLink);
            }

            storedRuntimeCssLink.disabled = true;
            loadCssLink(storedRuntimeCssLink);

            requestAnimationFrame(() => {
                setTimeout(() => {
                    storedRuntimeCssLink.disabled = false;
                    storedGlobalCssLink.disabled = false;
                    if (storedPageCssLink) {
                      storedPageCssLink.disabled = false;
                    }
                    cssLinks = null;
                }, 0);
            });
        }
    }
  

  function loadCSS(link) {
    try {
      var urlParams = new URLSearchParams(window.location.search);
      var noCSS = !!urlParams.get("nocss");
      var cssTimeout = urlParams.get("cssTimeout") || 0;

      if (noCSS) {
        return;
      }
      if (link.href.includes("d-css-runtime")) {
        cssLinks.runtime = link;
        checkCss();
      } else if (link.id === "siteGlobalCss") {
        cssLinks.global = link;
        checkCss();
      } 
      
      else if(link.id.includes("CssLink")) {
        cssLinks.page = link;
        checkCss();
      }  
      
      else {
        requestIdleCallback(function () {
          window.setTimeout(function () {
            loadCssLink(link);
          }, parseInt(cssTimeout, 10));
        });
      }
    } catch (e) {
      throw e
    }
  }
  window.loadCSS = window.loadCSS || loadCSS;
})();
</script>

<script data-role="deferred-init" type="text/javascript">
    /* usage: window.getDeferred(<deferred name>).resolve() or window.getDeferred(<deferred name>).promise.then(...)*/
    function Def(){this.promise=new Promise((function(a,b){this.resolve=a,this.reject=b}).bind(this))}
    const defs={};
    window.getDeferred=function(a){return null==defs[a]&&(defs[a]=new Def),defs[a]}
    window.waitForDeferred = function (b, a, c) {
      let d = window?.getDeferred?.(b);
      d
        ? d.promise.then(a)
        : c && ["complete", "interactive"].includes(document.readyState)
        ? setTimeout(a, 1)
        : c
        ? document.addEventListener("DOMContentLoaded", a)
        : console.error(`Deferred  does not exist`);
    };
</script>
<style id="forceCssIncludes">
    /* This file is auto-generated from a `scss` file with the same name */

.videobgwrapper{overflow:hidden;position:absolute;z-index:0;width:100%;height:100%;top:0;left:0;pointer-events:none;border-radius:inherit}.videobgframe{position:absolute;width:101%;height:100%;top:50%;left:50%;transform:translateY(-50%) translateX(-50%);object-fit:fill}#dm video.videobgframe{margin:0}@media (max-width:767px){.dmRoot .dmPhotoGallery.newPhotoGallery:not(.photo-gallery-done){min-height:80vh}}@media (min-width:1025px){.dmRoot .dmPhotoGallery.newPhotoGallery:not(.photo-gallery-done){min-height:45vh}}@media (min-width:768px) and (max-width:1024px){.responsiveTablet .dmPhotoGallery.newPhotoGallery:not(.photo-gallery-done){min-height:45vh}}#dm [data-show-on-page-only]{display:none!important}
</style>
<style id="cssVariables" type="text/css">
    :root {
  --color_1: rgba(255, 255, 255, 1);
  --color_2: rgba(194, 166, 165, 1);
  --color_3: rgba(252, 233, 214, 1);
  --color_4: rgba(0, 0, 0, 1);
  --color_5: rgba(194, 191, 171, 1);
}
</style>





















<!-- Google Fonts Include -->













<!-- loadCSS function -->



<script id="d-js-load-css">
/**
 * There are a few <link> tags with CSS resource in them that are preloaded in the page
 * in each of those there is a "onload" handler which invokes the loadCSS callback
 * defined here.
 * We are monitoring 3 main CSS files - the runtime, the global and the page.
 * When each load we check to see if we can append them all in a batch. If threre
 * is no page css (which may happen on inner pages) then we do not wait for it
 */
(function () {
  let cssLinks = {};
  function loadCssLink(link) {
    link.onload = null;
    link.rel = "stylesheet";
    link.type = "text/css";
  }
  
    function checkCss() {
      const pageCssLink = document.querySelector("[id*='CssLink']");

        if (cssLinks && cssLinks.runtime && cssLinks.global && (!pageCssLink || cssLinks.page)) {
            const storedRuntimeCssLink = cssLinks.runtime;
            const storedPageCssLink = cssLinks.page;
            const storedGlobalCssLink = cssLinks.global;

            storedGlobalCssLink.disabled = true;
            loadCssLink(storedGlobalCssLink);

            if (storedPageCssLink) {
                storedPageCssLink.disabled = true;
                loadCssLink(storedPageCssLink);
            }

            storedRuntimeCssLink.disabled = true;
            loadCssLink(storedRuntimeCssLink);

            requestAnimationFrame(() => {
                setTimeout(() => {
                    storedRuntimeCssLink.disabled = false;
                    storedGlobalCssLink.disabled = false;
                    if (storedPageCssLink) {
                      storedPageCssLink.disabled = false;
                    }
                    cssLinks = null;
                }, 0);
            });
        }
    }
  

  function loadCSS(link) {
    try {
      var urlParams = new URLSearchParams(window.location.search);
      var noCSS = !!urlParams.get("nocss");
      var cssTimeout = urlParams.get("cssTimeout") || 0;

      if (noCSS) {
        return;
      }
      if (link.href.includes("d-css-runtime")) {
        cssLinks.runtime = link;
        checkCss();
      } else if (link.id === "siteGlobalCss") {
        cssLinks.global = link;
        checkCss();
      } 
      
      else if(link.id.includes("CssLink")) {
        cssLinks.page = link;
        checkCss();
      }  
      
      else {
        requestIdleCallback(function () {
          window.setTimeout(function () {
            loadCssLink(link);
          }, parseInt(cssTimeout, 10));
        });
      }
    } catch (e) {
      throw e
    }
  }
  window.loadCSS = window.loadCSS || loadCSS;
})();
</script>

<link type="text/css" rel="stylesheet" href="https://irp.cdn-website.com/fonts/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;0,500;0,600;0,700;1,300;1,400;1,500;1,600;1,700&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&family=Tenor+Sans:ital,wght@0,400&family=Montserrat:ital,wght@0,100..900;1,100..900&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Yeseva+One:ital,wght@0,400&family=Open+Sans:ital,wght@0,300..800;1,300..800&amp;subset=latin-ext&amp;display=swap"  />





<!-- RT CSS Include d-css-runtime-desktop-one-package-structured-global-->
<link rel="stylesheet" type="text/css" href="https://static.cdn-website.com/mnlt/production/3886/_dm/s/rt/dist/css/d-css-runtime-desktop-one-package-structured-global.min.css" />

<!-- End of RT CSS Include -->


<link type="text/css" rel="stylesheet" href="https://irp.cdn-website.com/WIDGET_CSS/production_3886/a0bd0a1dbd123f28272d9c95336b6cca.css" id="widgetCSS" />


<!-- Support `img` size attributes -->
<style>img[width][height] {
  height: auto;
}</style>

<!-- Support showing sticky element on page only -->
<style>
  body[data-page-alias="home"] #dm [data-show-on-page-only="home"] {
    display: block !important;
  }
</style>

<!-- This is populated in Ajax navigation -->
<style id="pageAdditionalWidgetsCss" type="text/css">
</style>




<!-- Site CSS -->
<link type="text/css" rel="stylesheet" href="https://irp.cdn-website.com/e384b44b/files/e384b44b_withFlex_1.min.css?v=198" id="siteGlobalCss" />



<style id="customWidgetStyle" type="text/css">
    
    .widget-1f5975 .copyright {
    font-size: 13px;
    display: flex;
    text-align: left;
    justify-content: flex-start;
}
    
</style>
<style id="innerPagesStyle" type="text/css">
    
</style>


<style
        id="additionalGlobalCss" type="text/css"
>
</style>

<!-- Page CSS -->
<link type="text/css" rel="stylesheet" href="https://irp.cdn-website.com/e384b44b/files/e384b44b_home_withFlex_1.min.css?v=198" id="homeCssLink" />

<style id="pagestyle" type="text/css">
    
</style>

<style id="pagestyleDevice" type="text/css">
    
</style>

<!-- Flex Sections CSS -->





<style id="globalFontSizeStyle" type="text/css">
    .font-size-50, .size-50, .size-50 > font { font-size: 50px !important; }.font-size-50, .size-50, .size-50 > font { font-size: 50px !important; }.font-size-18, .size-18, .size-18 > font { font-size: 18px !important; }.font-size-18, .size-18, .size-18 > font { font-size: 18px !important; }.font-size-36, .size-36, .size-36 > font { font-size: 36px !important; }.font-size-36, .size-36, .size-36 > font { font-size: 36px !important; }.font-size-24, .size-24, .size-24 > font { font-size: 24px !important; }.font-size-24, .size-24, .size-24 > font { font-size: 24px !important; }.font-size-36, .size-36, .size-36 > font { font-size: 36px !important; }.font-size-36, .size-36, .size-36 > font { font-size: 36px !important; }.font-size-24, .size-24, .size-24 > font { font-size: 24px !important; }.font-size-24, .size-24, .size-24 > font { font-size: 24px !important; }.font-size-36, .size-36, .size-36 > font { font-size: 36px !important; }.font-size-36, .size-36, .size-36 > font { font-size: 36px !important; }.font-size-36, .size-36, .size-36 > font { font-size: 36px !important; }.font-size-24, .size-24, .size-24 > font { font-size: 24px !important; }.font-size-24, .size-24, .size-24 > font { font-size: 24px !important; }.font-size-36, .size-36, .size-36 > font { font-size: 36px !important; }.font-size-36, .size-36, .size-36 > font { font-size: 36px !important; }.font-size-24, .size-24, .size-24 > font { font-size: 24px !important; }.font-size-24, .size-24, .size-24 > font { font-size: 24px !important; }.font-size-48, .size-48, .size-48 > font { font-size: 48px !important; }.font-size-48, .size-48, .size-48 > font { font-size: 48px !important; }
</style>
<style id="pageFontSizeStyle" type="text/css">
</style>




<style id="hideAnimFix">
  .dmDesktopBody:not(.editGrid) [data-anim-desktop]:not([data-anim-desktop='none']), .dmDesktopBody:not(.editGrid) [data-anim-extended] {
    visibility: hidden;
  }
  .dmDesktopBody:not(.editGrid) .dmNewParagraph[data-anim-desktop]:not([data-anim-desktop='none']), .dmDesktopBody:not(.editGrid) .dmNewParagraph[data-anim-extended] {
    visibility: hidden !important;
  }
</style>




<style id="fontFallbacks">
    @font-face {
  font-family: "Cormorant Garamond Fallback";
  src: local('Arial');
  ascent-override: 104.8482%;
  descent-override: 32.5665%;
  size-adjust: 88.1274%;
  line-gap-override: 0%;
 }@font-face {
  font-family: "Roboto Fallback";
  src: local('Arial');
  ascent-override: 92.6709%;
  descent-override: 24.3871%;
  size-adjust: 100.1106%;
  line-gap-override: 0%;
 }@font-face {
  font-family: "Tenor Sans Fallback";
  src: local('Arial');
  ascent-override: 83.7307%;
  descent-override: 22.7529%;
  size-adjust: 109.8761%;
  line-gap-override: 0%;
 }@font-face {
  font-family: "Montserrat Fallback";
  src: local('Arial');
  ascent-override: 84.9466%;
  descent-override: 22.0264%;
  size-adjust: 113.954%;
  line-gap-override: 0%;
 }@font-face {
  font-family: "Poppins Fallback";
  src: local('Arial');
  ascent-override: 92.326%;
  descent-override: 30.7753%;
  line-gap-override: 8.793%;
  size-adjust: 113.7274%;
}@font-face {
  font-family: "Yeseva One Fallback";
  src: local('Arial');
  ascent-override: 79.0385%;
  descent-override: 20.7314%;
  size-adjust: 115.7664%;
  line-gap-override: 0%;
 }@font-face {
  font-family: "Open Sans Fallback";
  src: local('Arial');
  ascent-override: 101.1768%;
  descent-override: 27.7323%;
  size-adjust: 105.6416%;
  line-gap-override: 0%;
 }
</style>


<!-- End render the required css and JS in the head section -->






<meta property="og:type" content="website">
<script type="application/ld+json">
    {
        "@context" : "https://schema.org",
        "@type" : "WebSite",
        "name" : "Mita's Kitchen",
        "url" : "https://www.mitaskitchen.com/"
    }
</script>
  <title>
    Mita's Kitchen
  </title>
  <meta name="keywords" content="mitaskitchen, mita's kitchen, mitas, restaurant, indian restaurant, indian cuisine, nepalian restaurant, nepalian cuisine, fresh naan, masala chicken near me, indian restaurant near me"/>

  <meta name="twitter:card" content="summary"/>
  <meta name="twitter:title" content="Mita's Kitchen"/>
  <meta name="twitter:image" content="https://lirp.cdn-website.com/e384b44b/dms3rep/multi/opt/Social+Media+1200x630-1920w.png"/>
  <meta property="og:title" content="Mita's Kitchen"/>
  <meta property="og:image" content="https://lirp.cdn-website.com/e384b44b/dms3rep/multi/opt/Social+Media+1200x630-1920w.png"/>




<!-- SYS- VVNfRElSRUNUX1BST0RVQ1RJT04= -->
</head>






















<body id="dmRoot" data-page-alias="home"  class="dmRoot dmDesktopBody fix-mobile-scrolling addCanvasBorder dmResellerSite dmLargeBody responsiveTablet " style="padding:0;margin:0;"
      
      >
















<!-- Preconnect to Snipcart -->
<link rel="preconnect" href="https://dudacommerce-cdn.snipcart.com">

<!-- Snipcart installation script https://docs.snipcart.com/v3/setup/installation#addproductbehavior -->
<script>
window.SnipcartSettings = {
    publicApiKey: "test_pub_a14a7e2fed404f43af8df82d9459abe1",
    loadStrategy: "on-user-interaction",
    version: "3.0.0",
    baseUrl: "https://dudacommerce-cdn.snipcart.com/",
    
    modalStyle: "side",
    
};




(function(){var s,c;(c=(s=window.SnipcartSettings).version)!=null||(s.version="3.0.0");var d,S;(S=(d=window.SnipcartSettings).timeoutDuration)!=null||(d.timeoutDuration=2750);var l,p;(p=(l=window.SnipcartSettings).baseUrl)!=null||(l.baseUrl="/");var w,u;(u=(w=window.SnipcartSettings).loadCSS)!=null||(w.loadCSS=!0);var f=window.SnipcartSettings.version.includes("v3.0.0-ci")||window.SnipcartSettings.version!="3.0.0"&&window.SnipcartSettings.version.localeCompare("3.4.0",void 0,{numeric:!0,sensitivity:"base"})===-1,g=["focus","mouseover","touchmove","scroll","keydown"];window.LoadSnipcart=r;document.readyState==="loading"?document.addEventListener("DOMContentLoaded",o):o();function o(){window.SnipcartSettings.loadStrategy?window.SnipcartSettings.loadStrategy==="on-user-interaction"&&(g.forEach(function(t){return document.addEventListener(t,r)}),setTimeout(r,window.SnipcartSettings.timeoutDuration)):r()}var a=!1;function r(){if(a)return;a=!0;let t=document.getElementsByTagName("head")[0],e=document.querySelector("#snipcart"),i=document.querySelector('src[src^="'.concat(window.SnipcartSettings.baseUrl,'"][src$="snipcart.js"]')),n=document.querySelector('link[href^="'.concat(window.SnipcartSettings.baseUrl,'"][href$="snipcart.css"]'));e||(e=document.createElement("div"),e.id="snipcart",e.setAttribute("hidden","true"),document.body.appendChild(e)),v(e),i||(i=document.createElement("script"),i.src="".concat(window.SnipcartSettings.baseUrl,"themes/v").concat(window.SnipcartSettings.version,"/default/snipcart.js"),i.async=!0,t.appendChild(i)),!n&&window.SnipcartSettings.loadCSS&&(n=document.createElement("link"),n.rel="stylesheet",n.type="text/css",n.href="".concat(window.SnipcartSettings.baseUrl,"themes/v").concat(window.SnipcartSettings.version,"/default/snipcart.css"),t.prepend(n)),g.forEach(function(m){return document.removeEventListener(m,r)})}function v(t){!f||(t.dataset.apiKey=window.SnipcartSettings.publicApiKey,window.SnipcartSettings.addProductBehavior&&(t.dataset.configAddProductBehavior=window.SnipcartSettings.addProductBehavior),window.SnipcartSettings.modalStyle&&(t.dataset.configModalStyle=window.SnipcartSettings.modalStyle),window.SnipcartSettings.currency&&(t.dataset.currency=window.SnipcartSettings.currency),window.SnipcartSettings.templatesUrl&&(t.dataset.templatesUrl=window.SnipcartSettings.templatesUrl))}})();
</script>



<!-- ========= Site Content ========= -->
<div id="dm" class='dmwr'>
    
    <div class="dm_wrapper standard-var5 widgetStyle-3 standard">
         <div dmwrapped="true" id="1901957768" class="dm-home-page" themewaschanged="true" desktop-global-classes="header-over-content" tablet-global-classes="header-over-content" mobile-global-classes="header-over-content"> <div dmtemplateid="Hamburger" data-responsive-name="ResponsiveDesktopTopTabletHamburger" class="runtime-module-container dm-bfs dm-layout-home hasAnimations hasStickyHeader rows-1200 inMiniHeaderMode hamburger-reverse header-over-content dmPageBody d-page-1716942098 dmFreeHeader" id="dm-outer-wrapper" data-page-class="1716942098" data-soch="true" data-background-parallax-selector=".dmHomeSection1, .dmSectionParallex"> <div id="dmStyle_outerContainer" class="dmOuter"> <div id="dmStyle_innerContainer" class="dmInner"> <div class="dmLayoutWrapper standard-var dmStandardDesktop"> <div id="site_content"> <div class="p_hfcontainer showOnMedium"> <div id="hamburger-drawer" class="hamburger-drawer layout-drawer" layout="e9d510f4eb904e939c2be8efaf777e6e===header" data-origin="side-reverse" data-auto-height="true"> <div class="u_1826294544 dmRespRow" style="text-align: center;" id="1826294544"> <div class="dmRespColsWrapper" id="1337204992"> <div class="u_1183846399 dmRespCol small-12 medium-12 large-12 empty-column" id="1183846399"></div> 
</div> 
</div> 
 <div class="u_1021493186 dmRespRow middleDrawerRow" style="text-align: center;" id="1021493186"> <div class="dmRespColsWrapper" id="1170137577"> <div class="dmRespCol small-12 u_1808057136 medium-12 large-12" id="1808057136"> <nav class="u_1144820115 effect-bottom2 main-navigation unifiednav dmLinksMenu" role="navigation" layout-main="vertical_nav_layout_2" layout-sub="" data-show-vertical-sub-items="HIDE" id="1144820115" dmle_extension="onelinksmenu" data-element-type="onelinksmenu" data-logo-src="" alt="" data-nav-structure="VERTICAL" wr="true" icon="true" surround="true" adwords="" navigation-id="unifiedNav"> <ul role="menubar" class="unifiednav__container  " data-auto="navigation-pages"> <li role="menuitem" class=" unifiednav__item-wrap " data-auto="more-pages" data-depth="0"> <a href="/" class="unifiednav__item  dmNavItemSelected  dmUDNavigationItem_00  " target="" data-target-page-alias="" data-auto="selected-page"> <span class="nav-item-text " data-link-text="
         Home
        " data-auto="page-text-style">Home<span class="icon icon-angle-down"></span> 
</span> 
</a> 
</li> 
 <li role="menuitem" class=" unifiednav__item-wrap " data-auto="more-pages" data-depth="0"> <a href="/menu" class="unifiednav__item  dmUDNavigationItem_010101326518  " target="" data-target-page-alias=""> <span class="nav-item-text " data-link-text="
         Menu
        " data-auto="page-text-style">Menu<span class="icon icon-angle-down"></span> 
</span> 
</a> 
</li> 
 <li role="menuitem" class=" unifiednav__item-wrap " data-auto="more-pages" data-depth="0"> <a href="/catering-online-order" class="unifiednav__item  dmUDNavigationItem_010101500621  " target="" data-target-page-alias=""> <span class="nav-item-text " data-link-text="Catering" data-auto="page-text-style">Catering<span class="icon icon-angle-down"></span> 
</span> 
</a> 
</li> 
 <li role="menuitem" class=" unifiednav__item-wrap " data-auto="more-pages" data-depth="0"> <a href="/about" class="unifiednav__item  dmUDNavigationItem_010101436714  " target="" data-target-page-alias=""> <span class="nav-item-text " data-link-text="
         About
        " data-auto="page-text-style">About<span class="icon icon-angle-down"></span> 
</span> 
</a> 
</li> 
 <li role="menuitem" class=" unifiednav__item-wrap " data-auto="more-pages" data-depth="0"> <a href="/contact" class="unifiednav__item  dmUDNavigationItem_010101943230  " target="" data-target-page-alias=""> <span class="nav-item-text " data-link-text="
         Contact
        " data-auto="page-text-style">Contact<span class="icon icon-angle-down"></span> 
</span> 
</a> 
</li> 
 <li role="menuitem" class=" unifiednav__item-wrap " data-auto="more-pages" data-depth="0"> <a href="https://squareup.com/loyalty/MLHWR7C0E9HY7" class="unifiednav__item  dmUDNavigationItem_0101019020  " target="_blank" data-target-page-alias=""> <span class="nav-item-text " data-link-text="Reward" data-auto="page-text-style">Reward<span class="icon icon-angle-down"></span> 
</span> 
</a> 
</li> 
 <li role="menuitem" class=" unifiednav__item-wrap " data-auto="more-pages" data-depth="0"> <a href="https://partners.hello-doordash.com/api/mailings/click/PMRGSZBCHIYTCMZQGY3TSOBMEJ2XE3BCHIRGQ5DUOBZTULZPN5ZGIZLSFZXW43DJNZSS6YTVONUW4ZLTOMXW22LUMFZS22DJNVQWYYLZMFXC223JORRWQZLOFUYTCNRUGU2DMMZCFQRG64THEI5CENJVMI3TOYJQGMWTQOBWGEWTIZDFMEWTQNRXMQWWEYRQGBRTEZLBMQ4DMYRCFQRHMZLSONUW63RCHIRDIIRMEJZWSZZCHIRGK53NG52EI6TENVVWSLLQPBJG2RKDNFIUMURZMZ2TIM3JKZXGQ4LFOJUE632KJJFWKZ2FHURH2===" class="unifiednav__item  dmUDNavigationItem_010101669821  " target="_blank" data-target-page-alias=""> <span class="nav-item-text " data-link-text="
         Doordash
        " data-auto="page-text-style">Doordash<span class="icon icon-angle-down"></span> 
</span> 
</a> 
</li> 
 <li role="menuitem" class=" unifiednav__item-wrap " data-auto="more-pages" data-depth="0"> <a href="https://www.order.store/store/mitas-himalayan-kitchen/j_eXMIW4TkKY_A7vMRc5_A" class="unifiednav__item  dmUDNavigationItem_010101473552  " target="_blank" data-target-page-alias=""> <span class="nav-item-text " data-link-text="UberEats" data-auto="page-text-style">UberEats<span class="icon icon-angle-down"></span> 
</span> 
</a> 
</li> 
</ul> 
</nav> 
</div> 
</div> 
</div> 
 <div class="dmRespRow u_1676049285" style="text-align: center;" id="1676049285"> <div class="dmRespColsWrapper" id="1888750820"> <div class="dmRespCol empty-column small-12 medium-12 large-12" id="1088595535"></div> 
</div> 
</div> 
</div> 
 <div class="layout-drawer-overlay" id="layout-drawer-overlay"></div> 
</div> 
 <div class="site_content"> <div id="hamburger-header-container" class="showOnMedium hamburger-header-container p_hfcontainer"> <div id="hamburger-header" class="hamburger-header p_hfcontainer" layout="44dc38f951e9489490b055748e10ba9f===header" data-scrollable-target="body" data-scroll-responder-id="hamburger-header"> <div class="u_1705692124 dmRespRow" style="text-align: center;" id="1705692124"> <div class="dmRespColsWrapper" id="1469942216"> <div class="u_1655486006 dmRespCol small-12 large-10 medium-10" id="1655486006"> <div class="u_1923160809 imageWidget align-center" data-element-type="image" data-widget-type="image" id="1923160809" data-binding="W3siYmluZGluZ05hbWUiOiJpbWFnZSIsInZhbHVlIjoic2l0ZV9pbWFnZXMubG9nbyJ9XQ=="> <a href="/" id="1573522578" file="false"><img src="https://lirp.cdn-website.com/e384b44b/dms3rep/multi/opt/large-Logo-Himalaya-2+-+Edited+White-1920w.png" id="1761992403" class="" data-dm-image-path="https://irp.cdn-website.com/e384b44b/dms3rep/multi/large-Logo-Himalaya-2+-+Edited+White.png" width="196" height="33" alt="logo" data-diy-image="" onerror="handleImageLoadError(this)"/></a> 
</div> 
</div> 
 <div class="u_1570920501 dmRespCol empty-column small-12 large-1 medium-1" id="1570920501"></div> 
 <div class="u_1524741679 dmRespCol small-12 large-1 medium-1" id="1524741679"> <div data-element-type="spacer" class="dmSpacer" id="1482400632"></div> 
</div> 
</div> 
</div> 
</div> 
</div> 
 <div class="dmHeaderContainer fHeader d-header-wrapper showOnLarge"> <div id="hcontainer" class="u_hcontainer dmHeader p_hfcontainer" freeheader="true" headerlayout="b58ba5b5703b4cd7b5f5f7951565dc87===horizontal-layout-5" layout="29bf4fa55d88450885fbcefc03615aa2===header" mini-header-show-only-navigation-row="true" data-scrollable-target="body" data-scrollable-target-threshold="1" data-scroll-responder-id="1" preserve-sticky-header="true" logo-size-target="77%"> <div dm:templateorder="85" class="dmHeaderResp dmHeaderStack noSwitch" id="1709005236"> <div class="u_1108793676 dmRespRow dmDefaultListContentRow fullBleedChanged fullBleedMode" style="text-align:center" id="1108793676"> <div class="dmRespColsWrapper" id="1107074743"> <div class="u_1047626887 small-12 dmRespCol large-1 medium-1" id="1047626887"> <div class="u_1699608514 imageWidget align-center" data-widget-type="image" id="1699608514" data-element-type="image"> <a href="/" id="1205720555"><img src="https://lirp.cdn-website.com/e384b44b/dms3rep/multi/opt/Blank-2b32aa7c-1920w.png" id="1440686295" class="" data-dm-image-path="https://irp.cdn-website.com/e384b44b/dms3rep/multi/Blank-2b32aa7c.png" width="570" height="177" alt="logo" onerror="handleImageLoadError(this)"/></a> 
</div> 
</div> 
 <div class="u_1797454970 dmRespCol small-12 large-9 medium-9" id="1797454970"> <span id="1721344478"></span> 
 <nav class="u_1351338839 effect-none main-navigation unifiednav dmLinksMenu" role="navigation" layout-main="horizontal_nav_layout_1" layout-sub="submenu_horizontal_1" data-show-vertical-sub-items="HOVER" id="1351338839" dmle_extension="onelinksmenu" data-element-type="onelinksmenu" data-logo-src="" alt="" data-nav-structure="HORIZONTAL" wr="true" icon="true" surround="true" adwords="" navigation-id="unifiedNav"> <ul role="menubar" class="unifiednav__container  " data-auto="navigation-pages"> <li role="menuitem" class=" unifiednav__item-wrap " data-auto="more-pages" data-depth="0"> <a href="/" class="unifiednav__item  dmNavItemSelected  dmUDNavigationItem_00  " target="" data-target-page-alias="" data-auto="selected-page"> <span class="nav-item-text " data-link-text="
         Home
        " data-auto="page-text-style">Home<span class="icon icon-angle-down"></span> 
</span> 
</a> 
</li> 
 <li role="menuitem" class=" unifiednav__item-wrap " data-auto="more-pages" data-depth="0"> <a href="/menu" class="unifiednav__item  dmUDNavigationItem_010101326518  " target="" data-target-page-alias=""> <span class="nav-item-text " data-link-text="
         Menu
        " data-auto="page-text-style">Menu<span class="icon icon-angle-down"></span> 
</span> 
</a> 
</li> 
 <li role="menuitem" class=" unifiednav__item-wrap " data-auto="more-pages" data-depth="0"> <a href="/catering-online-order" class="unifiednav__item  dmUDNavigationItem_010101500621  " target="" data-target-page-alias=""> <span class="nav-item-text " data-link-text="Catering" data-auto="page-text-style">Catering<span class="icon icon-angle-down"></span> 
</span> 
</a> 
</li> 
 <li role="menuitem" class=" unifiednav__item-wrap " data-auto="more-pages" data-depth="0"> <a href="/about" class="unifiednav__item  dmUDNavigationItem_010101436714  " target="" data-target-page-alias=""> <span class="nav-item-text " data-link-text="
         About
        " data-auto="page-text-style">About<span class="icon icon-angle-down"></span> 
</span> 
</a> 
</li> 
 <li role="menuitem" class=" unifiednav__item-wrap " data-auto="more-pages" data-depth="0"> <a href="/contact" class="unifiednav__item  dmUDNavigationItem_010101943230  " target="" data-target-page-alias=""> <span class="nav-item-text " data-link-text="
         Contact
        " data-auto="page-text-style">Contact<span class="icon icon-angle-down"></span> 
</span> 
</a> 
</li> 
 <li role="menuitem" class=" unifiednav__item-wrap " data-auto="more-pages" data-depth="0"> <a href="https://squareup.com/loyalty/MLHWR7C0E9HY7" class="unifiednav__item  dmUDNavigationItem_0101019020  " target="_blank" data-target-page-alias=""> <span class="nav-item-text " data-link-text="Reward" data-auto="page-text-style">Reward<span class="icon icon-angle-down"></span> 
</span> 
</a> 
</li> 
 <li role="menuitem" class=" unifiednav__item-wrap " data-auto="more-pages" data-depth="0"> <a href="https://partners.hello-doordash.com/api/mailings/click/PMRGSZBCHIYTCMZQGY3TSOBMEJ2XE3BCHIRGQ5DUOBZTULZPN5ZGIZLSFZXW43DJNZSS6YTVONUW4ZLTOMXW22LUMFZS22DJNVQWYYLZMFXC223JORRWQZLOFUYTCNRUGU2DMMZCFQRG64THEI5CENJVMI3TOYJQGMWTQOBWGEWTIZDFMEWTQNRXMQWWEYRQGBRTEZLBMQ4DMYRCFQRHMZLSONUW63RCHIRDIIRMEJZWSZZCHIRGK53NG52EI6TENVVWSLLQPBJG2RKDNFIUMURZMZ2TIM3JKZXGQ4LFOJUE632KJJFWKZ2FHURH2===" class="unifiednav__item  dmUDNavigationItem_010101669821  " target="_blank" data-target-page-alias=""> <span class="nav-item-text " data-link-text="
         Doordash
        " data-auto="page-text-style">Doordash<span class="icon icon-angle-down"></span> 
</span> 
</a> 
</li> 
 <li role="menuitem" class=" unifiednav__item-wrap " data-auto="more-pages" data-depth="0"> <a href="https://www.order.store/store/mitas-himalayan-kitchen/j_eXMIW4TkKY_A7vMRc5_A" class="unifiednav__item  dmUDNavigationItem_010101473552  " target="_blank" data-target-page-alias=""> <span class="nav-item-text " data-link-text="UberEats" data-auto="page-text-style">UberEats<span class="icon icon-angle-down"></span> 
</span> 
</a> 
</li> 
</ul> 
</nav> 
</div> 
 <div class="u_1470331130 dmRespCol small-12 large-2 medium-2" id="1470331130"> <a data-display-type="block" class="u_1098755880 align-center dmButtonLink dmWidget dmWwr default dmOnlyButton dmDefaultGradient" file="false" href="https://mitas-indo-nepali-kitchen-llc.square.site" data-element-type="dButtonLinkId" id="1098755880"> <span class="iconBg" id="1385025987"> <span class="icon hasFontIcon icon-star" id="1348432046"></span> 
</span> 
 <span class="text" id="1443830934">Order online</span> 
</a> 
</div> 
</div> 
</div> 
</div> 
</div> 
</div> 
 <div class="stickyHeaderSpacer" id="stickyHeaderSpacer" data-new="true"></div> 
 <div dmwrapped="true" id="1901957768" class="dmBody u_dmStyle_template_home dm-home-page" themewaschanged="true" desktop-global-classes="header-over-content" tablet-global-classes="header-over-content" mobile-global-classes="header-over-content"> <div id="allWrapper" class="allWrapper"><!-- navigation placeholders --> <div id="dm_content" class="dmContent"> <div dm:templateorder="170" class="dmHomeRespTmpl mainBorder dmRespRowsWrapper dmFullRowRespTmpl" id="1716942098"> <div class="u_1175519632 dmRespRow fullBleedChanged fullBleedMode hasBackgroundOverlay" id="1175519632"> <div class="dmRespColsWrapper" id="1151051667"> <div class="u_1710916498 dmRespCol small-12 medium-12 large-12" id="1710916498"> <div id="1724299654" dmle_extension="ssrimageslider" data-element-type="ssrimageslider" class="u_1724299654" data-anim-extended="eyJkZXNrdG9wIjp7InRyaWdnZXIiOiJlbnRyYW5jZSIsImFuaW1hdGlvbiI6ImZhZGVJbkNvbWJvIiwiZGlyIjoiaW4tcGxhY2UifX0="> <span id="ssrWrap-1724299654"> <style data-styled="true" data-styled-version="5.3.11">@media all{.dmHqPN{height:100%;-webkit-align-items:center;-webkit-box-align:center;-ms-flex-align:center;align-items:center;background-repeat:no-repeat;background-size:100%;position:relative;width:100%;}}/*!sc*/
@media all{.dqVOmB{height:100%;width:100%;box-sizing:border-box;}}/*!sc*/
@media all{.fEwegE{width:100%;height:100%;position:relative;overflow:hidden;}}/*!sc*/
@media (max-width:767px){.fEwegE{width:100%;}}/*!sc*/
@media all{.gMQzZl{display:-webkit-box;display:-webkit-flex;display:-ms-flexbox;display:flex;position:absolute;left:-0%;top:0;right:-500%;bottom:0;-webkit-flex-direction:row;-ms-flex-direction:row;flex-direction:row;-webkit-transition:left,top,right,bottom;transition:left,top,right,bottom;-webkit-transition-duration:1s;transition-duration:1s;-webkit-transition-timing-function:ease-in-out;transition-timing-function:ease-in-out;}}/*!sc*/
@media all{.gwCzaK{position:relative;-webkit-flex:1;-ms-flex:1;flex:1;}}/*!sc*/
@media all{.bqnjbi{position:absolute;top:0;bottom:0;left:0;right:0;}}/*!sc*/
@media (max-width:767px){.bqnjbi{left:0;right:0;}}/*!sc*/
@media all{.gPtwjB{width:100%;height:100%;position:relative;display:block;overflow:hidden;}}/*!sc*/
@media all{.gISPYK{background-color:#eee;overflow:hidden;position:absolute;left:0;bottom:0;top:0;right:0;border-width:3px;}}/*!sc*/
@media all{.bshgWi{position:absolute;top:0;bottom:0;left:0;right:0;background-color:rgba(0,0,0,0.58);}}/*!sc*/
@media all{.kiZeaj{display:-webkit-box;display:-webkit-flex;display:-ms-flexbox;display:flex;visibility:visible;position:absolute;left:0;bottom:35px;padding-block-start:35px;padding-inline:24px;top:60px;right:0;-webkit-align-items:center;-webkit-box-align:center;-ms-flex-align:center;align-items:center;-webkit-flex-direction:column;-ms-flex-direction:column;flex-direction:column;-webkit-box-pack:center;-webkit-justify-content:center;-ms-flex-pack:center;justify-content:center;text-align:center;}}/*!sc*/
@media (min-width:1025px){.kiZeaj{padding-left:250px;padding-right:250px;}}/*!sc*/
@media (max-width:1024px) and (min-width:768px){.kiZeaj{padding-left:250px;padding-right:250px;}}/*!sc*/
@media (max-width:767px){.kiZeaj{top:0;}}/*!sc*/
@media all{.eNPxal{object-fit:cover;display:block;width:100%;height:100%;}}/*!sc*/
@media all{.jsZpJH{display:-webkit-box;display:-webkit-flex;display:-ms-flexbox;display:flex;visibility:hidden;position:absolute;left:0;bottom:35px;padding-block-start:35px;padding-inline:24px;top:60px;right:0;-webkit-align-items:center;-webkit-box-align:center;-ms-flex-align:center;align-items:center;-webkit-flex-direction:column;-ms-flex-direction:column;flex-direction:column;-webkit-box-pack:center;-webkit-justify-content:center;-ms-flex-pack:center;justify-content:center;text-align:center;}}/*!sc*/
@media (min-width:1025px){.jsZpJH{padding-left:250px;padding-right:250px;}}/*!sc*/
@media (max-width:1024px) and (min-width:768px){.jsZpJH{padding-left:250px;padding-right:250px;}}/*!sc*/
@media (max-width:767px){.jsZpJH{top:0;}}/*!sc*/
@media all{.gzPFTU{display:-webkit-box;display:-webkit-flex;display:-ms-flexbox;display:flex;-webkit-box-pack:center;-webkit-justify-content:center;-ms-flex-pack:center;justify-content:center;-webkit-align-items:center;-webkit-box-align:center;-ms-flex-align:center;align-items:center;gap:8px;position:absolute;bottom:22px;width:100%;}}/*!sc*/
data-styled.g1[id="sc-aXZVg"]{content:"dmHqPN,dqVOmB,fEwegE,gMQzZl,gwCzaK,bqnjbi,gPtwjB,gISPYK,bshgWi,kiZeaj,eNPxal,jsZpJH,gzPFTU,"}/*!sc*/
@media all{.ieIOVf{object-fit:cover;display:block;width:100%;height:100%;}}/*!sc*/
data-styled.g3[id="sc-eqUAAy"]{content:"ieIOVf,"}/*!sc*/
@media all{#dm#dm#dm .gNxaUx.gNxaUx{padding:unset;background-color:currentColor;border:unset;cursor:pointer;border-radius:50%;width:8px;height:8px;box-shadow:0px 0px 2px rgba(24,39,75,0.3),0px 0px 3px rgba(24,39,75,0.04);color:white;}}/*!sc*/
@media all{#dm#dm#dm .cgAWng.cgAWng{padding:unset;background-color:#CED6D9;border:unset;cursor:pointer;border-radius:50%;width:8px;height:8px;box-shadow:0px 0px 2px rgba(24,39,75,0.3),0px 0px 3px rgba(24,39,75,0.04);}}/*!sc*/
data-styled.g8[id="sc-kAyceB"]{content:"gNxaUx,cgAWng,"}/*!sc*/
@media all{#dm#dm#dm .gExtix.gExtix{margin:0;margin-block-end:8px;color:white;font-weight:700;}}/*!sc*/
@media all{#dm#dm#dm .emcOBO.emcOBO{color:var(--color_1);}#dm#dm#dm .emcOBO.emcOBO p{margin-block:0;}}/*!sc*/
@media all{#dm#dm#dm .jjCrPo.jjCrPo{max-width:revert;white-space:revert;display:inline-block;-webkit-box-flex:1;-webkit-flex-grow:1;-ms-flex-positive:1;flex-grow:1;}}/*!sc*/
data-styled.g20[id="sc-eldPxv"]{content:"gExtix,emcOBO,jjCrPo,"}/*!sc*/
@media all{#dm#dm#dm .jA-dWuM.jA-dWuM{display:-webkit-box;display:-webkit-flex;display:-ms-flexbox;display:flex;-webkit-align-items:center;-webkit-box-align:center;-ms-flex-align:center;align-items:center;-webkit-box-pack:center;-webkit-justify-content:center;-ms-flex-pack:center;justify-content:center;min-width:150px;width:auto;padding-inline-start:20px;padding-inline-end:20px;margin:0;margin-block-start:24px;}#dm#dm#dm .jA-dWuM.jA-dWuM:after{display:none;}}/*!sc*/
data-styled.g25[id="sc-feUZmu"]{content:"jA-dWuM,"}/*!sc*/</style> 
 <div style="height:100%;overflow:hidden" class="sc-aXZVg"> <div data-auto="actual-slider" class="sc-aXZVg dmHqPN"> <div class="sc-aXZVg dqVOmB"> <div class="sc-aXZVg fEwegE"> <div data-auto="slider-filmRole" class="sc-aXZVg gMQzZl"> <div data-auto="slideSlot 0 slideSlotActive" class="sc-aXZVg gwCzaK"> <div class="sc-aXZVg bqnjbi"> <div data-auto="ssr-slide-74786" class="sc-aXZVg gPtwjB"> <div data-grab="slide-media-container" class="sc-aXZVg gISPYK"><img data-grab="slide-media" src="https://lirp.cdn-website.com/e384b44b/dms3rep/multi/opt/Collage-1920w.jpg" class="sc-eqUAAy ieIOVf" onerror="handleImageLoadError(this)"/> <div data-grab="slide-overlay" class="sc-aXZVg bshgWi"></div> 
</div> 
 <div class="sc-aXZVg kiZeaj animated fadeInUp" data-grab="slideContentContainer"> <h3 data-auto="title" data-grab="title" class="sc-eldPxv gExtix">LUNCH/DINNER SPECIAL</h3> 
 <div data-auto="desc" data-grab="description" class="sc-eldPxv emcOBO"> <p>Everyday</p> 
 <p>11AM - 1PM / 4PM - 7PM</p> 
</div> 
 <a href="https://irp.cdn-website.com/e384b44b/files/uploaded/Lunch-Dinner.png" type="file" link_type="file" data-auto="button-root" data-grab="button-root" class="sc-feUZmu jA-dWuM dmWidget    " data-disabled="false" data-after-text="true"> <span data-auto="button-text" data-grab="button-text" class="sc-eldPxv jjCrPo text">Click for details</span> 
</a> 
</div> 
</div> 
</div> 
</div> 
 <div data-auto="slideSlot 1" class="sc-aXZVg gwCzaK"> <div class="sc-aXZVg bqnjbi"> <div data-auto="ssr-slide-10997" class="sc-aXZVg gPtwjB"> <div data-grab="slide-media-container" class="sc-aXZVg gISPYK"> <div data-grab="slide-media" class="sc-aXZVg eNPxal"></div> 
 <div data-grab="slide-overlay" class="sc-aXZVg bshgWi"></div> 
</div> 
 <div class="sc-aXZVg jsZpJH" data-grab="slideContentContainer"> <h3 data-auto="title" data-grab="title" class="sc-eldPxv gExtix">HAPPY HOURS</h3> 
 <div data-auto="desc" data-grab="description" class="sc-eldPxv emcOBO"> <p>Everyday</p> 
 <p>1PM - 2PM / 8PM - 9PM</p> 
 <p>Get a free bottled drink for dining in</p> 
</div> 
 <a href="https://irp.cdn-website.com/e384b44b/files/uploaded/Everyday-89814442.png" type="file" link_type="file" data-auto="button-root" data-grab="button-root" class="sc-feUZmu jA-dWuM dmWidget    " data-disabled="false" data-after-text="true"> <span data-auto="button-text" data-grab="button-text" class="sc-eldPxv jjCrPo text">Click for details</span> 
</a> 
</div> 
</div> 
</div> 
</div> 
 <div data-auto="slideSlot 2" class="sc-aXZVg gwCzaK"> <div class="sc-aXZVg bqnjbi"> <div data-auto="ssr-slide-37621" class="sc-aXZVg gPtwjB"> <div data-grab="slide-media-container" class="sc-aXZVg gISPYK"> <div data-grab="slide-media" class="sc-aXZVg eNPxal"></div> 
 <div data-grab="slide-overlay" class="sc-aXZVg bshgWi"></div> 
</div> 
 <div class="sc-aXZVg jsZpJH" data-grab="slideContentContainer"> <h3 data-auto="title" data-grab="title" class="sc-eldPxv gExtix">MITA'S MONDAY: 10% OFF ON ENTIRE DINE-IN BILL</h3> 
 <div data-auto="desc" data-grab="description" class="sc-eldPxv emcOBO"> <p>Every Monday, you can enjoy a delightful 10% off the entire bill for dine-in!</p> 
 <p>Whether you're a longtime fan of Himalayan cuisine or a curious newcomer, Mita's Himalayan Kitchen has something extraordinary to offer. From the warm and hearty flavors of Nepali Momo dumplings to the aromatic and savory curries, you'll find a diverse and delicious menu that will</p> 
 <p>leave you craving more.</p> 
</div> 
 <a href="https://irp.cdn-website.com/e384b44b/files/uploaded/Mita-s Monday-a3cdc367.png" type="file" link_type="file" data-auto="button-root" data-grab="button-root" class="sc-feUZmu jA-dWuM dmWidget    " data-disabled="false" data-after-text="true"> <span data-auto="button-text" data-grab="button-text" class="sc-eldPxv jjCrPo text">Click here</span> 
</a> 
</div> 
</div> 
</div> 
</div> 
 <div data-auto="slideSlot 3" class="sc-aXZVg gwCzaK"> <div class="sc-aXZVg bqnjbi"> <div data-auto="ssr-slide-24739" class="sc-aXZVg gPtwjB"> <div data-grab="slide-media-container" class="sc-aXZVg gISPYK"> <div data-grab="slide-media" class="sc-aXZVg eNPxal"></div> 
 <div data-grab="slide-overlay" class="sc-aXZVg bshgWi"></div> 
</div> 
 <div class="sc-aXZVg jsZpJH" data-grab="slideContentContainer"> <h3 data-auto="title" data-grab="title" class="sc-eldPxv gExtix">WOW WEDNESDAY</h3> 
 <div data-auto="desc" data-grab="description" class="sc-eldPxv emcOBO"> <p>Every Wednesday, get a free select item for dining in.</p> 
</div> 
 <a href="https://irp.cdn-website.com/e384b44b/files/uploaded/Wow Wednesday-371e438d.png" type="file" link_type="file" data-auto="button-root" data-grab="button-root" class="sc-feUZmu jA-dWuM dmWidget    " data-disabled="false" data-after-text="true"> <span data-auto="button-text" data-grab="button-text" class="sc-eldPxv jjCrPo text">Click for details</span> 
</a> 
</div> 
</div> 
</div> 
</div> 
 <div data-auto="slideSlot 4" class="sc-aXZVg gwCzaK"> <div class="sc-aXZVg bqnjbi"> <div data-auto="ssr-slide-21559" class="sc-aXZVg gPtwjB"> <div data-grab="slide-media-container" class="sc-aXZVg gISPYK"> <div data-grab="slide-media" class="sc-aXZVg eNPxal"></div> 
 <div data-grab="slide-overlay" class="sc-aXZVg bshgWi"></div> 
</div> 
 <div class="sc-aXZVg jsZpJH" data-grab="slideContentContainer"> <h3 data-auto="title" data-grab="title" class="sc-eldPxv gExtix">BYOB (Bring Your Own Bottle)</h3> 
 <a href="https://irp.cdn-website.com/e384b44b/files/uploaded/BYOB Bring your own bottle-6cf8683d.png" type="file" link_type="file" data-auto="button-root" data-grab="button-root" class="sc-feUZmu jA-dWuM dmWidget    " data-disabled="false" data-after-text="true"> <span data-auto="button-text" data-grab="button-text" class="sc-eldPxv jjCrPo text">Click here</span> 
</a> 
</div> 
</div> 
</div> 
</div> 
 <div data-auto="slideSlot 5" class="sc-aXZVg gwCzaK"> <div class="sc-aXZVg bqnjbi"> <div data-auto="ssr-slide-8262" class="sc-aXZVg gPtwjB"> <div data-grab="slide-media-container" class="sc-aXZVg gISPYK"> <div data-grab="slide-media" class="sc-aXZVg eNPxal"></div> 
 <div data-grab="slide-overlay" class="sc-aXZVg bshgWi"></div> 
</div> 
 <div class="sc-aXZVg jsZpJH" data-grab="slideContentContainer"> <h3 data-auto="title" data-grab="title" class="sc-eldPxv gExtix">Check Our Catering Menu</h3> 
 <div data-auto="desc" data-grab="description" class="sc-eldPxv emcOBO"> <p>Amazing for big events!!! Click on catering to place order. Select items, fill up required information, select date and time for pickup, complete payment and your catering order would be ready for pick up on specified date and time. Note: order should be place at least 2 days ahead of pickup date.</p> 
</div> 
 <a href="https://irp.cdn-website.com/e384b44b/files/uploaded/Mita-s Catering.png" type="file" link_type="file" data-auto="button-root" data-grab="button-root" class="sc-feUZmu jA-dWuM dmWidget    " data-disabled="false" data-after-text="true"> <span data-auto="button-text" data-grab="button-text" class="sc-eldPxv jjCrPo text">Click for details</span> 
</a> 
</div> 
</div> 
</div> 
</div> 
</div> 
</div> 
</div> 
 <div data-auto="pagination-bullets-base-container" data-grab="pagination-container" class="sc-aXZVg gzPFTU"> <button data-grab="pagination-button-bullet active" data-auto="pagination-button-bullet 0 active" aria-label="go to slide 1" class="sc-kAyceB gNxaUx"></button> 
 <button data-grab="pagination-button-bullet" data-auto="pagination-button-bullet 1" aria-label="go to slide 2" class="sc-kAyceB cgAWng"></button> 
 <button data-grab="pagination-button-bullet" data-auto="pagination-button-bullet 2" aria-label="go to slide 3" class="sc-kAyceB cgAWng"></button> 
 <button data-grab="pagination-button-bullet" data-auto="pagination-button-bullet 3" aria-label="go to slide 4" class="sc-kAyceB cgAWng"></button> 
 <button data-grab="pagination-button-bullet" data-auto="pagination-button-bullet 4" aria-label="go to slide 5" class="sc-kAyceB cgAWng"></button> 
 <button data-grab="pagination-button-bullet" data-auto="pagination-button-bullet 5" aria-label="go to slide 6" class="sc-kAyceB cgAWng"></button> 
</div> 
</div> 
</div> 
 <script data-role="hydration">;window?.waitForDeferred?.('ssrLibrariesLoaded', () => {window.SSRRuntime.RuntimeReactHelpers.hydrate({"type":"SSR_IMAGE_SLIDER","props":{"layout":"LAYOUT_1","autoPagination":{"on":true,"intervalInSeconds":5,"pauseOnHover":false},"slidesData":[{"uuid":"74786","title":"LUNCH/DINNER SPECIAL","desc":"<p>            Everyday</p><p>11AM - 1PM / 4PM - 7PM</p>","media":{"imgSrc":"https://lirp.cdn-website.com/e384b44b/dms3rep/multi/opt/Collage-1920w.jpg","alt":null,"vidSrc":null,"lazy":false,"type":"IMAGE"},"button":{"text":"Click for details"},"linkDomAttributes":{"href":"https://irp.cdn-website.com/e384b44b/files/uploaded/Lunch-Dinner.png","type":"file","target":null,"link_type":"file","popup_target":null},"showButton":true},{"uuid":"10997","title":"HAPPY HOURS","desc":"<p>Everyday</p><p>1PM - 2PM / 8PM - 9PM</p><p>Get a free bottled drink for dining in</p>","media":{"imgSrc":"https://lirp.cdn-website.com/e384b44b/dms3rep/multi/opt/Collage-1920w.jpg","alt":null,"vidSrc":null,"lazy":false,"type":"IMAGE"},"button":{"text":"Click for details"},"linkDomAttributes":{"href":"https://irp.cdn-website.com/e384b44b/files/uploaded/Everyday-89814442.png","type":"file","target":null,"link_type":"file","popup_target":null},"showButton":true},{"uuid":"37621","title":"MITA'S MONDAY: 10% OFF ON ENTIRE DINE-IN BILL","desc":"<p>Every Monday, you can enjoy a delightful 10% off the entire bill for dine-in!</p><p>Whether you're a longtime fan of Himalayan cuisine or a curious newcomer, Mita's Himalayan Kitchen has something extraordinary to offer. From the warm and hearty flavors of Nepali Momo dumplings to the aromatic and savory curries, you'll find a diverse and delicious menu that will</p><p>leave you craving more.</p>","media":{"imgSrc":"https://lirp.cdn-website.com/e384b44b/dms3rep/multi/opt/Collage-1920w.jpg","alt":null,"vidSrc":null,"lazy":false,"type":"IMAGE"},"button":{"text":"Click here"},"linkDomAttributes":{"href":"https://irp.cdn-website.com/e384b44b/files/uploaded/Mita-s Monday-a3cdc367.png","type":"file","target":null,"link_type":"file","popup_target":null},"showButton":true},{"uuid":"24739","title":"WOW WEDNESDAY","desc":"<p>Every Wednesday, get a free select item for dining in.</p>","media":{"imgSrc":"https://lirp.cdn-website.com/e384b44b/dms3rep/multi/opt/Collage-1920w.jpg","alt":null,"vidSrc":null,"lazy":false,"type":"IMAGE"},"button":{"text":"Click for details"},"linkDomAttributes":{"href":"https://irp.cdn-website.com/e384b44b/files/uploaded/Wow Wednesday-371e438d.png","type":"file","target":null,"link_type":"file","popup_target":null},"showButton":true},{"uuid":"21559","title":"BYOB (Bring Your Own Bottle)","media":{"imgSrc":"https://lirp.cdn-website.com/e384b44b/dms3rep/multi/opt/Collage-1920w.jpg","alt":null,"vidSrc":null,"lazy":false,"type":"IMAGE"},"button":{"text":"Click here"},"linkDomAttributes":{"href":"https://irp.cdn-website.com/e384b44b/files/uploaded/BYOB Bring your own bottle-6cf8683d.png","type":"file","target":null,"link_type":"file","popup_target":null},"showButton":true},{"uuid":"8262","title":"Check Our Catering Menu","desc":"<p>Amazing for big events!!! Click on catering to place order. Select items, fill up required information, select date and time for pickup, complete payment and your catering order would be ready for pick up on specified date and time. Note: order should be place at least 2 days ahead of pickup date.</p>","media":{"imgSrc":"https://lirp.cdn-website.com/e384b44b/dms3rep/multi/opt/Collage-1920w.jpg","alt":null,"vidSrc":null,"lazy":false,"type":"IMAGE"},"button":{"text":"Click for details"},"linkDomAttributes":{"href":"https://irp.cdn-website.com/e384b44b/files/uploaded/Mita-s Catering.png","type":"file","target":null,"link_type":"file","popup_target":null},"showButton":true}],"animationType":"slide","contentAnimationTypeCssClass":"fadeInUp","bindingSource":null,"paginationShow":"always","arrowStyle":"arrow_thin","slotsInFrame":null,"_styles":{"slide_contentContainer":{"desktop":{"padding-left":"250px","padding-right":"250px"},"tablet":{"padding-left":"250px","padding-right":"250px"}},"slide_title":{"common":{"fontWeight":"700"}},"slide_desc":{"common":{"color":"var(--color_1)"}},"slide_mediaContainer":{"common":{"border-top-width":null,"border-right-width":null,"border-bottom-width":null,"border-width":"3px","border-left-width":null}},"slide_media":{"common":{"object-fit":"cover"}},"slide_overlay":{"common":{"background-color":"rgba(0, 0, 0, 0.58)"}}}},"id":"1724299654"}, {"observer":false})});</script> 
</span> 
</div> 
 <div class="u_1526983883 dmNewParagraph hide-for-small" data-element-type="paragraph" data-version="5" id="1526983883" style="transition: none 0s ease 0s; text-align: left; display: block;"> <h1 class="text-align-center m-text-align-center m-size-40 size-50" style="line-height: 0.8;"><span style="display: initial; color: rgba(0, 0, 0, 0);" class="font-size-50 m-font-size-40" m-font-size-set="true">Mita's Himalayan Kitchen</span></h1> 
</div> 
 <div class="u_1456347215 dmNewParagraph" data-element-type="paragraph" data-version="5" id="1456347215" style="transition: opacity 1s ease-in-out 0s;"> <h1 class="text-align-center size-18 m-size-14"><span style="display: unset; color: rgba(0, 0, 0, 0);" class="font-size-18 m-font-size-14">Mita's Himalayan Kitchen</span></h1> 
</div> 
 <div class="u_1064936565 imageWidget align-center" data-element-type="image" data-widget-type="image" id="1064936565"><img src="https://lirp.cdn-website.com/e384b44b/dms3rep/multi/opt/large-Logo-Himalaya-2+-+Edited+2+White-1920w.png" alt="" id="1045677264" class="" data-dm-image-path="https://irp.cdn-website.com/e384b44b/dms3rep/multi/large-Logo-Himalaya-2+-+Edited+2+White.png" width="570" height="522" onerror="handleImageLoadError(this)"/></div> 
 <div class="u_1636703256 dmRespRow" id="1636703256" mode="1"> <div class="dmRespColsWrapper" id="1419387904"> <div class="dmRespCol large-6 medium-6 small-12" id="1798447053"> <a data-display-type="block" class="u_1877165583 align-center dmButtonLink dmWidget dmWwr default dmOnlyButton dmDefaultGradient" file="false" href="https://mitas-indo-nepali-kitchen-llc.square.site" data-element-type="dButtonLinkId" id="1877165583"> <span class="iconBg" id="1149663812"> <span class="icon hasFontIcon icon-star" id="1177108842"></span> 
</span> 
 <span class="text" id="1236842668">Order online</span> 
</a> 
</div> 
 <div class="dmRespCol large-6 medium-6 small-12" id="1947241753"> <a data-display-type="block" class="u_1163061705 align-center dmButtonLink dmWidget dmWwr default dmOnlyButton dmDefaultGradient" file="false" href="/menu" data-element-type="dButtonLinkId" id="1163061705"> <span class="iconBg" id="1598635924"> <span class="icon hasFontIcon icon-star" id="1708402071"></span> 
</span> 
 <span class="text" id="1778415681">See menu</span> 
</a> 
</div> 
</div> 
</div> 
 <div class="u_1038248483 dmRespRow fullBleedChanged fullBleedMode" id="1038248483"> <div class="dmRespColsWrapper" id="1315803587"> <div class="dmRespCol large-12 medium-12 small-12" id="1435747648"> <div data-element-type="spacer" class="u_1938601863 dmSpacer" id="1938601863"></div> 
</div> 
</div> 
</div> 
</div> 
</div> 
</div> 
 <div class="dmRespRow u_1074049312 fullBleedChanged fullBleedMode" id="1074049312"> <div class="dmRespColsWrapper" id="1606853711"> <div class="dmRespCol large-12 medium-12 small-12" id="1953794418"> <div class="u_1645777280 dmRespRow fullBleedChanged fullBleedMode" id="1645777280"> <div class="dmRespColsWrapper" id="1768834645"> <div class="u_1614699839 dmRespCol small-12 large-3 medium-3" id="1614699839"> <div class="u_1343753636 imageWidget align-center hide-for-small" data-element-type="image" data-widget-type="image" id="1343753636"><img src="https://lirp.cdn-website.com/e384b44b/dms3rep/multi/opt/large-Logo-Himalaya-2+-+Edited+2+White-1920w.png" alt="" id="1533841361" class="" data-dm-image-path="https://irp.cdn-website.com/e384b44b/dms3rep/multi/large-Logo-Himalaya-2+-+Edited+2+White.png" width="570" height="522" onerror="handleImageLoadError(this)"/></div> 
 <div class="u_1542019906 imageWidget align-center hide-for-medium hide-for-large" data-element-type="image" data-widget-type="image" id="1542019906"><img src="https://lirp.cdn-website.com/e384b44b/dms3rep/multi/opt/large-Logo-Himalaya--Mountains---Edited-3-White-1920w.png" alt="" id="1609642461" class="" data-dm-image-path="https://irp.cdn-website.com/e384b44b/dms3rep/multi/large-Logo-Himalaya--Mountains---Edited-3-White.png" width="570" height="219" onerror="handleImageLoadError(this)"/></div> 
</div> 
 <div class="u_1776394560 dmRespCol small-12 large-8 medium-8" id="1776394560"> <div class="u_1206198029 dmNewParagraph" data-element-type="paragraph" data-version="5" id="1206198029" style="transition: none 0s ease 0s; text-align: left; display: block;"> <h4 class="text-align-left" style="line-height: 1.5;"><span style="font-weight: normal; display: initial;">Welcome to Mita's Himalayan Kitchen, where we bring the flavors and aromas of Nepal and India to your plate. Our passion for&nbsp;</span><a href="" target="_blank" runtime_url="" style="font-weight: normal; display: initial;">great food</a><span style="font-weight: normal; display: initial;">&nbsp;is reflected in every dish we serve, as we strive to create a truly&nbsp;</span><a href="" target="_blank" runtime_url="" style="font-weight: normal; display: initial;">authentic experience</a><span style="font-weight: normal; display: initial;">&nbsp;that transports you to the foothills of the Himalayas.</span></h4> 
</div> 
</div> 
 <div class="u_1712232178 dmRespCol empty-column small-12 large-1 medium-1 hide-for-small" id="1712232178"></div> 
</div> 
</div> 
</div> 
</div> 
</div> 
 <div class="dmRespRow u_1186515259" id="1186515259"> <div class="dmRespColsWrapper" id="1276756595"> <div class="dmRespCol large-12 medium-12 small-12 u_1398340231" id="1398340231"> <div class="u_1339499295 dmPhotoGallery newPhotoGallery dmPhotoGalleryResp" galleryoptionsparams="{thumbnailsPerRow: 3, rowsToShow: 3, imageScaleMethod: true}" data-desktop-layout="square" data-desktop-columns="4" data-element-type="dPhotoGalleryId" data-desktop-text-layout="fixed" id="1339499295" data-desktop-caption-alignment="center_center" data-placeholder="false" data-rows-to-show="100" data-link-gallery="true"> <ul class="dmPhotoGalleryHolder clearfix gallery shadowEffectToChildren gallery4inArow" id="1936209435"> <li class="photoGalleryThumbs" id="1829928094"> <div class="image-container" id="1995446183"> <a data-dm-multisize-attr="href" data-image-url="https://irp.cdn-website.com/e384b44b/dms3rep/multi/Mita-s+Kitchen+%281%29-dc5c83e7.svg" id="1945139337" class="u_1945139337"><img irh="" irw="" alt="" data-src="https://irp.cdn-website.com/e384b44b/dms3rep/multi/Mita-s+Kitchen+%281%29-dc5c83e7.svg" id="1211785888" class="" onerror="handleImageLoadError(this)"/></a> 
</div> 
 <div class="caption-container" style="display:none" id="1784917448"> <span class="caption-inner" id="1642146671"> <a class="caption-button dmWidget clearfix" id="1395423178"> <span class="iconBg" id="1193376676"> <span class="icon hasFontIcon icon-star" id="1414752362"></span> 
</span> 
 <span class="text" id="1820526655">Button</span> 
</a> 
</span> 
</div> 
</li> 
 <li class="photoGalleryThumbs" id="1624644350"> <div class="image-container" id="1870293729"> <a data-dm-multisize-attr="href" data-image-url="https://irp.cdn-website.com/e384b44b/dms3rep/multi/Mita-s+Kitchen+%284%29-8a68e070.svg" id="1736409305" class="u_1736409305"><img irh="" irw="" alt="" data-src="https://irp.cdn-website.com/e384b44b/dms3rep/multi/Mita-s+Kitchen+%284%29-8a68e070.svg" id="1265743727" class="" onerror="handleImageLoadError(this)"/></a> 
</div> 
 <div class="caption-container" style="display:none" id="1684456252"> <span class="caption-inner" id="1037034778"> <a class="caption-button dmWidget clearfix" id="1469307024"> <span class="iconBg" id="1650088068"> <span class="icon hasFontIcon icon-star" id="1690994583"></span> 
</span> 
 <span class="text" id="1552346239">Button</span> 
</a> 
</span> 
</div> 
</li> 
</ul> 
 <div class="photoGalleryViewAll link" isall="true" data-viewall="View more" data-viewless="View less" style="display:none;" id="1351393434"></div> 
 <li class="photoGalleryThumbs" id="1612397551"> <div class="image-container" id="1783472567"> <a data-dm-multisize-attr="href" data-image-url="https://irp.cdn-website.com/e384b44b/dms3rep/multi/Mita-s+Kitchen+%283%29-59e23c7f.svg" id="1538068864"><img irh="" irw="" alt="" data-src="https://irp.cdn-website.com/e384b44b/dms3rep/multi/Mita-s+Kitchen+%283%29-59e23c7f.svg" id="1249752306" onerror="handleImageLoadError(this)"/></a> 
</div> 
 <div class="caption-container" style="display:none" id="1726936799"> <span class="caption-inner" id="1034044183"> <a class="caption-button dmWidget clearfix" id="1972289898"> <span class="iconBg" id="1404399857"> <span class="icon hasFontIcon icon-star" id="1751857674"></span> 
</span> 
 <span class="text" id="1965829931">Button</span> 
</a> 
</span> 
</div> 
</li> 
 <li index="2" class="photoGalleryThumbs" id="1928380214"> <div class="image-container" id="1405352575"> <a data-dm-multisize-attr="href" data-image-url="https://irp.cdn-website.com/e384b44b/dms3rep/multi/Mita-s+Kitchen+%283%29.svg" id="1843958712" class="u_1843958712"><img data-src="https://irp.cdn-website.com/e384b44b/dms3rep/multi/Mita-s+Kitchen+%283%29.svg" irh="3" irw="4" alt="" id="1287304076" class="" onerror="handleImageLoadError(this)"/></a> 
</div> 
 <div class="caption-container  u_1012228884" id="1012228884"> <span class="caption-inner" id="1529116885"> <h3 class="caption-title u_1323119032" id="1323119032">Veg Pakora</h3> 
 <div class="caption-text u_1928519689" id="1928519689">Photo By: John Doe</div> 
 <a class="caption-button dmWidget   clearfix u_1612767023" href="" id="1612767023"> <span class="iconBg" id="1374760953"> <span class="icon hasFontIcon icon-star" id="1448062741"></span> 
</span> 
 <span class="text" id="1113845788">Button</span> 
</a> 
</span> 
</div> 
</li> 
</div> 
</div> 
</div> 
</div> 
 <div class="u_1544848247 dmRespRow hide-for-medium hide-for-large" id="1544848247"> <div class="dmRespColsWrapper" id="1282458449"> <div class="dmRespCol large-12 medium-12 small-12" id="1782692437"> <a data-display-type="block" class="u_1906514622 align-center dmButtonLink dmWidget dmWwr default dmOnlyButton dmDefaultGradient" file="false" href="https://mitas-indo-nepali-kitchen-llc.square.site/" data-element-type="dButtonLinkId" id="1906514622"> <span class="iconBg" id="1097027398"> <span class="icon hasFontIcon icon-star" id="1818970318"></span> 
</span> 
 <span class="text" id="1630945965">Order online</span> 
</a> 
</div> 
</div> 
</div> 
 <div class="dmRespRow u_1778137442 dmSectionParallaxNew fullBleedChanged fullBleedMode" id="1778137442" mode="1"> <div class="dmRespColsWrapper" id="1690255969"> <div class="u_1066139008 dmRespCol small-12 large-1 medium-1" id="1066139008"> <div data-element-type="spacer" class="u_1812464551 dmSpacer hide-for-small" id="1812464551"></div> 
</div> 
 <div class="u_1948207987 dmRespCol small-12 large-5 medium-5" id="1948207987"> <div data-element-type="spacer" class="u_1510349096 dmSpacer" id="1510349096"></div> 
</div> 
 <div class="u_1706716257 dmRespCol small-12 large-5 medium-5 hasBackgroundOverlay" id="1706716257"> <div class="u_1144918944 dmNewParagraph" data-element-type="paragraph" data-version="5" id="1144918944" style="transition: none 0s ease 0s; text-align: left; display: block;"> <h3 class="m-text-align-center text-align-left m-size-29 size-36" style="line-height: 1;"><span style="font-weight: bold; display: initial; color: var(--color_4);" class="font-size-36 m-font-size-29">We love community</span></h3> 
</div> 
 <div class="u_1790776922 dmNewParagraph" data-element-type="paragraph" data-version="5" id="1790776922" style="transition: none 0s ease 0s; text-align: left; display: block;"><p class="m-size-19 m-text-align-center size-24" style="line-height: 1.5;"><span style="display: initial; color: var(--color_4);" class="m-font-size-19 font-size-24">We consider the impact on our city, in everything we do.</span></p></div> 
 <div class="u_1379028060 dmNewParagraph" data-element-type="paragraph" data-version="5" id="1379028060" style="transition: none 0s ease 0s; text-align: left; display: block;"> <h3 class="m-text-align-center m-size-29 size-36" style="line-height: 1;"><span style="color: var(--color_4); display: initial;" class="font-size-36 m-font-size-29">We love tradition</span></h3> 
</div> 
 <div class="u_1640608120 dmNewParagraph" data-element-type="paragraph" data-version="5" id="1640608120" style="transition: none 0s ease 0s; text-align: left; display: block;"><p class="m-text-align-center m-size-19 size-24" style="line-height: 1.5;"><span style="color: var(--color_4); display: initial;" class="font-size-24 m-font-size-19">Tradition meets flavor! Experience an expression of love in every dish.</span></p></div> 
 <div class="u_1416524901 dmNewParagraph" data-element-type="paragraph" data-version="5" id="1416524901" style="transition: none 0s ease 0s; text-align: left; display: block;"> <h3 class="m-size-29 m-text-align-center size-36" style="line-height: 1;"><span class="m-font-size-29 font-size-36" style="color: var(--color_4); display: initial;"><span class="m-font-size-29 font-size-36" style="color: var(--color_4); display: initial;">We focus on fresh</span> 
</span></h3> 
</div> 
 <div class="u_1211181908 dmNewParagraph" data-element-type="paragraph" data-version="5" id="1211181908" style="transition: none 0s ease 0s; text-align: left;"><p class="m-size-19 m-text-align-center text-align-left size-24" style="line-height: 1.5;"><span style="display: initial; color: var(--color_4);" class="m-font-size-19 font-size-24">Our commitment to fresh is what sets us apart. Always fresh, always good.</span></p></div> 
 <div class="u_1721791679 dmNewParagraph" data-element-type="paragraph" data-version="5" id="1721791679" style="transition: none 0s ease 0s; text-align: left; display: block;"> <h3 class="m-size-29 m-text-align-center text-align-left size-36" style="line-height: initial;"><span class="m-font-size-29 font-size-36" style="color: var(--color_4); display: initial;">We believe in good</span></h3> 
</div> 
 <div class="u_1082494926 dmNewParagraph" data-element-type="paragraph" data-version="5" id="1082494926" style="transition: none 0s ease 0s; text-align: left;"><p class="m-text-align-center text-align-left m-size-19 size-24" style="line-height: 1.5;"><span style="color: var(--color_4); display: initial;" class="font-size-24 m-font-size-19">We start every day with the preparation and intention of crafting something delicious for you!</span></p></div> 
</div> 
 <div class="u_1274802937 dmRespCol small-12 large-1 medium-1" id="1274802937"> <div data-element-type="spacer" class="dmSpacer" id="1296820038"></div> 
</div> 
</div> 
</div> 
 <div class="dmRespRow u_1731979173" id="1731979173"> <div class="dmRespColsWrapper" id="1497016587"> <div class="dmRespCol large-12 medium-12 small-12 u_1474663226" id="1474663226"> <a data-display-type="block" class="u_1861678105 align-center dmButtonLink dmWidget dmWwr default dmOnlyButton dmDefaultGradient" file="false" href="/about" data-element-type="dButtonLinkId" id="1861678105"> <span class="iconBg" id="1531790105"> <span class="icon hasFontIcon icon-star" id="1015045239"></span> 
</span> 
 <span class="text" id="1986154371">About us</span> 
</a> 
</div> 
</div> 
</div> 
 <div class="u_1995853054 dmRespRow fullBleedChanged fullBleedMode hide-for-small" id="1995853054"> <div class="dmRespColsWrapper" id="1029797894"> <div class="dmRespCol empty-column large-12 medium-12 small-12 u_1302893245" id="1302893245"></div> 
</div> 
</div> 
 <div class="u_1243667655 dmRespRow dmSectionNoParallax" style="text-align: center;" id="1243667655"> <div class="dmRespColsWrapper" id="1173148036"> <div class="u_1547960311 dmRespCol small-12 large-8 medium-8 content-removed" id="1547960311"> <div class="u_1791150958 dmNewParagraph" data-element-type="paragraph" data-version="5" id="1791150958" background-image":""}"="" style="transition: none 0s ease 0s; text-align: left; display: block;"> <h2 class="m-size-27 text-align-center size-48" style="line-height: 1.5;"><span style="color: var(--color_4); display: initial;" class="m-font-size-27 font-size-48" m-font-size-set="true">Visit us today and indulge in our mouthwatering dishes made with the freshest ingredients and a blend of traditional Himalayan spices. Book your table now and treat yourself to a culinary journey through Nepal &amp; India.</span></h2> 
</div> 
</div> 
 <div class="u_1083912959 dmRespCol small-12 large-4 medium-4 content-removed" id="1083912959"> <div class="u_1919545985 imageWidget align-center" data-element-type="image" data-widget-type="image" id="1919545985"><img src="https://lirp.cdn-website.com/e384b44b/dms3rep/multi/opt/large-Logo-Himalaya-2---Edited-b2adf1af-1920w.png" alt="" id="1626983682" class="" data-dm-image-path="https://irp.cdn-website.com/e384b44b/dms3rep/multi/large-Logo-Himalaya-2---Edited-b2adf1af.png" width="642" height="589" onerror="handleImageLoadError(this)"/></div> 
 <div class="imageWidget align-center u_1290753675" data-element-type="image" data-widget-type="image" id="1290753675"><img src="https://irp.cdn-website.com/e384b44b/dms3rep/multi/Mitas+Kitchen+Schedlue.svg" alt="" id="1265788008" class="" data-dm-image-path="https://irp.cdn-website.com/e384b44b/dms3rep/multi/Mitas+Kitchen+Schedlue.svg" width="700" height="300" onerror="handleImageLoadError(this)"/></div> 
 <a data-display-type="block" class="u_1654565557 align-center dmButtonLink dmWidget dmWwr default dmOnlyButton dmDefaultGradient" file="false" href="tel:662-798-0576" data-element-type="dButtonLinkId" id="1654565557"> <span class="iconBg" id="1401268152"> <span class="icon hasFontIcon icon-star" id="1222082405"></span> 
</span> 
 <span class="text" id="1821207637">Call Us &amp; Place an Order</span> 
</a> 
 <a data-display-type="block" class="u_1469647022 align-center dmButtonLink dmWidget dmWwr default dmOnlyButton dmDefaultGradient" file="false" href="https://www.google.com/maps/place/Mita's+Himalayan+Kitchen/@33.5306939,-88.4376676,17z/data=!3m1!4b1!4m6!3m5!1s0x8886e91de4e53947:0x89c26b858e54c779!8m2!3d33.5306939!4d-88.4354789!16s%2Fg%2F11t_lnxdd7?entry=ttu" data-element-type="dButtonLinkId" id="1469647022" target="_blank"> <span class="iconBg" id="1112344580"> <span class="icon hasFontIcon icon-star" id="1273949851"></span> 
</span> 
 <span class="text" id="1818177004">Visit Us</span> 
</a> 
</div> 
</div> 
</div> 
</div> 
</div> 
</div> 
</div> 
 <div class="dmFooterContainer"> <div id="fcontainer" class="u_fcontainer f_hcontainer dmFooter p_hfcontainer"> <div dm:templateorder="250" class="dmFooterResp generalFooter" id="1943048428"> <div class="dmRespRow u_1384333126" id="1384333126"> <div class="dmRespColsWrapper" id="1947252323"> <div class="dmRespCol large-12 medium-12 small-12 content-removed" id="1381628506"> <div class="u_1956682616 dmNewParagraph" data-element-type="paragraph" data-version="5" id="1956682616" style="transition: opacity 1s ease-in-out 0s;"><p class="text-align-center"><span style="color: var(--color_1);">Follow us on instagram</span></p></div> 
 <div class="u_1850691624 dmNewParagraph" data-element-type="paragraph" data-version="5" id="1850691624" style="transition: none 0s ease 0s; text-align: left; display: block;"> <h2 class="m-size-20 text-align-center"><span class="m-font-size-20" m-font-size-set="true" style="color: rgb(255, 255, 255);">#</span><span class="m-font-size-20" m-font-size-set="true" style="color: rgb(255, 255, 255); font-weight: 700;">mitashimalayankitchen</span></h2> 
</div> 
</div> 
</div> 
</div> 
 <div class="dmRespRow u_1644655235" id="1644655235" mode="1"> <div class="dmRespColsWrapper" id="1561290520"> <div class="u_1424033316 dmRespCol large-2 medium-2 small-12" id="1424033316"> <div class="u_1910672545 imageWidget align-center" data-element-type="image" data-widget-type="image" id="1910672545" data-binding="W3siYmluZGluZ05hbWUiOiJpbWFnZSIsInZhbHVlIjoic2l0ZV9pbWFnZXMubG9nbyJ9XQ=="> <a id="1668350090" href="/" file="false"><img src="https://lirp.cdn-website.com/e384b44b/dms3rep/multi/opt/large-Logo-Himalaya-2+-+Edited+White-1920w.png" alt="" id="1904801071" class="" data-dm-image-path="https://irp.cdn-website.com/e384b44b/dms3rep/multi/large-Logo-Himalaya-2+-+Edited+White.png" width="196" height="33" data-diy-image="" onerror="handleImageLoadError(this)"/></a> 
</div> 
</div> 
 <div class="u_1009347560 dmRespCol large-8 medium-8 small-12 content-removed" id="1009347560"> <div class="u_1279876901 imageWidget align-center" data-element-type="image" data-widget-type="image" id="1279876901"><img src="https://irp.cdn-website.com/e384b44b/dms3rep/multi/Mitas+Kitchen+Schedule+White.svg" alt="" id="1685006394" class="" data-dm-image-path="https://irp.cdn-website.com/e384b44b/dms3rep/multi/Mitas+Kitchen+Schedule+White.svg" width="700" height="300" onerror="handleImageLoadError(this)"/></div> 
 <div class="u_1880306456 align-center text-align-center dmSocialHub" id="1880306456" dmle_extension="social_hub" data-element-type="social_hub" wr="true" networks="" icon="true" surround="true" adwords=""> <div class="socialHubWrapper"> <div class="socialHubInnerDiv "> <a href="https://www.facebook.com/people/Mitas-Himalayan-Kitchen/100089619136691/" target="_blank" dm_dont_rewrite_url="true" aria-label="facebook" onclick="dm_gaq_push_event &amp;&amp; dm_gaq_push_event(&apos;socialLink&apos;, &apos;click&apos;, &apos;Facebook&apos;)"> <span class="dmSocialFacebook dm-social-icons-facebook oneIcon socialHubIcon style8" aria-hidden="true" data-hover-effect=""></span> 
</a> 
 <a href="https://www.instagram.com/mitaskitchen2022/" target="_blank" dm_dont_rewrite_url="true" aria-label="instagram" onclick="dm_gaq_push_event &amp;&amp; dm_gaq_push_event(&apos;socialLink&apos;, &apos;click&apos;, &apos;Instagram&apos;)"> <span class="dmSocialInstagram dm-social-icons-instagram oneIcon socialHubIcon style8" aria-hidden="true" data-hover-effect=""></span> 
</a> 
 <a href="https://www.google.com/maps/place/Mita&apos;s+Himalayan+Kitchen/@33.5306939,-88.4376676,17z/data=!3m1!4b1!4m6!3m5!1s0x8886e91de4e53947:0x89c26b858e54c779!8m2!3d33.5306939!4d-88.4354789!16s%2Fg%2F11t_lnxdd7?entry=ttu" target="_blank" dm_dont_rewrite_url="true" aria-label="google_my_business" onclick="dm_gaq_push_event &amp;&amp; dm_gaq_push_event(&apos;socialLink&apos;, &apos;click&apos;, &apos;GoogleMyBusiness&apos;)"> <span class="dmSocialGoogleMyBusiness dm-social-icons-google-my-business oneIcon socialHubIcon style8" aria-hidden="true" data-hover-effect=""></span> 
</a> 
</div> 
</div> 
</div> 
 <nav class="u_1942028426 hide-for-small effect-none main-navigation unifiednav dmLinksMenu" role="navigation" layout-main="horizontal_nav_layout_1" layout-sub="submenu_horizontal_1" data-show-vertical-sub-items="HOVER" id="1942028426" dmle_extension="onelinksmenu" data-element-type="onelinksmenu" data-logo-src="" alt="" data-nav-structure="HORIZONTAL" wr="true" icon="true" surround="true" adwords="" navigation-id="unifiedNav"> <ul role="menubar" class="unifiednav__container  " data-auto="navigation-pages"> <li role="menuitem" class=" unifiednav__item-wrap " data-auto="more-pages" data-depth="0"> <a href="/" class="unifiednav__item  dmNavItemSelected  dmUDNavigationItem_00  " target="" data-target-page-alias="" data-auto="selected-page"> <span class="nav-item-text " data-link-text="
         Home
        " data-auto="page-text-style">Home<span class="icon icon-angle-down"></span> 
</span> 
</a> 
</li> 
 <li role="menuitem" class=" unifiednav__item-wrap " data-auto="more-pages" data-depth="0"> <a href="/menu" class="unifiednav__item  dmUDNavigationItem_010101326518  " target="" data-target-page-alias=""> <span class="nav-item-text " data-link-text="
         Menu
        " data-auto="page-text-style">Menu<span class="icon icon-angle-down"></span> 
</span> 
</a> 
</li> 
 <li role="menuitem" class=" unifiednav__item-wrap " data-auto="more-pages" data-depth="0"> <a href="/catering-online-order" class="unifiednav__item  dmUDNavigationItem_010101500621  " target="" data-target-page-alias=""> <span class="nav-item-text " data-link-text="Catering" data-auto="page-text-style">Catering<span class="icon icon-angle-down"></span> 
</span> 
</a> 
</li> 
 <li role="menuitem" class=" unifiednav__item-wrap " data-auto="more-pages" data-depth="0"> <a href="/about" class="unifiednav__item  dmUDNavigationItem_010101436714  " target="" data-target-page-alias=""> <span class="nav-item-text " data-link-text="
         About
        " data-auto="page-text-style">About<span class="icon icon-angle-down"></span> 
</span> 
</a> 
</li> 
 <li role="menuitem" class=" unifiednav__item-wrap " data-auto="more-pages" data-depth="0"> <a href="/contact" class="unifiednav__item  dmUDNavigationItem_010101943230  " target="" data-target-page-alias=""> <span class="nav-item-text " data-link-text="
         Contact
        " data-auto="page-text-style">Contact<span class="icon icon-angle-down"></span> 
</span> 
</a> 
</li> 
 <li role="menuitem" class=" unifiednav__item-wrap " data-auto="more-pages" data-depth="0"> <a href="https://squareup.com/loyalty/MLHWR7C0E9HY7" class="unifiednav__item  dmUDNavigationItem_0101019020  " target="_blank" data-target-page-alias=""> <span class="nav-item-text " data-link-text="Reward" data-auto="page-text-style">Reward<span class="icon icon-angle-down"></span> 
</span> 
</a> 
</li> 
 <li role="menuitem" class=" unifiednav__item-wrap " data-auto="more-pages" data-depth="0"> <a href="https://partners.hello-doordash.com/api/mailings/click/PMRGSZBCHIYTCMZQGY3TSOBMEJ2XE3BCHIRGQ5DUOBZTULZPN5ZGIZLSFZXW43DJNZSS6YTVONUW4ZLTOMXW22LUMFZS22DJNVQWYYLZMFXC223JORRWQZLOFUYTCNRUGU2DMMZCFQRG64THEI5CENJVMI3TOYJQGMWTQOBWGEWTIZDFMEWTQNRXMQWWEYRQGBRTEZLBMQ4DMYRCFQRHMZLSONUW63RCHIRDIIRMEJZWSZZCHIRGK53NG52EI6TENVVWSLLQPBJG2RKDNFIUMURZMZ2TIM3JKZXGQ4LFOJUE632KJJFWKZ2FHURH2===" class="unifiednav__item  dmUDNavigationItem_010101669821  " target="_blank" data-target-page-alias=""> <span class="nav-item-text " data-link-text="
         Doordash
        " data-auto="page-text-style">Doordash<span class="icon icon-angle-down"></span> 
</span> 
</a> 
</li> 
 <li role="menuitem" class=" unifiednav__item-wrap " data-auto="more-pages" data-depth="0"> <a href="https://www.order.store/store/mitas-himalayan-kitchen/j_eXMIW4TkKY_A7vMRc5_A" class="unifiednav__item  dmUDNavigationItem_010101473552  " target="_blank" data-target-page-alias=""> <span class="nav-item-text " data-link-text="UberEats" data-auto="page-text-style">UberEats<span class="icon icon-angle-down"></span> 
</span> 
</a> 
</li> 
</ul> 
</nav> 
 <div class="u_1476756311 widget-1f5975 dmCustomWidget" data-lazy-load="" data-title="" id="1476756311" dmle_extension="custom_extension" data-element-type="custom_extension" icon="false" surround="false" data-widget-id="1f5975986930429f819d4cd2154b5c4a" data-widget-version="22" data-widget-config="eyJjb3B5cmlnaHRUZXh0IjoiPHAgY2xhc3M9XCJydGVCbG9ja1wiPkFsbCBSaWdodHMgUmVzZXJ2ZWQgfCBNaXRhJiN4Mjc7cyBIaW1pbGF5YW4gS2l0Y2hlbjwvcD4ifQ=="> <div class="copyright"> <div>&copy; 2023&nbsp;</div> 
 <div><p class="rteBlock">All Rights Reserved | Mita's Himilayan Kitchen</p></div> 
</div> 
</div> 
</div> 
 <div class="u_1162892674 dmRespCol large-2 medium-2 small-12" id="1162892674"> <a data-display-type="block" class="u_1793970297 align-center dmButtonLink dmWidget dmWwr default dmOnlyButton dmDefaultGradient" file="false" href="tel:662-798-0576" data-element-type="dButtonLinkId" id="1793970297"> <span class="iconBg" id="1560149868"> <span class="icon hasFontIcon icon-star" id="1867130108"></span> 
</span> 
 <span class="text" id="1963403892">Call Us</span> 
</a> 
 <a data-display-type="block" class="u_1566059325 align-center dmButtonLink dmWidget dmWwr default dmOnlyButton dmDefaultGradient" file="false" href="https://www.google.com/maps/place/Mita's+Himalayan+Kitchen/@33.5306939,-88.4376676,17z/data=!3m1!4b1!4m6!3m5!1s0x8886e91de4e53947:0x89c26b858e54c779!8m2!3d33.5306939!4d-88.4354789!16s%2Fg%2F11t_lnxdd7?entry=ttu" data-element-type="dButtonLinkId" id="1566059325"> <span class="iconBg" id="1883835520"> <span class="icon hasFontIcon icon-star" id="1699429662"></span> 
</span> 
 <span class="text" id="1340477653">Visit Us</span> 
</a> 
</div> 
</div> 
</div> 
</div> 
 <div id="1236746004" dmle_extension="powered_by" data-element-type="powered_by" icon="true" surround="false"></div> 
</div> 
</div> 
</div> 
 <div class="showOnMedium layout-drawer-hamburger hamburger-on-header" id="layout-drawer-hamburger" role="button" aria-label="menu opener" tabindex="0"> <span class="hamburger__slice"></span> 
 <span class="hamburger__slice"></span> 
 <span class="hamburger__slice"></span> 
</div> 
</div> 
</div> 
</div> 
</div> 
</div> 
</div> 

    </div>
</div>
<!--  Add full CSS and Javascript before the close tag of the body if needed -->
<!-- ========= JS Section ========= -->

<script>
    var isWLR = true;

    window.customWidgetsFunctions = {};
    window.customWidgetsStrings = {};
    window.collections = {};
    window.currentLanguage = "ENGLISH"
    window.isSitePreview = false;
</script>
<script type="text/javascript">

    var d_version = "production_3886";
    var build = "2023-11-01T09_49_42";
    window['v' + 'ersion'] = d_version;

    function buildEditorParent() {
        window.isMultiScreen = true;
        window.editorParent = {};
        window.previewParent = {};
        window.assetsCacheQueryParam = "?version=2023-11-01T09_49_42";
        try {
            var _p = window.parent;
            if (_p && _p.document && _p.$ && _p.$.dmfw) {
                window.editorParent = _p;
            } else if (_p.isSitePreview) {
                window.previewParent = _p;
            }
        } catch (e) {

        }
    }

    buildEditorParent();
</script>

<!-- Load jQuery -->
    <script type="text/javascript" id='d-js-jquery'
            src="https://static.cdn-website.com/libs/jquery/jquery-3.7.0.min.js"></script>
    <!-- End Load jQuery -->
<!-- Injecting site-wide before scripts -->
<!-- End Injecting site-wide to the head -->


<script>
    var _jquery = window.$;

    var jqueryAliases = ['$', 'jquery', 'jQuery'];

    jqueryAliases.forEach((alias) => {
        Object.defineProperty(window, alias, {
            get() {
                return _jquery;
            },
            set() {
                console.warn("Trying to over-write the global jquery object!");
            }
        });
    });
    window.jQuery.migrateMute = true;
</script>
<script>
    window.cookiesNotificationMarkupPreview = 'null';
</script>

<!-- HEAD RT JS Include -->
<script id='d-js-params'>
    window.INSITE = window.INSITE || {};
    window.INSITE.device = "desktop";
    window.rtCommonProps = {};
    rtCommonProps["rt.ajax.ajaxScriptsFix"] =true;
    rtCommonProps["rt.pushnotifs.sslframe.encoded"] = 'aHR0cHM6Ly97c3ViZG9tYWlufS5wdXNoLW5vdGlmcy5jb20=';
    rtCommonProps["runtimecollector.url"] = 'https://rtc.multiscreensite.com';
    rtCommonProps["performance.tabletPreview.removeScroll"] = 'false';
    rtCommonProps["inlineEditGrid.snap"] =true;
    rtCommonProps["popup.insite.cookie.ttl"] = '0.5';
    rtCommonProps["rt.pushnotifs.force.button"] =true;

    rtCommonProps["common.mapbox.token"] = 'pk.eyJ1IjoiZGFubnliMTIzIiwiYSI6ImNqMGljZ256dzAwMDAycXBkdWxwbDgzeXYifQ.Ck5P-0NKPVKAZ6SH98gxxw';
    rtCommonProps["common.mapbox.js.override"] =false;
    rtCommonProps["common.opencage.token"] = '319e14f32bcce967ba55cd263478796d';
    rtCommonProps["common.here.appId"] = 'iYvDjIQ2quyEu0rg0hLo';
    rtCommonProps["common.here.appCode"] = '1hcIxLJcbybmtBYTD9Z1UA';
    rtCommonProps["isCoverage.test"] =false;
    rtCommonProps["ecommerce.ecwid.script"] = 'https://app.multiscreenstore.com/script.js';
    rtCommonProps["feature.flag.mappy.kml"] =false;
    rtCommonProps["common.resources.dist.cdn"] =true;
    rtCommonProps["common.build.dist.folder"] = 'production/3886';
    rtCommonProps["common.resources.cdn.host"] = 'https://static.cdn-website.com';
    rtCommonProps["common.resources.folder"] = 'https://static.cdn-website.com/mnlt/production/3886';
    rtCommonProps["feature.flag.runtime.backgroundSlider.preload.slowly"] =true;
    rtCommonProps["feature.flag.runtime.photoswipe.fix"] =true;
    rtCommonProps["feature.flag.runtime.newAnimation.enabled"] =true;
    rtCommonProps["feature.flag.runtime.newAnimation.respectCssAnimationProps.enabled"] =true;
    rtCommonProps["feature.flag.runtime.newAnimation.jitAnimation.enabled"] =true;
    rtCommonProps["feature.flag.sites.google.analytics.gtag"] =true;
    rtCommonProps["feature.flag.runOnReadyNewTask"] =true;
    rtCommonProps["feature.flag.addTargetBlankToExternalLinks"] =true;
    rtCommonProps["unsuspendEcwidStoreOnRuntime.enabled"] =true;
    rtCommonProps["keyboard.navigation.enabled"] =true;
    rtCommonProps["scripts.widgetCount.enabled"] =true;
    rtCommonProps["run.imageCount.script.enabled"] =false;
    rtCommonProps["maps.cookiebot.enabled"] =true;

    
    rtCommonProps['common.mapsProvider'] = 'mapbox';
    
    rtCommonProps['common.mapsProvider.version'] = '0.52.0';
    rtCommonProps['common.geocodeProvider'] = 'here';
    rtCommonProps['common.map.defaults.radiusSize'] = '1500';
    rtCommonProps['common.map.defaults.radiusBg'] = 'rgba(255, 255, 255, 0.4)';
    rtCommonProps['common.map.defaults.strokeColor'] = 'rgba(255, 255, 255, 1)';
    rtCommonProps['common.map.defaults.strokeSize'] = '2';
    rtCommonProps['server.for.resources'] = '';
    rtCommonProps['feature.flag.lazy.widgets'] = true;
    rtCommonProps['feature.flag.single.wow'] = false;
    rtCommonProps['feature.flag.disallowPopupsInEditor'] = true;
    rtCommonProps['feature.flag.mark.anchors'] = true;
    rtCommonProps['captcha.public.key'] = '6LffcBsUAAAAAMU-MYacU-6QHY4iDtUEYv_Ppwlz';
    rtCommonProps['captcha.invisible.public.key'] = '6LeiWB8UAAAAAHYnVJM7_-7ap6bXCUNGiv7bBPME';
    rtCommonProps["images.sizes.small"] =160;
    rtCommonProps["images.sizes.mobile"] =640;
    rtCommonProps["images.sizes.tablet"] =1280;
    rtCommonProps["images.sizes.desktop"] =1920;
    rtCommonProps["modules.resources.cdn"] =true;
    rtCommonProps["import.images.storage.imageCDN"] = 'https://lirp.cdn-website.com/';
    rtCommonProps["ecom.ecwid.categoryPage.modifyLinks"] = true;
    rtCommonProps["ecom.ecwidNewUrlStructure.enabled"] = false;
    rtCommonProps["facebook.api.version"] = '7.0';
    rtCommonProps["feature.flag.photo.gallery.exact.size"] =false;
    rtCommonProps["new.store.fix.ecwid.back.bug"] =true;
    rtCommonProps["new.store.accountPage.ecwid.resetPassword.fix"] =true;
    rtCommonProps["site.runtime.video.background.ssr"] =true;
    rtCommonProps["geocode.search.localize"] =false;
    rtCommonProps["facebook.runtime.widgets.upgrade"] =true;
    rtCommonProps["feature.flag.runtime.inp.threshold"] =150;
    rtCommonProps["feature.flag.runtime.newAnimation.asyncInit.setTimeout.enabled"] =false;
    rtCommonProps["feature.flag.performance.logs"] =true;
    rtCommonProps["site.contact.form.fix.for.attribute"] =true;
    rtCommonProps["site.widget.form.captcha.type"] = 'g_recaptcha';
    rtCommonProps["friendly.captcha.site.key"] = 'FCMGSQG9GVNMFS8K';
    rtCommonProps["contact.form.date.format.enabled"] = true;
    rtCommonProps["filestack.uploadToTempBucket.enabled"] = true;
    rtCommonProps["platform.monolith.loginBar.getUserLoggedIn.enabled"] = true;
    rtCommonProps["platform.monolith.loginBar.layout.enabled"] = true;
</script>
<script src="https://static.cdn-website.com/mnlt/production/3886/_dm/s/rt/dist/scripts/d-js-one-runtime-unified-desktop.min.js"  id="d-js-core"></script>
<!-- End of HEAD RT JS Include -->
<script src="https://static.cdn-website.com/mnlt/production/3886/_dm/s/rt/dist/scripts/d-js-jquery-migrate.min.js" ></script>
<script>jQuery.DM.updateWidthAndHeight();
$(window).resize(function () {
    
});
$(window).bind("orientationchange", function (e) {
    $.layoutManager.initLayout();
    
});
$(document).resize(function () {
    
});
</script>
<script type="text/javascript" id="d_track_campaign">
(function() {
 	var campaign = (/utm_campaign=([^&]*)/).exec(window.location.search);

 	if (campaign && campaign != null && campaign.length > 1) {
 		campaign = campaign[1];
 		document.cookie = "_dm_rt_campaign=" + campaign + ";expires=" + new Date().getTime() + 24*60*60*1000 + ";domain=" + window.location.hostname + ";path=/";
 	}
}());
</script>
<script type="text/javascript" >
  var _dm_gaq = {};
  var _gaq = _gaq || [];
  var _dm_insite = [];
</script>

  </script>
<script type="text/javascript" id="d_track_sp">
;(function(p,l,o,w,i,n,g){if(!p[i]){p.GlobalSnowplowNamespace=p.GlobalSnowplowNamespace||[];
p.GlobalSnowplowNamespace.push(i);p[i]=function(){(p[i].q=p[i].q||[]).push(arguments)
};p[i].q=p[i].q||[];n=l.createElement(o);g=l.getElementsByTagName(o)[0];n.async=1;
n.src=w;g.parentNode.insertBefore(n,g)}}(window,document,"script","//d32hwlnfiv2gyn.cloudfront.net/sp-2.0.0-dm-0.1.min.js","snowplow"));
window.dmsnowplow  = window.snowplow;

dmsnowplow('newTracker', 'cf', 'd32hwlnfiv2gyn.cloudfront.net', { // Initialise a tracker
  appId: 'e384b44b'
});

dmsnowplow('trackPageView')
$.each(_dm_insite, function(idx, rule) {
	//('trackStructEvent', 'category','action','label','property','value');
			// Specifically in popup only the client knows if it is shown or not so we don't always want to track its impression here
	        // the tracking is in popup.js
			if (rule.actionName !== "popup") {
                dmsnowplow('trackStructEvent', 'insite', 'impression', rule.ruleType, rule.ruleId);
            }
 			$(document).ready(function(){
 				$.DM.events.trigger('event-ruleTriggered', {value: rule})}
 			);
 		});
</script>
   <div style="display:none;" id="P6iryBW0Wu"></div>

<!-- photoswipe markup -->









<!-- Root element of PhotoSwipe. Must have class pswp. -->
<div class="pswp" tabindex="-1" role="dialog" aria-hidden="true">

    <!-- Background of PhotoSwipe. 
         It's a separate element as animating opacity is faster than rgba(). -->
    <div class="pswp__bg"></div>

    <!-- Slides wrapper with overflow:hidden. -->
    <div class="pswp__scroll-wrap">

        <!-- Container that holds slides. 
            PhotoSwipe keeps only 3 of them in the DOM to save memory.
            Don't modify these 3 pswp__item elements, data is added later on. -->
        <div class="pswp__container">
            <div class="pswp__item"></div>
            <div class="pswp__item"></div>
            <div class="pswp__item"></div>
        </div>

        <!-- Default (PhotoSwipeUI_Default) interface on top of sliding area. Can be changed. -->
        <div class="pswp__ui pswp__ui--hidden">

            <div class="pswp__top-bar">

                <!--  Controls are self-explanatory. Order can be changed. -->

                <div class="pswp__counter"></div>

                <button class="pswp__button pswp__button--close" title="Close (Esc)"></button>

                <button class="pswp__button pswp__button--share" title="Share"></button>

                <button class="pswp__button pswp__button--fs" title="Toggle fullscreen"></button>

                <button class="pswp__button pswp__button--zoom" title="Zoom in/out"></button>

                <!-- Preloader demo http://codepen.io/dimsemenov/pen/yyBWoR -->
                <!-- element will get class pswp__preloader--active when preloader is running -->
                <div class="pswp__preloader">
                    <div class="pswp__preloader__icn">
                      <div class="pswp__preloader__cut">
                        <div class="pswp__preloader__donut"></div>
                      </div>
                    </div>
                </div>
            </div>

            <div class="pswp__share-modal pswp__share-modal--hidden pswp__single-tap">
                <div class="pswp__share-tooltip"></div> 
            </div>

            <button class="pswp__button pswp__button--arrow--left" title="Previous (arrow left)">
            </button>

            <button class="pswp__button pswp__button--arrow--right" title="Next (arrow right)">
            </button>

            <div class="pswp__caption">
                <div class="pswp__caption__center"></div>
            </div>

        </div>

    </div>

</div>
<div id="fb-root"
        data-locale="en"></div>
<!-- Alias: e384b44b -->
<div class="dmPopupMask" id="dmPopupMask"></div>
<div id="dmPopup" class="dmPopup">
	<div class="dmPopupCloseWrapper"> <div class="dmPopupClose dm-common-icons-close oneIcon" onclick="dmHidePopup(event);"></div> </div>
 	<div class="dmPopupTitle"> <span></span> Share by:</div> 
	<div class="data"></div>
</div><script id="d_track_personalization">
// Collects client data and updates cookies used by smart sites
var expireDays = 365,visitLength = 30 * 60000;
$.setCookie("dm_timezone_offset", (new Date()).getTimezoneOffset(), expireDays);
function setSmartSiteCookies() {
	setSmartSiteCookiesInternal("dm_this_page_view","dm_last_page_view","dm_total_visits","dm_last_visit");
}
$.DM.events.on("afterAjax", setSmartSiteCookies);
setSmartSiteCookies();
</script>
<script type="text/javascript">
    
    Parameters.NavigationAreaParams.MoreButtonText = 'MORE';
    
    Parameters.NavigationAreaParams.LessButtonText = 'LESS';
    Parameters.HomeLinkText = 'Home';
    </script>
<script>
    jQuery(window).on('load', function () {
        try {
            jQuery.DM.updateIOSHeight();
        } catch (e) {
        }
    });
</script>
<script>
    dmAPI.loadScript(
        window.rtCommonProps['common.resources.cdn.host'] + '/libs/lozad/1.15.0/lozad.min.js',
        function () {
            dmAPI.runOnReady('lozadInit', function () {
                window.document.querySelectorAll('img.lazy').forEach(function (img) {
                    img.addEventListener('load', function (event) {
                        var img = event.target;
                        img.style.filter = 'blur(0)';
                        setTimeout(function () {
                            $(img).closest('.imageWidget').addClass('lazyLoaded');
                        }, 250)
                    });
                });
                lozad('.lazy', {
                    threshold: 0.1,
                    loaded: function (element) {
                        if (element.getAttribute('data-background-image')) {
                            element.style.setProperty(
                                'background-image',
                                "url('" + element.getAttribute('data-background-image') + "')",
                                "important"
                            );
                        }
                    }
                }).observe();
            });
        }
    );
</script>
<div><script type="text/javascript">
             try{
            if (globalThis.parent){
                 var parentFlags =  globalThis.parent._flags;
                 var parentStrings =  globalThis.parent.dmStr;

             }
            } catch(e) {}
            _flags = window._flags || {};_flags = {...parentFlags,..._flags,...{"runtime.ssr.add.render":true,"runtime.ssr.enabled":true,"runtime.ssr.forceincludelib":false,"runtime.ssr.initial-props-in-data-attribute":true,"runtime.ssr.media-non-view-priority-low":false,"runtime.ssr.new-runtime-fix-model-set-props":false,"runtime.ssr.non-view-media-server-placeholder":true,"runtime.ssr.script-fetch-priority-low":false,"runtime.ssr.slider-dev-logging":false,"runtime.ssr.slider-layout3-image-aligned-content":false,"runtime.ssr.slider-reOrderSelectedToBeFirst":true,"runtime.ssr.widget.migration.addtocart":false,"runtime.ssr.widgetPropsStore.reset":false}}
           
        
          var dmStr = {...parentStrings,...dmStr,...{"placeholder.add-content":"Add Content","widget.filtersort.filter-by.title":"Filter by","widget.filtersort.sort-by.title":"Sort by","second.key":"value2","key.runtime":"some value","widget.addtocart.title":"Add to cart","widget.filtersort.clear-all":"clear all","widget.addtocart.disabledText.placeHolder":"OUT OF STOCK","ui.ed.breadcrumbs.empty.message":"There aren't any visible pages to show in the breadcrumbs. This message won't appear on your live published site.","widget.filtersort.title":"Sort & Filter","ui.runtimessr.priceOptions.option.oneTimeOnly":"One-time purchase","ui.runtimessr.collectionSearch.noResults":"No results."}}

</script>
        <script id="ssr-static" type="module"  src="https://ms-cdn.multiscreensite.com/runtime-react/3604/res/js/runtime-react.js" ></script></div><!--  End Script tags -->

<!--  Site Wide Html Markup -->
<!--  Site Wide Html Markup -->
</body>
</html>
