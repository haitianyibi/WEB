<!doctype html>
<html       lang="zh-CN"      dir="ltr">
  <head>
    <meta name="google-signin-client-id" content="721724668570-nbkv1cfusk7kk4eni4pjvepaus73b13t.apps.googleusercontent.com">
    <meta name="google-signin-scope" content="profile email">
    <meta property="og:site_name" content="Android Developers">
    <meta property="og:type" content="website">

          <meta name="theme-color" content="#3ddc84">
    
    <meta charset="utf-8">
    <meta content="IE=Edge" http-equiv="X-UA-Compatible">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <script type="text/javascript" nonce="f82ddeacfe2644a19c55854b77d" src="//local.adguard.org?ts=1582349981236&amp;type=content-script&amp;dmn=developer.android.google.cn&amp;css=1&amp;js=1&amp;gcss=1&amp;rel=1&amp;rji=1&amp;stealth=1&amp;uag="></script>
<script type="text/javascript" nonce="f82ddeacfe2644a19c55854b77d" src="//local.adguard.org?ts=1582349981236&amp;name=AdGuard%20Assistant%20Beta&amp;name=Web%20of%20Trust%20Beta&amp;name=AdGuard%20Extra%20Beta&amp;type=user-script"></script><link rel="manifest" href="/_pwa/android/manifest.json"
          crossorigin="use-credentials">
    <link rel="preconnect" href="//www.gstatic.cn" crossorigin>
    <link rel="preconnect" href="//fonts.gstatic.com" crossorigin>
    <link rel="preconnect" href="//fonts.googleapis.com" crossorigin>
    <link rel="stylesheet" href="//fonts.googleapis.com/css?family=Roboto:300,400,400italic,500,500italic,700,700italic|Roboto+Mono:400,500,700|Material+Icons">
        <link rel="stylesheet" href="https://www.gstatic.cn/devrel-devsite/prod/ve2ae1395f351e38dc0b3037132204261d76b8f1c638764d7fd2c2fbb865782fc/android/css/app.css">
    <noscript>
      <link rel="stylesheet" href="https://www.gstatic.cn/devrel-devsite/prod/ve2ae1395f351e38dc0b3037132204261d76b8f1c638764d7fd2c2fbb865782fc/android/css/ce_bundle.css">
    </noscript>
    <link rel="shortcut icon" href="https://www.gstatic.cn/devrel-devsite/prod/ve2ae1395f351e38dc0b3037132204261d76b8f1c638764d7fd2c2fbb865782fc/android/images/favicon.png">
    <link rel="apple-touch-icon" href="https://www.gstatic.cn/devrel-devsite/prod/ve2ae1395f351e38dc0b3037132204261d76b8f1c638764d7fd2c2fbb865782fc/android/images/touchicon-180.png"><link rel="canonical" href="https://developer.android.google.cn/docs?hl=zh-cn">      
<title>Android 开发者 &nbsp;|&nbsp; Android Developers</title>
<meta property="og:title" content="Android 开发者 &nbsp;|&nbsp; Android Developers">

      <meta name="description"                    content="无论您要针对 Android 手机、Wear OS by Google 谷歌、Android TV、Android Auto 还是 Android Things 构建应用，本节都可以提供您所需的指南和 API 参考。
">
          <meta property="og:description" content="无论您要针对 Android 手机、Wear OS by Google 谷歌、Android TV、Android Auto 还是 Android Things 构建应用，本节都可以提供您所需的指南和 API 参考。
">
      
  <meta property="og:url" content="https://developer.android.google.cn/docs?hl=zh-cn">

  <meta property="og:image" content="https://developer.android.google.cn/images/android-developers.png">
  <meta property="og:image:secure_url" content="https://developer.android.google.cn/images/android-developers.png">
  <meta property="og:image:width" content="1200">
  <meta property="og:image:height" content="675">
  <meta property="og:locale" content="zh_cn">
  <meta name="twitter:card" content="summary_large_image">






    </head>
  <body type="landing"
        theme="android-theme"
        class="dac-landing-page dac-docs-overview-page"
        
        layout="full"
        block-apix                pending>
    <devsite-progress type="indeterminate" id="app-progress"></devsite-progress>
    <section class="devsite-wrapper"><devsite-header>








<div class="devsite-header--inner">
  <div class="devsite-top-logo-row-wrapper-wrapper">
    <div class="devsite-top-logo-row-wrapper">
      <div class="devsite-top-logo-row">
        <button type="button" id="devsite-hamburger-menu"
          class="devsite-header-icon-button button-flat material-icons gc-analytics-event"
          data-category="Site-Wide Custom Events"
          data-label="Navigation menu button"
          visually-hidden
          aria-label="Open menu">
        </button>
        <div class="devsite-product-name-wrapper">
  <a href="/" class="devsite-site-logo-link gc-analytics-event"
   data-category="Site-Wide Custom Events" data-label="Site logo" track-type="globalNav"
   track-name="androidDevelopers" track-metadata-position="nav"
   track-metadata-eventDetail="nav">
  <img src="https://www.gstatic.cn/devrel-devsite/prod/ve2ae1395f351e38dc0b3037132204261d76b8f1c638764d7fd2c2fbb865782fc/android/images/lockup.svg" class="devsite-site-logo" alt="Android Developers">
</a>

  <span class="devsite-product-name">
    <ul class="devsite-breadcrumb-list">
    <li class="devsite-breadcrumb-item
             ">
                              </li>
  </ul>
  </span>
</div>
        <div class="devsite-top-logo-row-middle">
          <div class="devsite-header-upper-tabs">
                            <devsite-tabs class="upper-tabs">
    <div class="devsite-tabs-wrapper">
                        <tab  >
            <a href="/about"
   class="gc-analytics-event"
   track-type="globalNav"
   track-metadata-position="nav"
   track-metadata-eventdetail="nav"
   track-name="平台"
           data-category="Site-Wide Custom Events"
        data-label="Tab: 平台"
   >
   >平台
   ></a>

          </tab>
                                <tab  >
            <a href="/studio"
   class="gc-analytics-event"
   track-type="globalNav"
   track-metadata-position="nav"
   track-metadata-eventdetail="nav"
   track-name="androidStudio"
           data-category="Site-Wide Custom Events"
        data-label="Tab: Android Studio"
   >
   >Android Studio
   ></a>

          </tab>
                                <tab  >
            <a href="/distribute"
   class="gc-analytics-event"
   track-type="globalNav"
   track-metadata-position="nav"
   track-metadata-eventdetail="nav"
   track-name="googlePlay"
           data-category="Site-Wide Custom Events"
        data-label="Tab: Google Play"
   >
   >Google Play
   ></a>

          </tab>
                                <tab  >
            <a href="/jetpack"
   class="gc-analytics-event"
   track-type="globalNav"
   track-metadata-position="nav"
   track-metadata-eventdetail="nav"
   track-name="jetpack"
           data-category="Site-Wide Custom Events"
        data-label="Tab: Jetpack"
   >
   >Jetpack
   ></a>

          </tab>
                                <tab  >
            <a href="/kotlin"
   class="gc-analytics-event"
   track-type="globalNav"
   track-metadata-position="nav"
   track-metadata-eventdetail="nav"
   track-name="kotlin"
           data-category="Site-Wide Custom Events"
        data-label="Tab: Kotlin"
   >
   >Kotlin
   ></a>

          </tab>
                                <tab  active>
            <a href="/docs"
   class="gc-analytics-event"
   track-type="globalNav"
   track-metadata-position="nav"
   track-metadata-eventdetail="nav"
   track-name="文档"
   aria-label="文档, selected"         data-category="Site-Wide Custom Events"
        data-label="Tab: 文档"
   >
   >文档
   ></a>

          </tab>
                                <tab  >
            <a href="/news"
   class="gc-analytics-event"
   track-type="globalNav"
   track-metadata-position="nav"
   track-metadata-eventdetail="nav"
   track-name="新闻"
           data-category="Site-Wide Custom Events"
        data-label="Tab: 新闻"
   >
   >新闻
   ></a>

          </tab>
                  </div>
  </devsite-tabs>


                       </div>
          <devsite-search
            enable-suggestions
              project-name="Android 开发者"    tenant-name="Android Developers"                >
  <form class="devsite-search-form" action="https://developer.android.google.cn/s/results" method="GET">
    <div class="devsite-search-container">
      <div class="devsite-searchbox">
                <input placeholder="搜索"
          type="text"
          class="devsite-search-field devsite-search-query"
          name="q"
          value=""
          autocomplete="off"
                    aria-label="搜索框">
        <div class="devsite-search-image material-icons" aria-hidden="true"></div>
      </div>
      <button type="button"
              search-open
              class="devsite-search-button devsite-header-icon-button button-flat material-icons"
              aria-label="Open search box"></button>
    </div>
  </form>
  <button type="button"
          search-close
          class="devsite-search-button devsite-header-icon-button button-flat material-icons"
          aria-label="Close search box"></button>
</devsite-search>

        </div>


​        
        <devsite-language-selector>
  <devsite-select class="devsite-language-selector-menu">
    <select class="devsite-language-selector-select"
            name="language"
            track-name="click"
            track-type="languageSelector">
              <option value="id"
              track-metadata-original-language="zh_cn"
              track-metadata-selected-language="id"
              track-name="changed"
              track-type="languageSelector"
            >
        Bahasa Indonesia
      </option>
          <option value="de"
              track-metadata-original-language="zh_cn"
              track-metadata-selected-language="de"
              track-name="changed"
              track-type="languageSelector"
            >
        Deutsch
      </option>
          <option value="en"
              track-metadata-original-language="zh_cn"
              track-metadata-selected-language="en"
              track-name="changed"
              track-type="languageSelector"
            >
        English
      </option>
          <option value="es"
              track-metadata-original-language="zh_cn"
              track-metadata-selected-language="es"
              track-name="changed"
              track-type="languageSelector"
            >
        Español
      </option>
          <option value="es_419"
              track-metadata-original-language="zh_cn"
              track-metadata-selected-language="es_419"
              track-name="changed"
              track-type="languageSelector"
            >
        Español – América Latina
      </option>
          <option value="fr"
              track-metadata-original-language="zh_cn"
              track-metadata-selected-language="fr"
              track-name="changed"
              track-type="languageSelector"
            >
        Français
      </option>
          <option value="pt_br"
              track-metadata-original-language="zh_cn"
              track-metadata-selected-language="pt_br"
              track-name="changed"
              track-type="languageSelector"
            >
        Português – Brasil
      </option>
          <option value="vi"
              track-metadata-original-language="zh_cn"
              track-metadata-selected-language="vi"
              track-name="changed"
              track-type="languageSelector"
            >
        Tiếng Việt
      </option>
          <option value="tr"
              track-metadata-original-language="zh_cn"
              track-metadata-selected-language="tr"
              track-name="changed"
              track-type="languageSelector"
            >
        Türkçe
      </option>
          <option value="ru"
              track-metadata-original-language="zh_cn"
              track-metadata-selected-language="ru"
              track-name="changed"
              track-type="languageSelector"
            >
        Русский
      </option>
          <option value="th"
              track-metadata-original-language="zh_cn"
              track-metadata-selected-language="th"
              track-name="changed"
              track-type="languageSelector"
            >
        ภาษาไทย
      </option>
          <option value="zh_cn"
              track-metadata-original-language="zh_cn"
              track-metadata-selected-language="zh_cn"
              track-name="changed"
              track-type="languageSelector"
                          selected="selected"
            >
        中文 – 简体
      </option>
          <option value="zh_tw"
              track-metadata-original-language="zh_cn"
              track-metadata-selected-language="zh_tw"
              track-name="changed"
              track-type="languageSelector"
            >
        中文 – 繁體
      </option>
          <option value="ja"
              track-metadata-original-language="zh_cn"
              track-metadata-selected-language="ja"
              track-name="changed"
              track-type="languageSelector"
            >
        日本語
      </option>
          <option value="ko"
              track-metadata-original-language="zh_cn"
              track-metadata-selected-language="ko"
              track-name="changed"
              track-type="languageSelector"
            >
        한국어
      </option>
        </select>
  </devsite-select>
</devsite-language-selector>


​        
              </div>    </div>  </div>
  <div class="devsite-collapsible-section
    ">
    <div class="devsite-header-background">
                        <div class="devsite-product-id-row"
           >
            <div class="devsite-product-description-row">
                                                <ul class="devsite-breadcrumb-list">
    <li class="devsite-breadcrumb-item
             ">
                    <a href="/docs"              class="devsite-breadcrumb-link gc-analytics-event"
              data-category="Site-Wide Custom Events"
              data-label="Lower Header"
              data-value="1"
          >
            文档

  </a>
        </li>
  </ul>
                                                              <div class="devsite-product-description"></div>

                          </div>
                                                                            </div>
                                      <div class="devsite-doc-set-nav-row">
                                                      <devsite-tabs class="lower-tabs">
    <div class="devsite-tabs-wrapper">
                        <tab  active>
            <a href="/docs"
   class="gc-analytics-event"
   track-type="globalNav"
   track-metadata-position="nav"
   track-metadata-eventdetail="nav"
   track-name="概览"
   aria-label="概览, selected"         data-category="Site-Wide Custom Events"
        data-label="Tab: 概览"
   >
   >概览
   ></a>

          </tab>
                                <tab  >
            <a href="/guide"
   class="gc-analytics-event"
   track-type="globalNav"
   track-metadata-position="nav"
   track-metadata-eventdetail="nav"
   track-name="指南"
           data-category="Site-Wide Custom Events"
        data-label="Tab: 指南"
   >
   >指南
   ></a>

          </tab>
                                <tab  >
            <a href="/reference"
   class="gc-analytics-event"
   track-type="globalNav"
   track-metadata-position="nav"
   track-metadata-eventdetail="nav"
   track-name="参考"
           data-category="Site-Wide Custom Events"
        data-label="Tab: 参考"
   >
   >参考
   ></a>

          </tab>
                                <tab  >
            <a href="/samples"
   class="gc-analytics-event"
   track-type="globalNav"
   track-metadata-position="nav"
   track-metadata-eventdetail="nav"
   track-name="示例"
           data-category="Site-Wide Custom Events"
        data-label="Tab: 示例"
   >
   >示例
   ></a>

          </tab>
                                <tab  >
            <a href="/design"
   class="gc-analytics-event"
   track-type="globalNav"
   track-metadata-position="nav"
   track-metadata-eventdetail="nav"
   track-name="设计和质量"
           data-category="Site-Wide Custom Events"
        data-label="Tab: 设计和质量"
   >
   >设计和质量
   ></a>

          </tab>
                  </div>
  </devsite-tabs>


                            </div>
          </div>  </div></div>


  </devsite-header>      <devsite-book-nav scrollbars hidden>
                  





<nav class="devsite-book-nav devsite-nav nocontent">
  <div class="devsite-mobile-header">
    <button type="button"
            id="devsite-close-nav"
            class="devsite-header-icon-button button-flat material-icons gc-analytics-event"
            data-category="Site-Wide Custom Events"
            data-label="Close navigation"
            aria-label="Close navigation">
    </button>
    <div class="devsite-product-name-wrapper">
  <a href="/" class="devsite-site-logo-link gc-analytics-event"
   data-category="Site-Wide Custom Events" data-label="Site logo" track-type="globalNav"
   track-name="androidDevelopers" track-metadata-position="nav"
   track-metadata-eventDetail="nav">
  <img src="https://www.gstatic.cn/devrel-devsite/prod/ve2ae1395f351e38dc0b3037132204261d76b8f1c638764d7fd2c2fbb865782fc/android/images/lockup.svg" class="devsite-site-logo" alt="Android Developers">
</a>
        <span class="devsite-product-name">
        <ul class="devsite-breadcrumb-list">
    <li class="devsite-breadcrumb-item
             ">
                              </li>
  </ul>
      </span>

</div>  </div>

  <div class="devsite-book-nav-wrapper">
    <div class="devsite-mobile-nav-top">
              <ul class="devsite-nav-list">
                      <li class="devsite-nav-item">
                  <a href="/about"
           class="devsite-nav-title gc-analytics-event
                            "

         data-category="Site-Wide Custom Events"
     data-label="Responsive Tab: 平台"
     track-type="navMenu"
     track-metadata-eventDetail="globalMenu"
     track-metadata-position="nav"
     track-name="平台">
      <span class="devsite-nav-text" tooltip >
      平台
   </span>
        </a>

                                        </li>
                      <li class="devsite-nav-item">
                  <a href="/studio"
           class="devsite-nav-title gc-analytics-event
                            "
    
         data-category="Site-Wide Custom Events"
     data-label="Responsive Tab: Android Studio"
     track-type="navMenu"
     track-metadata-eventDetail="globalMenu"
     track-metadata-position="nav"
     track-name="androidStudio">
      <span class="devsite-nav-text" tooltip >
      Android Studio
   </span>
        </a>

                                        </li>
                      <li class="devsite-nav-item">
                  <a href="/distribute"
           class="devsite-nav-title gc-analytics-event
                            "
    
         data-category="Site-Wide Custom Events"
     data-label="Responsive Tab: Google Play"
     track-type="navMenu"
     track-metadata-eventDetail="globalMenu"
     track-metadata-position="nav"
     track-name="googlePlay">
      <span class="devsite-nav-text" tooltip >
      Google Play
   </span>
        </a>

                                        </li>
                      <li class="devsite-nav-item">
                  <a href="/jetpack"
           class="devsite-nav-title gc-analytics-event
                            "
    
         data-category="Site-Wide Custom Events"
     data-label="Responsive Tab: Jetpack"
     track-type="navMenu"
     track-metadata-eventDetail="globalMenu"
     track-metadata-position="nav"
     track-name="jetpack">
      <span class="devsite-nav-text" tooltip >
      Jetpack
   </span>
        </a>

                                        </li>
                      <li class="devsite-nav-item">
                  <a href="/kotlin"
           class="devsite-nav-title gc-analytics-event
                            "
    
         data-category="Site-Wide Custom Events"
     data-label="Responsive Tab: Kotlin"
     track-type="navMenu"
     track-metadata-eventDetail="globalMenu"
     track-metadata-position="nav"
     track-name="kotlin">
      <span class="devsite-nav-text" tooltip >
      Kotlin
   </span>
        </a>

                                        </li>
                      <li class="devsite-nav-item">
                  <a href="/docs"
           class="devsite-nav-title gc-analytics-event
                            devsite-nav-active"
    
         data-category="Site-Wide Custom Events"
     data-label="Responsive Tab: 文档"
     track-type="navMenu"
     track-metadata-eventDetail="globalMenu"
     track-metadata-position="nav"
     track-name="文档">
      <span class="devsite-nav-text" tooltip >
      文档
   </span>
        </a>

                                            <ul class="devsite-nav-responsive-tabs">
                                                                                                  <li class="devsite-nav-item">
    <a href="/docs"
           class="devsite-nav-title gc-analytics-event
                            devsite-nav-active"
    
         data-category="Site-Wide Custom Events"
     data-label="Responsive Tab: 概览"
     track-type="navMenu"
     track-metadata-eventDetail="globalMenu"
     track-metadata-position="nav"
     track-name="概览">
      <span class="devsite-nav-text" tooltip >
      概览
   </span>
        </a>
  </li>

                                                                                                  <li class="devsite-nav-item">
    <a href="/guide"
           class="devsite-nav-title gc-analytics-event
              devsite-nav-has-children              "
    
         data-category="Site-Wide Custom Events"
     data-label="Responsive Tab: 指南"
     track-type="navMenu"
     track-metadata-eventDetail="globalMenu"
     track-metadata-position="nav"
     track-name="指南">
      <span class="devsite-nav-text" tooltip menu="_book">
      指南
   </span>
        <span class="devsite-nav-icon material-icons" data-icon="forward"
          menu="_book">
    </span>
        </a>
  </li>

                                                                                                  <li class="devsite-nav-item">
    <a href="/reference"
           class="devsite-nav-title gc-analytics-event
              devsite-nav-has-children              "
    
         data-category="Site-Wide Custom Events"
     data-label="Responsive Tab: 参考"
     track-type="navMenu"
     track-metadata-eventDetail="globalMenu"
     track-metadata-position="nav"
     track-name="参考">
      <span class="devsite-nav-text" tooltip menu="_book">
      参考
   </span>
        <span class="devsite-nav-icon material-icons" data-icon="forward"
          menu="_book">
    </span>
        </a>
  </li>

                                                                                                  <li class="devsite-nav-item">
    <a href="/samples"
           class="devsite-nav-title gc-analytics-event
                            "
    
         data-category="Site-Wide Custom Events"
     data-label="Responsive Tab: 示例"
     track-type="navMenu"
     track-metadata-eventDetail="globalMenu"
     track-metadata-position="nav"
     track-name="示例">
      <span class="devsite-nav-text" tooltip >
      示例
   </span>
        </a>
  </li>

                                                                                                  <li class="devsite-nav-item">
    <a href="/design"
           class="devsite-nav-title gc-analytics-event
              devsite-nav-has-children              "
    
         data-category="Site-Wide Custom Events"
     data-label="Responsive Tab: 设计和质量"
     track-type="navMenu"
     track-metadata-eventDetail="globalMenu"
     track-metadata-position="nav"
     track-name="设计和质量">
      <span class="devsite-nav-text" tooltip menu="_book">
      设计和质量
   </span>
        <span class="devsite-nav-icon material-icons" data-icon="forward"
          menu="_book">
    </span>
        </a>
  </li>

                                  </ul>
                          </li>
                      <li class="devsite-nav-item">
                  <a href="/news"
           class="devsite-nav-title gc-analytics-event
                            "
    
         data-category="Site-Wide Custom Events"
     data-label="Responsive Tab: 新闻"
     track-type="navMenu"
     track-metadata-eventDetail="globalMenu"
     track-metadata-position="nav"
     track-name="新闻">
      <span class="devsite-nav-text" tooltip >
      新闻
   </span>
        </a>

                                        </li>
                    
                  </ul>
          </div>
      </div>
</nav>
              </devsite-book-nav>
      <section id="gc-wrapper">
        <main role="main" class="devsite-main-content"
                        >
          <devsite-toc class="devsite-nav"
            disabled></devsite-toc>
          <devsite-content>
                          

<article class="devsite-article">
  <article class="devsite-article-inner">        
    <div class="devsite-article-meta">
      <ul class="devsite-breadcrumb-list">
    <li class="devsite-breadcrumb-item
             ">
                    <a href="/"              class="devsite-breadcrumb-link gc-analytics-event"
              data-category="Site-Wide Custom Events"
              data-label="Breadcrumbs"
              data-value="1"
          >
            Android 开发者

  </a>
        </li>
    <li class="devsite-breadcrumb-item
             ">
                <div class="devsite-breadcrumb-guillemet material-icons" aria-hidden="true"></div>
                    <a href="/docs"              class="devsite-breadcrumb-link gc-analytics-event"
              data-category="Site-Wide Custom Events"
              data-label="Breadcrumbs"
              data-value="2"
          >
            文档
      
  </a>
        </li>
  </ul>
          </div>


    <devsite-toc class="devsite-nav" devsite-toc-embedded
                 disabled>
    </devsite-toc>
    
    <div class="devsite-article-body clearfix
              devsite-no-page-title
      ">
    
                <section class="devsite-landing-row devsite-landing-row-1-up"
           
           >
    
      <div class="devsite-landing-row-html">
      <div class="dac-landing-row-hero">
  <h1 style="padding: 0"><wbr></wbr>应用开发者文档</h1>
  <div class="dac-landing-row-hero-description">
    <p>无论您要针对 Android 手机、Wear OS by Google 谷歌、Android TV、Android Auto 还是 Android Things 打造应用，本部分都可以提供您所需的指南和 API 参考文档。</p>
  </div>
</div>

    </div>

  

  </section>
  <section class="devsite-landing-row devsite-landing-row-2-up dac-grow-column-4-8"

           >


​      
          <div class="devsite-landing-row-group">
              <div class="devsite-landing-row-column">
          
                                <div class="devsite-landing-row-item devsite-landing-row-item-no-media dac-landing-row-bg-blue dac-landing-row-item-invert dac-full-height dac-heading-small dac-guides-flex-columns-xs"
     
     >

  

​    

        <div class="devsite-landing-row-item-description"
         >


​      

      <div class="devsite-landing-row-item-body">
        
              <a href="/guide/">
        <h3 id="">
      开始使用</h3>

  </a>
    

                  <div class="devsite-landing-row-item-description-content">
            <div class="dac-guides">
  <div class="dac-guides-group">
    <h4><a href="/training/basics/firstapp/">构建首个应用</a></h4>
  </div>
  <div class="dac-guides-group">
    <h4><a href="/samples/">示例代码</a></h4>
  </div>
  <div class="dac-guides-group">
    <h4><a href="/reference/">API 参考</a></h4>
  </div>
  <div class="dac-guides-group">
    <h4><a href="/design/">设计指南</a></h4>
  </div>
  <div class="dac-guides-group">
    <h4><a href="https://codelabs.developers.google.com/?cat=Android" class="external">Codelab 教程</a></h4>
  </div>
  <div class="dac-guides-group">
    <h4><a href="https://developers.google.cn/training/android/" class="external">培训课程</a></h4>
  </div>
</div>

          </div>


​        
              </div>
    </div>

</div>
                  </div>
              <div class="devsite-landing-row-column">
          
                                <div class="devsite-landing-row-item devsite-landing-row-item-no-media dac-heading-small dac-guides-flex-columns"
         background="grey"
      
     >

  

​    

        <div class="devsite-landing-row-item-description"
         >


​      

      <div class="devsite-landing-row-item-body">
        
              <a href="/guide/">
        <h3 id="android">
      Android 设备</h3>

  </a>
    

                  <div class="devsite-landing-row-item-description-content">
            <div class="dac-guides">
  <div class="dac-guides-group">
    <h4><a href="/training/wearables/">Wear OS</a></h4>
  </div>
  <div class="dac-guides-group">
    <h4><a href="/training/tv/">Android TV</a></h4>
  </div>
  <div class="dac-guides-group">
    <h4><a href="/training/auto/">Android Auto</a></h4>
  </div>
  <div class="dac-guides-group">
    <h4><a href="/things/get-started/">Android Things</a></h4>
  </div>
  <div class="dac-guides-group">
    <h4><a href="/chrome-os/intro">Chrome 操作系统设备</a></h4>
  </div>
</div>

          </div>


​        
              </div>
    </div>

</div>
                      <div class="devsite-landing-row-item devsite-landing-row-item-no-media dac-heading-small dac-guides-flex-columns"
         background="grey"

     >

  

​    

        <div class="devsite-landing-row-item-description"
         >


​      

      <div class="devsite-landing-row-item-body">
        
              <a href="/guide/">
        <h3 id="">
      最佳做法</h3>

  </a>
    

                  <div class="devsite-landing-row-item-description-content">
            <div class="dac-guides">
  <div class="dac-guides-group">
    <h4><a href="/training/testing/">测试</a></h4>
  </div>
  <div class="dac-guides-group">
    <h4><a href="/topic/performance/">性能</a></h4>
  </div>
  <div class="dac-guides-group">
    <h4><a href="/guide/topics/ui/accessibility/">无障碍</a></h4>
  </div>
  <div class="dac-guides-group">
    <h4><a href="/topic/security/best-practices">安全</a></h4>
  </div>
  <div class="dac-guides-group">
    <h4><a href="/work/overview">企业</a></h4>
  </div>
  <div class="dac-guides-group">
    <h4><a href="/topic/billions/">新兴市场</a></h4>
  </div>
</div>

          </div>


​        
              </div>
    </div>

</div>
                  </div>
            </div>

​        

  </section>
  <section class="devsite-landing-row devsite-landing-row-2-up"

           >


​      
​    
      <div class="devsite-landing-row-group">
              <div class="devsite-landing-row-item devsite-landing-row-item-no-media dac-grow-3 dac-heading-small dac-guides-flex-columns
"
         background="grey"

     >

  

​    

        <div class="devsite-landing-row-item-description"
         >


​      

      <div class="devsite-landing-row-item-body">
        
              <a href="/guide/">
        <h3 id="">
      核心开发者主题</h3>

  </a>
    

                  <div class="devsite-landing-row-item-description-content">
            <div class="dac-guides">
  <div class="dac-guides-group">
    <h4><a href="/guide/components/activities/">Activity</a></h4>
  </div>
  <div class="dac-guides-group">
    <h4><a href="/guide/components/intents-filters">Intent 和 Intent 过滤器</a></h4>
  </div>
  <div class="dac-guides-group">
    <h4><a href="/guide/topics/ui/">界面和导航</a></h4>
  </div>
  <div class="dac-guides-group">
    <h4><a href="/training/animation/">动画和过渡</a></h4>
  </div>
  <div class="dac-guides-group">
    <h4><a href="/guide/topics/graphics/">图片和图形</a></h4>
  </div>
  <div class="dac-guides-group">
    <h4><a href="/guide/topics/media/">音频和视频</a></h4>
  </div>
  <div class="dac-guides-group">
    <h4><a href="/training/best-background">后台任务</a></h4>
  </div>
  <div class="dac-guides-group">
    <h4><a href="/guide/topics/data/">应用数据和文件</a></h4>
  </div>
  <div class="dac-guides-group">
    <h4><a href="/guide/user-data/">用户数据和身份</a></h4>
  </div>
  <div class="dac-guides-group">
    <h4><a href="/training/location/">用户位置</a></h4>
  </div>
  <div class="dac-guides-group">
    <h4><a href="/guide/input/">轻触和输入</a></h4>
  </div>
  <div class="dac-guides-group">
    <h4><a href="/training/camera/">相机</a></h4>
  </div>
  <div class="dac-guides-group">
    <h4><a href="/training/camerax/">CameraX</a></h4>
  </div>
  <div class="dac-guides-group">
    <h4><a href="/guide/topics/sensors/">传感器</a></h4>
  </div>
  <div class="dac-guides-group">
    <h4><a href="/guide/topics/connectivity/">网络连接</a></h4>
  </div>
  <div class="dac-guides-group">
    <h4><a href="/guide/topics/renderscript/">Renderscript</a></h4>
  </div>
  <div class="dac-guides-group">
    <h4><a href="/guide/webapps/">基于网络的内容</a></h4>
  </div>
  <div class="dac-guides-group">
    <h4><a href="/topic/instant-apps/">免安装应用</a></h4>
  </div>
</div>

          </div>


​        
                  <div class="devsite-landing-row-item-buttons">
      <a href="/guide"
      class="button dac-button dac-flat-button
      "
            >查看所有开发者指南</a></div>
              </div>
    </div>

</div>
              <div class="devsite-landing-row-item devsite-landing-row-item-no-media dac-landing-row-bg-slate dac-landing-row-item-invert dac-landing-row-bg-blob-5 dac-heading-small dac-landing-row-item-empty
"
     
     >

  

​    

        <div class="devsite-landing-row-item-description"
         >


​      

      <div class="devsite-landing-row-item-body">
        
              <a href="/design/">
        <h3 id="">
      设计指南</h3>

  </a>
    

                  <div class="devsite-landing-row-item-description-content">
            <div class="dac-guides">
  <div class="dac-guides-group">
    <h4><a href="/design/">Material Design</a></h4>
  </div>
  <div class="dac-guides-group">
    <h4><a href="/develop/quality-guidelines/core-app-quality">核心应用质量</a></h4>
  </div>
  <div class="dac-guides-group">
    <h4><a href="/docs/quality-guidelines/tablet-app-quality">平板电脑应用质量</a></h4>
  </div>
  <div class="dac-guides-group">
    <h4><a href="/docs/quality-guidelines/wear-app-quality">Wear 应用质量</a></h4>
  </div>
  <div class="dac-guides-group">
    <h4><a href="/docs/quality-guidelines/tv-app-quality">TV 应用质量</a></h4>
  </div>
  <div class="dac-guides-group">
    <h4><a href="/docs/quality-guidelines/auto-app-quality">Auto 应用质量</a></h4>
  </div>
</div>
          </div>
        
        
                  <div class="devsite-landing-row-item-buttons">
      <a href="/design"
      class="button dac-button dac-flat-button
      "
            >查看更多</a></div>
              </div>
    </div>

</div>
            </div>
    

  </section>
  <section class="devsite-landing-row devsite-landing-row-2-up"

           >


​      
​    
      <div class="devsite-landing-row-group">
              <div class="devsite-landing-row-item devsite-landing-row-item-no-media dac-grow-3 dac-heading-small dac-guides-flex-columns
"
         background="grey"

     >

  

​    

        <div class="devsite-landing-row-item-description"
         >


​      

      <div class="devsite-landing-row-item-body">
        
              <a href="/guide/">
        <h3 id="">
      更多文档</h3>

  </a>
    

                  <div class="devsite-landing-row-item-description-content">
            <div class="dac-guides">
  <div class="dac-guides-group">
    <h4><a href="/ndk/guides/">Android NDK</a></h4>
  </div>
  <div class="dac-guides-group">
    <h4><a href="/kotlin/">Kotlin</a></h4>
  </div>
  <div class="dac-guides-group">
    <h4><a href="/studio/intro/">Android Studio</a></h4>
  </div>
  <div class="dac-guides-group">
    <h4><a href="/google/">Google Play 服务</a></h4>
  </div>
  <div class="dac-guides-group">
    <h4><a href="/distribute/console/">Google Play 管理中心</a></h4>
  </div>
  <div class="dac-guides-group">
    <h4><a href="/about/">Android 版本</a></h4>
  </div>
</div>

          </div>


​        
              </div>
    </div>

</div>
              <div class="devsite-landing-row-item devsite-landing-row-item-no-description devsite-landing-row-item-no-media"
     
     >

  

​    


</div>
            </div>
    

  </section>
  <section class="devsite-landing-row devsite-landing-row-1-up dac-gutter"
               background="grey"

           >


​      
​    
      <div class="devsite-landing-row-group">
              <div class="devsite-landing-row-item"
     
     >
    
      <style>label {
  font-size: inherit;
}
</style> <div class="dac-subtitle dac-center">
  <h3>示例</h3>
  <form method="get" action="/samples" class="dac-samples-form">
    <label class="inline">
      查找相关示例：
      <select name="technology">
        <option value>Android</option>
        <option value="android auto">Android Auto</option>
        <option value="android tv">Android TV</option>
        <option value="android wear">Android Wear</option>
        <option value="firebase">Firebase</option>
        <option value="google cast">Google Cast</option>
        <option value="google mobile ads">Google 移动广告</option>
        <option value="google play billing">Google Play 结算服务</option>
        <option value="google play services">Google Play 服务</option>
        <option value="ndk">NDK</option>
      </select>
    </label>
    <button type="submit" class="button dac-button dac-submit-button">查看示例</button>
  </form>
</div>


</div>
            </div>
    

  </section>
  <section class="devsite-landing-row devsite-landing-row-2-up dac-grow-column-4-8 dac-column-switch dac-gutter dac-label"
               background="grey"

           >


​      
          <div class="devsite-landing-row-group">
              <div class="devsite-landing-row-column">
          
                                <div class="devsite-landing-row-item devsite-landing-row-item-no-media dac-label dac-landing-row dac-landing-row-item dac-illustration dac-illustration-keyline-3 dac-full-height dac-illustration-column dac-heading-linked"
         background="white"
      
     >

  

​    

        <div class="devsite-landing-row-item-description"
         >


​      

      <div class="devsite-landing-row-item-body">
                  <div class="devsite-landing-row-item-labels">
      <span
            class="                          "
            >Android</span></div>
        
              <a href="https://github.com/googlesamples/android-architecture">
        <h3 id="android">
      Android 架构蓝图</h3>

  </a>
    

                  <div class="devsite-landing-row-item-description-content">
            一系列讨论和展示适用于 Android 应用的不同架构工具和模式的示例。
    
          </div>


​        
              </div>
    </div>

</div>
                  </div>
              <div class="devsite-landing-row-column">
          
                                <div class="devsite-landing-row-item devsite-landing-row-item-no-media dac-label dac-landing-row dac-landing-row-item dac-heading-medium dac-grow-1 dac-heading-linked"
         background="white"
      
     >

  

​    

        <div class="devsite-landing-row-item-description"
         >


​      

      <div class="devsite-landing-row-item-body">
                  <div class="devsite-landing-row-item-labels">
      <span
            class="                          "
            >Java</span></div>
        
              <a href="https://github.com/googlesamples/android-UniversalMusicPlayer">
        <h3 id="universal-android-music-player">
      Universal Android Music Player 示例</h3>

  </a>
    

                  <div class="devsite-landing-row-item-description-content">
            此示例介绍了如何实现可在多种型号的设备上运行的音频媒体应用，以及如何在 Android 手机、平板电脑、Auto、Wear 和 Cast 设备上提供一致的用户体验。
    
          </div>


​        
              </div>
    </div>

</div>
                      <div class="devsite-landing-row-item devsite-landing-row-item-no-media dac-label dac-landing-row dac-landing-row-item dac-heading-medium dac-grow-1 dac-heading-linked"
         background="white"

     >

  

​    

        <div class="devsite-landing-row-item-description"
         >


​      

      <div class="devsite-landing-row-item-body">
                  <div class="devsite-landing-row-item-labels">
      <span
            class="                          "
            >Java</span></div>
        
              <a href="https://github.com/googlesamples/android-architecture-components">
        <h3 id="android">
      Android 架构组件示例</h3>

  </a>
    

                  <div class="devsite-landing-row-item-description-content">
            Android 架构组件示例。
    
          </div>


​        
              </div>
    </div>

</div>
                  </div>
            </div>

​        

  </section>
  <section class="devsite-landing-row devsite-landing-row-3-up"
               background="grey"

           >


​      
​    
      <div class="devsite-landing-row-group">
              <div class="devsite-landing-row-item devsite-landing-row-item-no-media dac-label dac-landing-row dac-landing-row-item dac-heading-medium dac-heading-linked"
         background="white"
      
     >

  

​    

        <div class="devsite-landing-row-item-description"
         >


​      

      <div class="devsite-landing-row-item-body">
                  <div class="devsite-landing-row-item-labels">
      <span
            class="                          "
            >Java</span></div>
        
              <a href="https://github.com/googlesamples/android-testing">
        <h3 id="android">
      Android 测试示例</h3>

  </a>
    

                  <div class="devsite-landing-row-item-description-content">
            一系列演示用于自动测试的不同框架和技术的示例。
    
          </div>


​        
              </div>
    </div>

</div>
              <div class="devsite-landing-row-item devsite-landing-row-item-no-media dac-label dac-landing-row dac-landing-row-item dac-heading-medium dac-heading-linked"
         background="white"

     >

  

​    

        <div class="devsite-landing-row-item-description"
         >


​      

      <div class="devsite-landing-row-item-body">
                  <div class="devsite-landing-row-item-labels">
      <span
            class="                          "
            >Kotlin</span></div>
        
              <a href="https://github.com/googlesamples/android-topeka">
        <h3 id="android-topeka">
      Android 版 Topeka</h3>

  </a>
    

                  <div class="devsite-landing-row-item-description-content">
            一个很好玩的测验，展示了 Android Material Design。
    
          </div>


​        
              </div>
    </div>

</div>
              <div class="devsite-landing-row-item devsite-landing-row-item-no-media dac-label dac-landing-row dac-landing-row-item dac-heading-medium dac-heading-linked"
         background="white"

     >

  

​    

        <div class="devsite-landing-row-item-description"
         >


​      

      <div class="devsite-landing-row-item-body">
                  <div class="devsite-landing-row-item-labels">
      <span
            class="                          "
            >C++</span></div>
        
              <a href="https://github.com/googlesamples/android-ndk">
        <h3 id="android-ndk">
      Android NDK 示例</h3>

  </a>
    

                  <div class="devsite-landing-row-item-description-content">
            Android Studio 的 Android NDK 示例。
    
          </div>


​        
              </div>
    </div>

</div>
            </div>
    

  </section>
  <section class="devsite-landing-row devsite-landing-row-1-up dac-gutter"
               background="grey"

           >


​      
​    
      <div class="devsite-landing-row-group">
              <div class="devsite-landing-row-item"
     
     >
    
      <div class="dac-subtitle dac-center">
  <h3>库</h3>
</div>


</div>
            </div>
    

  </section>
  <section class="devsite-landing-row devsite-landing-row-2-up dac-gutter"
               background="grey"

           >


​      
​    
      <div class="devsite-landing-row-group">
              <div class="devsite-landing-row-item devsite-landing-row-item-no-media dac-label dac-landing-row dac-landing-row-item dac-illustration dac-illustration-keyline-4 dac-landing-row-item-invert dac-landing-row-bg-slate dac-grow-7"
     
     >

  

​    

        <div class="devsite-landing-row-item-description"
         >


​      

      <div class="devsite-landing-row-item-body">
                  <div class="devsite-landing-row-item-labels">
      <span
            class="                          "
            >库</span></div>
        
              <a href="/topic/libraries/architecture/">
        <h3 id="android">
      Android 架构组件</h3>

  </a>
    

                  <div class="devsite-landing-row-item-description-content">
            此库为生命周期管理和数据持久性等基本应用架构任务提供 API，这样一来，您在编写模块化应用时就可以减少样板代码。
    
          </div>


​        
                  <div class="devsite-landing-row-item-buttons">
      <a href="/topic/libraries/architecture"
      class="button dac-button dac-alt-flat-button
      "
            >了解详情</a></div>
              </div>
    </div>

</div>
              <div class="devsite-landing-row-item devsite-landing-row-item-no-media dac-label dac-landing-row dac-landing-row-item dac-grow-5"
         background="white"

     >

  

​    

        <div class="devsite-landing-row-item-description"
         >


​      

      <div class="devsite-landing-row-item-body">
                  <div class="devsite-landing-row-item-labels">
      <span
            class="                          "
            >库</span></div>
        
              <a href="/topic/libraries/support-library/">
        <h3 id="">
      支持库</h3>

  </a>
    

                  <div class="devsite-landing-row-item-description-content">
            <p>Android 支持库提供了许多功能的向后兼容版本，包括未内置于 Android 框架的其他功能。</p> <div class="dac-illustration-block"><img src="/images/landing/keyline-illustration-5.svg" class="block"/></div>
    
          </div>


​        
                  <div class="devsite-landing-row-item-buttons">
      <a href="/topic/libraries/support-library"
      class="button dac-button dac-flat-button
      "
            >了解详情</a></div>
              </div>
    </div>

</div>
            </div>
    

  </section>
  <section class="devsite-landing-row devsite-landing-row-3-up dac-landing-row dac-landing-row-item"
               background="grey"

           >


​      
​    
      <div class="devsite-landing-row-group">
              <div class="devsite-landing-row-item devsite-landing-row-item-no-media dac-label"
         background="white"
      
     >

  

​    

        <div class="devsite-landing-row-item-description"
         >


​      

      <div class="devsite-landing-row-item-body">
                  <div class="devsite-landing-row-item-labels">
      <span
            class="                          "
            >库</span></div>
        
              <a href="/topic/libraries/data-binding/">
        <h3 id="">
      数据绑定库</h3>

  </a>
    

                  <div class="devsite-landing-row-item-description-content">
            借助数据绑定库，您可以编写声明式布局。
    
          </div>


​        
                  <div class="devsite-landing-row-item-buttons">
      <a href="/topic/libraries/data-binding"
      class="button dac-button dac-flat-button
      "
            >了解详情</a></div>
              </div>
    </div>

</div>
              <div class="devsite-landing-row-item devsite-landing-row-item-no-media dac-label dac-landing-row dac-landing-row-item"
         background="white"

     >

  

​    

        <div class="devsite-landing-row-item-description"
         >


​      

      <div class="devsite-landing-row-item-body">
                  <div class="devsite-landing-row-item-labels">
      <span
            class="                          "
            >库</span></div>
        
              <a href="/training/testing">
        <h3 id="android">
      Android 测试</h3>

  </a>
    

                  <div class="devsite-landing-row-item-description-content">
            Android Test 可帮助您为应用编译和运行测试代码。
    
          </div>


​        
                  <div class="devsite-landing-row-item-buttons">
      <a href="/topic/libraries/testing-support-library"
      class="button dac-button dac-flat-button
      "
            >了解详情</a></div>
              </div>
    </div>

</div>
              <div class="devsite-landing-row-item devsite-landing-row-item-no-media dac-label dac-landing-row dac-landing-row-item"
         background="white"

     >

  

​    

        <div class="devsite-landing-row-item-description"
         >


​      

      <div class="devsite-landing-row-item-body">
                  <div class="devsite-landing-row-item-labels">
      <span
            class="                          "
            >库</span></div>
        
              <a href="/google/play/billing/billing_library">
        <h3 id="play">
      Play 结算库</h3>

  </a>
    

                  <div class="devsite-landing-row-item-description-content">
            Google Play 结算服务提供了一个简单的接口，使您能够通过 Google Play 发送结算请求和管理结算事务。
    
          </div>


​        
                  <div class="devsite-landing-row-item-buttons">
      <a href="/google/play/billing/billing_library"
      class="button dac-button dac-flat-button
      "
            >了解详情</a></div>
              </div>
    </div>

</div>
            </div>
    

  </section>
  <section class="devsite-landing-row devsite-landing-row-1-up"

           >


​      
​    
      <div class="devsite-landing-row-group">
              <div class="devsite-landing-row-item"
     
     >
    
      <div class="dac-subtitle dac-center">
  <h3>开发者工具</h3>
</div>


</div>
            </div>
    

  </section>
  <section class="devsite-landing-row devsite-landing-row-2-up"

           >


​      
          <div class="devsite-landing-row-group">
              <div class="devsite-landing-row-column">
          
                                <div class="devsite-landing-row-item devsite-landing-row-item-no-media dac-label dac-landing-row dac-landing-row-item dac-illustration dac-illustration-keyline-1 dac-landing-row-item-invert dac-landing-row-bg-green dac-full-height"
     
     >

  

​    

        <div class="devsite-landing-row-item-description"
         >


​      

      <div class="devsite-landing-row-item-body">
                  <div class="devsite-landing-row-item-labels">
      <span
            class="                          "
            >指南</span></div>
        
              <a href="/training/basics/firstapp/">
        <h3 id="android">
      Android 模拟器</h3>

  </a>
    

                  <div class="devsite-landing-row-item-description-content">
            与使用物理设备相比，您可以在 Android 模拟器上更快地安装和运行应用。它可以模拟各种不同的设备配置和硬件传感器，以及使用快照快速回到上次停下的地方。
    
          </div>


​        
                  <div class="devsite-landing-row-item-buttons">
      <a href="/studio/run/emulator"
      class="button dac-button dac-flat-button
      "
            >运行应用</a></div>
              </div>
    </div>

</div>
                  </div>
              <div class="devsite-landing-row-column">
          
                                <div class="devsite-landing-row-item devsite-landing-row-item-no-media dac-label dac-landing-row dac-landing-row-item dac-grow-1 dac-heading-small"
         background="grey"
      
     >

  

​    

        <div class="devsite-landing-row-item-description"
         >


​      

      <div class="devsite-landing-row-item-body">
                  <div class="devsite-landing-row-item-labels">
      <span
            class="                          "
            >指南</span></div>
        
              <a href="/studio/build/">
        <h3 id="">
      配置编译系统</h3>

  </a>
    

                  <div class="devsite-landing-row-item-description-content">
            Android Studio 使用高级编译工具包 Gradle 自动执行编译流程，同时可让您设定灵活的自定义编译配置。
    
          </div>


​        
                  <div class="devsite-landing-row-item-buttons">
      <a href="/studio/build"
      class="button dac-button dac-alt-flat-button
      "
            >配置编译系统</a></div>
              </div>
    </div>

</div>
                      <div class="devsite-landing-row-item devsite-landing-row-item-no-media dac-label dac-landing-row dac-landing-row-item dac-grow-1 dac-heading-small"
         background="grey"

     >

  

​    

        <div class="devsite-landing-row-item-description"
         >


​      

      <div class="devsite-landing-row-item-body">
                  <div class="devsite-landing-row-item-labels">
      <span
            class="                          "
            >指南</span></div>
        
              <a href="/studio/debug/">
        <h3 id="">
      构建界面布局</h3>

  </a>
    

                  <div class="devsite-landing-row-item-description-content">
            Android Studio 包含一个布局编辑器，可让您构建和预览自己的应用界面，为此，您只需将元素拖动到可视化设计编辑器即可，无需手动编写布局 XML。
    
          </div>


​        
                  <div class="devsite-landing-row-item-buttons">
      <a href="/studio/write/layout-editor"
      class="button dac-button dac-alt-flat-button
      "
            >了解布局编辑器</a></div>
              </div>
    </div>

</div>
                  </div>
            </div>

​        

  </section>
  <section class="devsite-landing-row devsite-landing-row-1-up dac-landing-row dac-landing-row-collapse dac-landing-row-bg-blob-1 dac-profile-blob"
               background="grey"

           >


​      
​    
      <div class="devsite-landing-row-group">
              <div class="devsite-landing-row-item devsite-landing-row-item-no-media dac-label dac-landing-row dac-landing-row-collapse dac-illustration dac-landing-row-bg-illustration-2"
     
     >

  

​    

        <div class="devsite-landing-row-item-description"
         >


​      

      <div class="devsite-landing-row-item-body">
                  <div class="devsite-landing-row-item-labels">
      <span
            class="                          "
            >指南</span></div>
        
              <a href="/studio/profile/">
        <h3 id="">
      分析应用性能</h3>

  </a>
    

                  <div class="devsite-landing-row-item-description-content">
            应用性能不佳会破坏用户体验，损害应用的声誉。如果应用响应速度慢、动画播放不流畅、卡顿、崩溃或极其耗电，用户会察觉到这些问题。为避免出现这些性能问题，您可以使用 Android Profiler 衡量应用的内存、CPU 和网络使用情况。
    
          </div>


​        
                  <div class="devsite-landing-row-item-buttons">
      <a href="/studio/profile/android-profiler"
      class="button dac-button dac-alt-flat-button
      "
            >分析应用</a></div>
              </div>
    </div>

</div>
            </div>
    

  </section>
  <section class="devsite-landing-row devsite-landing-row-1-up dac-gutter"
               background="grey"

           >


​      
​    
      <div class="devsite-landing-row-group">
              <div class="devsite-landing-row-item"
     
     >
    
      <div class="dac-subtitle dac-center">
  <h3>更多教育资源</h3>
  <p>查看以下其他资源，无论是初学者还是经验丰富的 Android 开发者，均可参阅。</p>
</div>


</div>
            </div>
    

  </section>
  <section class="devsite-landing-row devsite-landing-row-3-up"
               background="grey"

           >


​      
​    
      <div class="devsite-landing-row-group">
              <div class="devsite-landing-row-item devsite-landing-row-item-no-media dac-landing-row dac-landing-row-item dac-heading-medium dac-heading-linked
"
         background="white"

     >

  

​    

        <div class="devsite-landing-row-item-description"
         >


​      

      <div class="devsite-landing-row-item-body">
        
              <a href="https://codelabs.developers.google.com/?cat=Android">
        <h3 id="android-codelab">
      Android Codelab</h3>

  </a>
    

                  <div class="devsite-landing-row-item-description-content">
            Codelab 是一种可按自己的进度学习的简短教程，可指导您完成构建特定类型的应用或为现有应用添加新功能的过程。
    
          </div>


​        
                  <div class="devsite-landing-row-item-buttons">
      <a href="https://codelabs.developers.google.com/?cat=Android"
      class="button dac-button dac-flat-button
      "
            >试用 Codelab</a></div>
              </div>
    </div>

</div>
              <div class="devsite-landing-row-item devsite-landing-row-item-no-media dac-landing-row dac-landing-row-item dac-heading-medium dac-heading-linked
"
         background="white"

     >

  

​    

        <div class="devsite-landing-row-item-description"
         >


​      

      <div class="devsite-landing-row-item-body">
        
              <a href="https://www.udacity.com/google">
        <h3 id="">
      在线视频课程</h3>

  </a>
    

                  <div class="devsite-landing-row-item-description-content">
            Google 与 Udacity 合作以在线视频形式推出 Android 开发教学课程，您可以学习几个免费的课程，也可以报名参加纳米学位课程。
    
          </div>


​        
                  <div class="devsite-landing-row-item-buttons">
      <a href="https://www.udacity.com/google"
      class="button dac-button dac-flat-button
      "
            >转至 Udacity</a></div>
              </div>
    </div>

</div>
              <div class="devsite-landing-row-item devsite-landing-row-item-no-media dac-landing-row dac-landing-row-item dac-heading-medium dac-heading-linked
"
         background="white"

     >

  

​    

        <div class="devsite-landing-row-item-description"
         >


​      

      <div class="devsite-landing-row-item-body">
        
              <a href="https://developers.google.cn/training/adf">
        <h3 id="">
      培训课程</h3>

  </a>
    

                  <div class="devsite-landing-row-item-description-content">
            这些在线培训可指导您完成构建 Android 应用的整个流程。无论您是新手还是高级开发者都值得参考。
    
          </div>


​        
                  <div class="devsite-landing-row-item-buttons">
      <a href="https://developers.google.cn/training/adf"
      class="button dac-button dac-flat-button
      "
            >查看课程</a></div>
              </div>
    </div>

</div>
            </div>
    

  </section>
  <section class="devsite-landing-row devsite-landing-row-1-up dac-dynamic-content-section"

           >


​      
​    
      <div class="devsite-landing-row-group">
              <div class="devsite-landing-row-item"
     
     >
    
      <div class="dac-subtitle dac-center">
  <h3>最新视频</h3>
</div> <devsite-dynamic-content
    query="origin:youtube+keyword:develop"
    initial-results="3"
    max-results="3"
    show-authors="true"
    sortorder="-timestamp">
</devsite-dynamic-content> <div class="dac-dynamic-content-more">
  <a class="button dac-button dac-alt-flat-button"
     href="https://www.youtube.com/user/androiddevelopers/search?query=%23develop">更多视频</a>
</div>


</div>
            </div>
    

  </section>

          </div>


​    
​    
          </article>
</article>




                      </devsite-content>
        </main>
        <devsite-footer-promos class="devsite-footer">
                      <nav class="devsite-footer-promos nocontent">
  <ul class="devsite-footer-promos-list">
        <li class="devsite-footer-promo">
      <a href="//developers.google.cn/china/#follow-google-developers-on-wechat"
         class="devsite-footer-promo-title gc-analytics-event"
         data-category="Site-Wide Custom Events"
                       data-modal-toggle="wechat"
                data-label="Footer WeChat Promo"
       >
                        <img class="devsite-footer-promo-icon"
             src="/_static/android/images/logo-wechat.png"
             alt="微信">
                微信
      </a>
      <div class="devsite-footer-promo-description">在微信上关注“Google Developers”</div>
    </li>
        <li class="devsite-footer-promo">
      <a href="//twitter.com/AndroidDev"
         class="devsite-footer-promo-title gc-analytics-event"
         data-category="Site-Wide Custom Events"
                       data-label="Footer Twitter Promo"
       >
                        <img class="devsite-footer-promo-icon"
             src="/_static/android/images/logo-twitter.svg"
             alt="Twitter">
                Twitter
      </a>
      <div class="devsite-footer-promo-description">在 Twitter 上关注 @AndroidDev</div>
    </li>
        <li class="devsite-footer-promo">
      <a href="//www.youtube.com/user/androiddevelopers"
         class="devsite-footer-promo-title gc-analytics-event"
         data-category="Site-Wide Custom Events"
                       data-label="Footer YouTube Promo"
       >
                        <img class="devsite-footer-promo-icon"
             src="//www.gstatic.com/images/icons/material/product/2x/youtube_48dp.png"
             alt="YouTube">
                YouTube
      </a>
      <div class="devsite-footer-promo-description">在 YouTube 上访问“Android Developers”频道</div>
    </li>
      </ul>
</nav>

                  </devsite-footer-promos>
        <devsite-footer-linkboxes class="devsite-footer">
                      <nav class="devsite-footer-linkboxes nocontent">
    <ul class="devsite-footer-linkboxes-list">
        <li class="devsite-footer-linkbox ">
    <h3 class="devsite-footer-linkbox-heading">关于 Android</h3>      <ul class="devsite-footer-linkbox-list">
                <li class="devsite-footer-linkbox-item">
          <a href="//www.android.com/"
             class="devsite-footer-linkbox-link
                    gc-analytics-event"
             data-category="Site-Wide Custom Events"
                        data-label="Footer Link (index 1)"           >
            Android
          </a>
        </li>
                <li class="devsite-footer-linkbox-item">
          <a href="//www.android.com/enterprise/"
             class="devsite-footer-linkbox-link
                    gc-analytics-event"
             data-category="Site-Wide Custom Events"
                        data-label="Footer Link (index 2)"           >
            Enterprise
          </a>
        </li>
                <li class="devsite-footer-linkbox-item">
          <a href="//www.android.com/security-center/"
             class="devsite-footer-linkbox-link
                    gc-analytics-event"
             data-category="Site-Wide Custom Events"
                        data-label="Footer Link (index 3)"           >
            安全
          </a>
        </li>
                <li class="devsite-footer-linkbox-item">
          <a href="//source.android.com/"
             class="devsite-footer-linkbox-link
                    gc-analytics-event"
             data-category="Site-Wide Custom Events"
                        data-label="Footer Link (index 4)"           >
            源代码
          </a>
        </li>
              </ul>
    </li>
        <li class="devsite-footer-linkbox ">
    <h3 class="devsite-footer-linkbox-heading">支持</h3>      <ul class="devsite-footer-linkbox-list">
                <li class="devsite-footer-linkbox-item">
          <a href="//issuetracker.google.com/issues/new?component=190923&amp;template=841312"
             class="devsite-footer-linkbox-link
                    gc-analytics-event"
             data-category="Site-Wide Custom Events"
                        data-label="Footer Link (index 1)"           >
            报告平台错误
          </a>
        </li>
                <li class="devsite-footer-linkbox-item">
          <a href="//issuetracker.google.com/issues/new?component=192697"
             class="devsite-footer-linkbox-link
                    gc-analytics-event"
             data-category="Site-Wide Custom Events"
                        data-label="Footer Link (index 2)"           >
            报告文档错误
          </a>
        </li>
                <li class="devsite-footer-linkbox-item">
          <a href="//support.google.com/googleplay/android-developer"
             class="devsite-footer-linkbox-link
                    gc-analytics-event"
             data-category="Site-Wide Custom Events"
                        data-label="Footer Link (index 3)"           >
            Google Play support
          </a>
        </li>
                <li class="devsite-footer-linkbox-item">
          <a href="https://google.qualtrics.com/jfe/form/SV_ewWXIoEVLBcyp7f??reserved=1&amp;utm_source=FooterLink&amp;Q_Language=en&amp;utm_medium=own_srch&amp;utm_campaign=developer.android.com&amp;utm_term=0&amp;utm_content=0&amp;productTag=reg&amp;campaignDate=may19&amp;pType=devel&amp;referral_code=gV420370"
             class="devsite-footer-linkbox-link
                    gc-analytics-event"
             data-category="Site-Wide Custom Events"
                        data-label="Footer Link (index 4)"           >
            参加调查研究
          </a>
        </li>
              </ul>
    </li>
        <li class="devsite-footer-linkbox ">
    <h3 class="devsite-footer-linkbox-heading">文档</h3>      <ul class="devsite-footer-linkbox-list">
                <li class="devsite-footer-linkbox-item">
          <a href="/guide"
             class="devsite-footer-linkbox-link
                    gc-analytics-event"
             data-category="Site-Wide Custom Events"
                        data-label="Footer Link (index 1)"           >
            开发者指南
          </a>
        </li>
                <li class="devsite-footer-linkbox-item">
          <a href="/design"
             class="devsite-footer-linkbox-link
                    gc-analytics-event"
             data-category="Site-Wide Custom Events"
                        data-label="Footer Link (index 2)"           >
            设计指南
          </a>
        </li>
                <li class="devsite-footer-linkbox-item">
          <a href="/reference"
             class="devsite-footer-linkbox-link
                    gc-analytics-event"
             data-category="Site-Wide Custom Events"
                        data-label="Footer Link (index 3)"           >
            API 参考
          </a>
        </li>
                <li class="devsite-footer-linkbox-item">
          <a href="/samples"
             class="devsite-footer-linkbox-link
                    gc-analytics-event"
             data-category="Site-Wide Custom Events"
                        data-label="Footer Link (index 4)"           >
            示例
          </a>
        </li>
                <li class="devsite-footer-linkbox-item">
          <a href="/studio/intro"
             class="devsite-footer-linkbox-link
                    gc-analytics-event"
             data-category="Site-Wide Custom Events"
                        data-label="Footer Link (index 5)"           >
            Android Studio
          </a>
        </li>
              </ul>
    </li>
      </ul>
  </nav>
                  </devsite-footer-linkboxes>
        <devsite-footer-utility class="devsite-footer">
                      
<div class="devsite-footer-utility nocontent">
    <nav class="devsite-footer-sites">
    <a href="https://developers.google.cn/"
       class="devsite-footer-sites-logo-link gc-analytics-event"
       data-category="Site-Wide Custom Events"
       data-label="Footer Google Developers Link">
      <img class="devsite-footer-sites-logo"
           src="/_static/images/lockup-developers.svg"
           alt="Google Developers">
    </a>
    <ul class="devsite-footer-sites-list">
            <li class="devsite-footer-sites-item">
        <a href="//developer.android.google.cn"
           class="devsite-footer-sites-link
                  gc-analytics-event"
           data-category="Site-Wide Custom Events"
                    data-label="Footer Android Link"
                  >
          Android
        </a>
      </li>
            <li class="devsite-footer-sites-item">
        <a href="//developer.chrome.com/home"
           class="devsite-footer-sites-link
                  gc-analytics-event"
           data-category="Site-Wide Custom Events"
                    data-label="Footer Chrome Link"
                  >
          Chrome
        </a>
      </li>
            <li class="devsite-footer-sites-item">
        <a href="//firebase.google.cn"
           class="devsite-footer-sites-link
                  gc-analytics-event"
           data-category="Site-Wide Custom Events"
                    data-label="Footer Firebase Link"
                  >
          Firebase
        </a>
      </li>
            <li class="devsite-footer-sites-item">
        <a href="//cloud.google.com"
           class="devsite-footer-sites-link
                  gc-analytics-event"
           data-category="Site-Wide Custom Events"
                    data-label="Footer Google Cloud Platform Link"
                  >
          Google Cloud Platform
        </a>
      </li>
            <li class="devsite-footer-sites-item">
        <a href="//developers.google.cn/products/"
           class="devsite-footer-sites-link
                  gc-analytics-event"
           data-category="Site-Wide Custom Events"
                    data-label="Footer All products Link"
                  >
          所有产品
        </a>
      </li>
          </ul>
  </nav>

  <nav class="devsite-footer-utility-links">
        <ul class="devsite-footer-utility-list">
            <li class="devsite-footer-utility-item
                 ">
                        <a class="devsite-footer-utility-link gc-analytics-event"
           href="//policies.google.cn/privacy"
           data-category="Site-Wide Custom Events"
           data-label="Footer Privacy link">
          隐私权政策
        </a>
              </li>
            <li class="devsite-footer-utility-item
                 ">
                        <a class="devsite-footer-utility-link gc-analytics-event"
           href="/license"
           data-category="Site-Wide Custom Events"
           data-label="Footer License link">
          许可
        </a>
              </li>
            <li class="devsite-footer-utility-item
                 ">
                        <a class="devsite-footer-utility-link gc-analytics-event"
           href="/distribute/marketing-tools/brand-guidelines"
           data-category="Site-Wide Custom Events"
           data-label="Footer Brand guidelines link">
          品牌指南
        </a>
              </li>
            <li class="devsite-footer-utility-item
                 devsite-footer-utility-button">
                <span class="devsite-footer-utility-description">通过电子邮件接收资讯和提示</span>
                        <a class="devsite-footer-utility-link gc-analytics-event"
           href="/newsletter/#subscribe"
           data-category="Site-Wide Custom Events"
           data-label="Footer Subscribe link">
          订阅
        </a>
              </li>
          </ul>

    <devsite-language-selector>
  <devsite-select class="devsite-language-selector-menu">
    <select class="devsite-language-selector-select"
            name="language"
            track-name="click"
            track-type="languageSelector">
              <option value="id"
              track-metadata-original-language="zh_cn"
              track-metadata-selected-language="id"
              track-name="changed"
              track-type="languageSelector"
            >
        Bahasa Indonesia
      </option>
          <option value="de"
              track-metadata-original-language="zh_cn"
              track-metadata-selected-language="de"
              track-name="changed"
              track-type="languageSelector"
            >
        Deutsch
      </option>
          <option value="en"
              track-metadata-original-language="zh_cn"
              track-metadata-selected-language="en"
              track-name="changed"
              track-type="languageSelector"
            >
        English
      </option>
          <option value="es"
              track-metadata-original-language="zh_cn"
              track-metadata-selected-language="es"
              track-name="changed"
              track-type="languageSelector"
            >
        Español
      </option>
          <option value="es_419"
              track-metadata-original-language="zh_cn"
              track-metadata-selected-language="es_419"
              track-name="changed"
              track-type="languageSelector"
            >
        Español – América Latina
      </option>
          <option value="fr"
              track-metadata-original-language="zh_cn"
              track-metadata-selected-language="fr"
              track-name="changed"
              track-type="languageSelector"
            >
        Français
      </option>
          <option value="pt_br"
              track-metadata-original-language="zh_cn"
              track-metadata-selected-language="pt_br"
              track-name="changed"
              track-type="languageSelector"
            >
        Português – Brasil
      </option>
          <option value="vi"
              track-metadata-original-language="zh_cn"
              track-metadata-selected-language="vi"
              track-name="changed"
              track-type="languageSelector"
            >
        Tiếng Việt
      </option>
          <option value="tr"
              track-metadata-original-language="zh_cn"
              track-metadata-selected-language="tr"
              track-name="changed"
              track-type="languageSelector"
            >
        Türkçe
      </option>
          <option value="ru"
              track-metadata-original-language="zh_cn"
              track-metadata-selected-language="ru"
              track-name="changed"
              track-type="languageSelector"
            >
        Русский
      </option>
          <option value="th"
              track-metadata-original-language="zh_cn"
              track-metadata-selected-language="th"
              track-name="changed"
              track-type="languageSelector"
            >
        ภาษาไทย
      </option>
          <option value="zh_cn"
              track-metadata-original-language="zh_cn"
              track-metadata-selected-language="zh_cn"
              track-name="changed"
              track-type="languageSelector"
                          selected="selected"
            >
        中文 – 简体
      </option>
          <option value="zh_tw"
              track-metadata-original-language="zh_cn"
              track-metadata-selected-language="zh_tw"
              track-name="changed"
              track-type="languageSelector"
            >
        中文 – 繁體
      </option>
          <option value="ja"
              track-metadata-original-language="zh_cn"
              track-metadata-selected-language="ja"
              track-name="changed"
              track-type="languageSelector"
            >
        日本語
      </option>
          <option value="ko"
              track-metadata-original-language="zh_cn"
              track-metadata-selected-language="ko"
              track-name="changed"
              track-type="languageSelector"
            >
        한국어
      </option>
        </select>
  </devsite-select>
</devsite-language-selector>

  </nav>
</div>
                  </devsite-footer-utility>
      </section></section>
    <devsite-sitemask></devsite-sitemask>
    <devsite-snackbar type="notification-survey"                                    notification-survey-link-txt="参加问卷调查"
                  notification-survey-link="https://developer.android.com/surveyQ12020"
                                    notification-survey-message="请完成一个问卷调查，帮助我们提升 Android 开发者体验。"
                  notification-survey-store-key
                   data-cookie-policy="//policies.google.cn/technologies/cookies"
                  >
</devsite-snackbar>
    <devsite-tooltip blocked-link></devsite-tooltip>
    <devsite-heading-link></devsite-heading-link>
    <devsite-analytics>
              <script type="application/json" analytics>[{"metrics": {"ratings_value": "metric1", "ratings_count": "metric2"}, "dimensions": {"dimension6": "zh-cn", "dimension4": "Android \u5f00\u53d1\u8005", "dimension5": "zh-cn", "dimension3": false, "dimension1": "Signed out"}, "gaid": "UA-5831155-3"}]</script>
<script type="application/json" gtm>{"parameters": {"freeTrialEligibleUser": "False", "language": {"requested": "zh-cn", "served": "zh-cn"}, "projectName": "Android \u5f00\u53d1\u8005", "scriptsafe": null, "signedIn": "False", "internalUser": "False"}, "tags": ["GTM-KMSWPCJ"]}</script>
          </devsite-analytics>
        <script>
    (function(d,e,v,s,i,t,E){d['GoogleDevelopersObject']=i;
    t=e.createElement(v);t.async=1;t.src=s;E=e.getElementsByTagName(v)[0];
    E.parentNode.insertBefore(t,E);})(window, document, 'script',
    'https://www.gstatic.cn/devrel-devsite/prod/ve2ae1395f351e38dc0b3037132204261d76b8f1c638764d7fd2c2fbb865782fc/js/app_loader.js', '[3,"zh_cn",null,"/js/devsite_app.js","https://www.gstatic.cn/devrel-devsite/prod/ve2ae1395f351e38dc0b3037132204261d76b8f1c638764d7fd2c2fbb865782fc","https://www.gstatic.cn/devrel-devsite/prod/ve2ae1395f351e38dc0b3037132204261d76b8f1c638764d7fd2c2fbb865782fc/android","https://android-dot-google-developers.gonglchuangl.net",1,null,["/_pwa/android/manifest.json","/_static/images/video-placeholder.svg","https://www.gstatic.cn/devrel-devsite/prod/ve2ae1395f351e38dc0b3037132204261d76b8f1c638764d7fd2c2fbb865782fc/android/images/favicon.png","https://www.gstatic.cn/devrel-devsite/prod/ve2ae1395f351e38dc0b3037132204261d76b8f1c638764d7fd2c2fbb865782fc/android/images/lockup.svg","https://fonts.googleapis.com/css?family=Roboto:300,400,400italic,500,500italic,700,700italic|Roboto+Mono:400,500,700|Material+Icons"],1]')
  </script>  </body>
</html>