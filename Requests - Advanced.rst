





<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
  <link rel="dns-prefetch" href="https://github.githubassets.com">
  <link rel="dns-prefetch" href="https://avatars0.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars1.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars2.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars3.githubusercontent.com">
  <link rel="dns-prefetch" href="https://github-cloud.s3.amazonaws.com">
  <link rel="dns-prefetch" href="https://user-images.githubusercontent.com/">



  <link crossorigin="anonymous" media="all" integrity="sha512-UDS3MR1FfvqHmqZAs2MWSDCWPwLemVRLqCwld4/zfwH0vhv7I6RYmDnMnNAVQKP1YYvqnccOCH4iOhFaUUyrjw==" rel="stylesheet" href="https://github.githubassets.com/assets/frameworks-2e9090135c22aad5f56c2f72dcba7880.css" />
  
    <link crossorigin="anonymous" media="all" integrity="sha512-yisqjZS/nUryyRTaYtZWHPVO6kcvp2jWYiim97SS5VNxGnGft/RtC47C32awJMutxKARTpyceonrM+JzuYvXug==" rel="stylesheet" href="https://github.githubassets.com/assets/github-7265230e39dc9980c60a5c0a9785286a.css" />
    
    
    
    

  <meta name="viewport" content="width=device-width">
  
  <title>requests-docs-cn/advanced.rst at master · requests/requests-docs-cn</title>
    <meta name="description" content="Chinese translation of Requests&#39; documentation. Contribute to requests/requests-docs-cn development by creating an account on GitHub.">
    <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
  <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
  <meta property="fb:app_id" content="1401488693436528">

    <meta name="twitter:image:src" content="https://avatars2.githubusercontent.com/u/2805331?s=400&amp;v=4" /><meta name="twitter:site" content="@github" /><meta name="twitter:card" content="summary" /><meta name="twitter:title" content="requests/requests-docs-cn" /><meta name="twitter:description" content="Chinese translation of Requests&#39; documentation. Contribute to requests/requests-docs-cn development by creating an account on GitHub." />
    <meta property="og:image" content="https://avatars2.githubusercontent.com/u/2805331?s=400&amp;v=4" /><meta property="og:site_name" content="GitHub" /><meta property="og:type" content="object" /><meta property="og:title" content="requests/requests-docs-cn" /><meta property="og:url" content="https://github.com/requests/requests-docs-cn" /><meta property="og:description" content="Chinese translation of Requests&#39; documentation. Contribute to requests/requests-docs-cn development by creating an account on GitHub." />

  <link rel="assets" href="https://github.githubassets.com/">
  <link rel="web-socket" href="wss://live.github.com/_sockets/VjI6NDMxNDE3Njg1OmZiZmQ4OTJlMWE5MDE5NzFhOGI2MjIzZWU0YjczZmJhOTc2OGNhYzZkZTczNjA1YThmZTY0NGU0Y2ZjMjUxZTc=--1fdf0d77457e8bf9b0b8fb186a5747461adb6680">
  <meta name="pjax-timeout" content="1000">
  <link rel="sudo-modal" href="/sessions/sudo_modal">
  <meta name="request-id" content="BC05:7BB4:AB475E:F5B953:5D5E69B2" data-pjax-transient>


  

  <meta name="selected-link" value="repo_source" data-pjax-transient>

      <meta name="google-site-verification" content="KT5gs8h0wvaagLKAVWq8bbeNwnZZK1r1XQysX3xurLU">
    <meta name="google-site-verification" content="ZzhVyEFwb7w3e0-uOTltm8Jsck2F5StVihD0exw2fsA">
    <meta name="google-site-verification" content="GXs5KoUUkNCoaAZn7wPN-t01Pywp9M3sEjnt_3_ZWPc">

  <meta name="octolytics-host" content="collector.githubapp.com" /><meta name="octolytics-app-id" content="github" /><meta name="octolytics-event-url" content="https://collector.githubapp.com/github-external/browser_event" /><meta name="octolytics-dimension-request_id" content="BC05:7BB4:AB475E:F5B953:5D5E69B2" /><meta name="octolytics-dimension-region_edge" content="ap-southeast-1" /><meta name="octolytics-dimension-region_render" content="iad" /><meta name="octolytics-dimension-ga_id" content="" class="js-octo-ga-id" /><meta name="octolytics-dimension-visitor_id" content="4487529527760973873" /><meta name="octolytics-actor-id" content="52539335" /><meta name="octolytics-actor-login" content="diskya" /><meta name="octolytics-actor-hash" content="f1dee13116218c1520fe186a204d230fce81e30c5d23c7028f9d107bf0d84fe3" />
<meta name="analytics-location" content="/&lt;user-name&gt;/&lt;repo-name&gt;/blob/show" data-pjax-transient="true" />



    <meta name="google-analytics" content="UA-3769691-2">

  <meta class="js-ga-set" name="userId" content="30fae021130ca43b6ebcbc4616bb5d5e">

<meta class="js-ga-set" name="dimension1" content="Logged In">



  

      <meta name="hostname" content="github.com">
    <meta name="user-login" content="diskya">

      <meta name="expected-hostname" content="github.com">
    <meta name="js-proxy-site-detection-payload" content="MGZiYThhODM3OTQ3ZDM5ZmQ5NTA4ZThmY2Y2NjViMDQ1MDQyMWJjODY2MTI0ZGI2NWQzMDY3MjMzZmY3MzQzZXx7InJlbW90ZV9hZGRyZXNzIjoiNTIuNzYuODcuNTQiLCJyZXF1ZXN0X2lkIjoiQkMwNTo3QkI0OkFCNDc1RTpGNUI5NTM6NUQ1RTY5QjIiLCJ0aW1lc3RhbXAiOjE1NjY0Njg1MzQsImhvc3QiOiJnaXRodWIuY29tIn0=">

    <meta name="enabled-features" content="ACTIONS_V2_ON_MARKETPLACE,MARKETPLACE_FEATURED_BLOG_POSTS,MARKETPLACE_INVOICED_BILLING,MARKETPLACE_SOCIAL_PROOF_CUSTOMERS,MARKETPLACE_TRENDING_SOCIAL_PROOF,MARKETPLACE_RECOMMENDATIONS,MARKETPLACE_PENDING_INSTALLATIONS,NOTIFY_ON_BLOCK,RELATED_ISSUES,GHE_CLOUD_TRIAL">

  <meta name="html-safe-nonce" content="1c13858d4e39c8968c8858d9a0551451e1f4cc19">

  <meta http-equiv="x-pjax-version" content="d9e76c4c13adffb60a475a702b588e42">
  

      <link href="https://github.com/requests/requests-docs-cn/commits/master.atom" rel="alternate" title="Recent Commits to requests-docs-cn:master" type="application/atom+xml">

  <meta name="go-import" content="github.com/requests/requests-docs-cn git https://github.com/requests/requests-docs-cn.git">

  <meta name="octolytics-dimension-user_id" content="2805331" /><meta name="octolytics-dimension-user_login" content="requests" /><meta name="octolytics-dimension-repository_id" content="8642896" /><meta name="octolytics-dimension-repository_nwo" content="requests/requests-docs-cn" /><meta name="octolytics-dimension-repository_public" content="true" /><meta name="octolytics-dimension-repository_is_fork" content="false" /><meta name="octolytics-dimension-repository_network_root_id" content="8642896" /><meta name="octolytics-dimension-repository_network_root_nwo" content="requests/requests-docs-cn" /><meta name="octolytics-dimension-repository_explore_github_marketplace_ci_cta_shown" content="false" />


    <link rel="canonical" href="https://github.com/requests/requests-docs-cn/blob/master/docs/user/advanced.rst" data-pjax-transient>


  <meta name="browser-stats-url" content="https://api.github.com/_private/browser/stats">

  <meta name="browser-errors-url" content="https://api.github.com/_private/browser/errors">

  <link rel="mask-icon" href="https://github.githubassets.com/pinned-octocat.svg" color="#000000">
  <link rel="icon" type="image/x-icon" class="js-site-favicon" href="https://github.githubassets.com/favicon.ico">

<meta name="theme-color" content="#1e2327">


  <meta name="u2f-enabled" content="true">

  <meta name="webauthn-auth-enabled" content="true">

  <meta name="webauthn-registration-enabled" content="true">

  <link rel="manifest" href="/manifest.json" crossOrigin="use-credentials">

  </head>

  <body class="logged-in env-production page-responsive page-blob">
    

  <div class="position-relative js-header-wrapper ">
    <a href="#start-of-content" tabindex="1" class="p-3 bg-blue text-white show-on-focus js-skip-to-content">Skip to content</a>
    <div id="js-pjax-loader-bar" class="pjax-loader-bar"><div class="progress"></div></div>

    
    
    


          <header class="Header js-details-container Details flex-wrap flex-lg-nowrap p-responsive" role="banner">

    <div class="Header-item d-none d-lg-flex">
      <a class="Header-link" href="https://github.com/" data-hotkey="g d" aria-label="Homepage" data-ga-click="Header, go to dashboard, icon:logo">
  <svg class="octicon octicon-mark-github v-align-middle" height="32" viewBox="0 0 16 16" version="1.1" width="32" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"/></svg>
</a>

    </div>

    <div class="Header-item d-lg-none">
      <button class="Header-link btn-link js-details-target" type="button" aria-label="Toggle navigation" aria-expanded="false">
        <svg height="24" class="octicon octicon-three-bars" viewBox="0 0 12 16" version="1.1" width="18" aria-hidden="true"><path fill-rule="evenodd" d="M11.41 9H.59C0 9 0 8.59 0 8c0-.59 0-1 .59-1H11.4c.59 0 .59.41.59 1 0 .59 0 1-.59 1h.01zm0-4H.59C0 5 0 4.59 0 4c0-.59 0-1 .59-1H11.4c.59 0 .59.41.59 1 0 .59 0 1-.59 1h.01zM.59 11H11.4c.59 0 .59.41.59 1 0 .59 0 1-.59 1H.59C0 13 0 12.59 0 12c0-.59 0-1 .59-1z"/></svg>
      </button>
    </div>

    <div class="Header-item Header-item--full flex-column flex-lg-row width-full flex-order-2 flex-lg-order-none mr-0 mr-lg-3 mt-3 mt-lg-0 Details-content--hidden">
        <div class="header-search flex-self-stretch flex-lg-self-auto mr-0 mr-lg-3 mb-3 mb-lg-0 scoped-search site-scoped-search js-site-search position-relative js-jump-to"
  role="combobox"
  aria-owns="jump-to-results"
  aria-label="Search or jump to"
  aria-haspopup="listbox"
  aria-expanded="false"
>
  <div class="position-relative">
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="js-site-search-form" role="search" aria-label="Site" data-scope-type="Repository" data-scope-id="8642896" data-scoped-search-url="/requests/requests-docs-cn/search" data-unscoped-search-url="/search" action="/requests/requests-docs-cn/search" accept-charset="UTF-8" method="get"><input name="utf8" type="hidden" value="&#x2713;" />
      <label class="form-control input-sm header-search-wrapper p-0 header-search-wrapper-jump-to position-relative d-flex flex-justify-between flex-items-center js-chromeless-input-container">
        <input type="text"
          class="form-control input-sm header-search-input jump-to-field js-jump-to-field js-site-search-focus js-site-search-field is-clearable"
          data-hotkey="s,/"
          name="q"
          value=""
          placeholder="Search or jump to…"
          data-unscoped-placeholder="Search or jump to…"
          data-scoped-placeholder="Search or jump to…"
          autocapitalize="off"
          aria-autocomplete="list"
          aria-controls="jump-to-results"
          aria-label="Search or jump to…"
          data-jump-to-suggestions-path="/_graphql/GetSuggestedNavigationDestinations#csrf-token=N6ub927lm63Q548QM3ZAqJc2n2FUnXVL88Vhxu2m4UeMukapKQz2p5+sPK0ZMs5kOgGqUiMVoG6qUtkn3GKhOw=="
          spellcheck="false"
          autocomplete="off"
          >
          <input type="hidden" class="js-site-search-type-field" name="type" >
            <img src="https://github.githubassets.com/images/search-key-slash.svg" alt="" class="mr-2 header-search-key-slash">

            <div class="Box position-absolute overflow-hidden d-none jump-to-suggestions js-jump-to-suggestions-container">
              
<ul class="d-none js-jump-to-suggestions-template-container">
  

<li class="d-flex flex-justify-start flex-items-center p-0 f5 navigation-item js-navigation-item js-jump-to-suggestion" role="option">
  <a tabindex="-1" class="no-underline d-flex flex-auto flex-items-center jump-to-suggestions-path js-jump-to-suggestion-path js-navigation-open p-2" href="">
    <div class="jump-to-octicon js-jump-to-octicon flex-shrink-0 mr-2 text-center d-none">
      <svg height="16" width="16" class="octicon octicon-repo flex-shrink-0 js-jump-to-octicon-repo d-none" title="Repository" aria-label="Repository" viewBox="0 0 12 16" version="1.1" role="img"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-project flex-shrink-0 js-jump-to-octicon-project d-none" title="Project" aria-label="Project" viewBox="0 0 15 16" version="1.1" role="img"><path fill-rule="evenodd" d="M10 12h3V2h-3v10zm-4-2h3V2H6v8zm-4 4h3V2H2v12zm-1 1h13V1H1v14zM14 0H1a1 1 0 0 0-1 1v14a1 1 0 0 0 1 1h13a1 1 0 0 0 1-1V1a1 1 0 0 0-1-1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-search flex-shrink-0 js-jump-to-octicon-search d-none" title="Search" aria-label="Search" viewBox="0 0 16 16" version="1.1" role="img"><path fill-rule="evenodd" d="M15.7 13.3l-3.81-3.83A5.93 5.93 0 0 0 13 6c0-3.31-2.69-6-6-6S1 2.69 1 6s2.69 6 6 6c1.3 0 2.48-.41 3.47-1.11l3.83 3.81c.19.2.45.3.7.3.25 0 .52-.09.7-.3a.996.996 0 0 0 0-1.41v.01zM7 10.7c-2.59 0-4.7-2.11-4.7-4.7 0-2.59 2.11-4.7 4.7-4.7 2.59 0 4.7 2.11 4.7 4.7 0 2.59-2.11 4.7-4.7 4.7z"/></svg>
    </div>

    <img class="avatar mr-2 flex-shrink-0 js-jump-to-suggestion-avatar d-none" alt="" aria-label="Team" src="" width="28" height="28">

    <div class="jump-to-suggestion-name js-jump-to-suggestion-name flex-auto overflow-hidden text-left no-wrap css-truncate css-truncate-target">
    </div>

    <div class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none js-jump-to-badge-search">
      <span class="js-jump-to-badge-search-text-default d-none" aria-label="in this repository">
        In this repository
      </span>
      <span class="js-jump-to-badge-search-text-global d-none" aria-label="in all of GitHub">
        All GitHub
      </span>
      <span aria-hidden="true" class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>

    <div aria-hidden="true" class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none d-on-nav-focus js-jump-to-badge-jump">
      Jump to
      <span class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>
  </a>
</li>

</ul>

<ul class="d-none js-jump-to-no-results-template-container">
  <li class="d-flex flex-justify-center flex-items-center f5 d-none js-jump-to-suggestion p-2">
    <span class="text-gray">No suggested jump to results</span>
  </li>
</ul>

<ul id="jump-to-results" role="listbox" class="p-0 m-0 js-navigation-container jump-to-suggestions-results-container js-jump-to-suggestions-results-container">
  

<li class="d-flex flex-justify-start flex-items-center p-0 f5 navigation-item js-navigation-item js-jump-to-scoped-search d-none" role="option">
  <a tabindex="-1" class="no-underline d-flex flex-auto flex-items-center jump-to-suggestions-path js-jump-to-suggestion-path js-navigation-open p-2" href="">
    <div class="jump-to-octicon js-jump-to-octicon flex-shrink-0 mr-2 text-center d-none">
      <svg height="16" width="16" class="octicon octicon-repo flex-shrink-0 js-jump-to-octicon-repo d-none" title="Repository" aria-label="Repository" viewBox="0 0 12 16" version="1.1" role="img"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-project flex-shrink-0 js-jump-to-octicon-project d-none" title="Project" aria-label="Project" viewBox="0 0 15 16" version="1.1" role="img"><path fill-rule="evenodd" d="M10 12h3V2h-3v10zm-4-2h3V2H6v8zm-4 4h3V2H2v12zm-1 1h13V1H1v14zM14 0H1a1 1 0 0 0-1 1v14a1 1 0 0 0 1 1h13a1 1 0 0 0 1-1V1a1 1 0 0 0-1-1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-search flex-shrink-0 js-jump-to-octicon-search d-none" title="Search" aria-label="Search" viewBox="0 0 16 16" version="1.1" role="img"><path fill-rule="evenodd" d="M15.7 13.3l-3.81-3.83A5.93 5.93 0 0 0 13 6c0-3.31-2.69-6-6-6S1 2.69 1 6s2.69 6 6 6c1.3 0 2.48-.41 3.47-1.11l3.83 3.81c.19.2.45.3.7.3.25 0 .52-.09.7-.3a.996.996 0 0 0 0-1.41v.01zM7 10.7c-2.59 0-4.7-2.11-4.7-4.7 0-2.59 2.11-4.7 4.7-4.7 2.59 0 4.7 2.11 4.7 4.7 0 2.59-2.11 4.7-4.7 4.7z"/></svg>
    </div>

    <img class="avatar mr-2 flex-shrink-0 js-jump-to-suggestion-avatar d-none" alt="" aria-label="Team" src="" width="28" height="28">

    <div class="jump-to-suggestion-name js-jump-to-suggestion-name flex-auto overflow-hidden text-left no-wrap css-truncate css-truncate-target">
    </div>

    <div class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none js-jump-to-badge-search">
      <span class="js-jump-to-badge-search-text-default d-none" aria-label="in this repository">
        In this repository
      </span>
      <span class="js-jump-to-badge-search-text-global d-none" aria-label="in all of GitHub">
        All GitHub
      </span>
      <span aria-hidden="true" class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>

    <div aria-hidden="true" class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none d-on-nav-focus js-jump-to-badge-jump">
      Jump to
      <span class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>
  </a>
</li>

  

<li class="d-flex flex-justify-start flex-items-center p-0 f5 navigation-item js-navigation-item js-jump-to-global-search d-none" role="option">
  <a tabindex="-1" class="no-underline d-flex flex-auto flex-items-center jump-to-suggestions-path js-jump-to-suggestion-path js-navigation-open p-2" href="">
    <div class="jump-to-octicon js-jump-to-octicon flex-shrink-0 mr-2 text-center d-none">
      <svg height="16" width="16" class="octicon octicon-repo flex-shrink-0 js-jump-to-octicon-repo d-none" title="Repository" aria-label="Repository" viewBox="0 0 12 16" version="1.1" role="img"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-project flex-shrink-0 js-jump-to-octicon-project d-none" title="Project" aria-label="Project" viewBox="0 0 15 16" version="1.1" role="img"><path fill-rule="evenodd" d="M10 12h3V2h-3v10zm-4-2h3V2H6v8zm-4 4h3V2H2v12zm-1 1h13V1H1v14zM14 0H1a1 1 0 0 0-1 1v14a1 1 0 0 0 1 1h13a1 1 0 0 0 1-1V1a1 1 0 0 0-1-1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-search flex-shrink-0 js-jump-to-octicon-search d-none" title="Search" aria-label="Search" viewBox="0 0 16 16" version="1.1" role="img"><path fill-rule="evenodd" d="M15.7 13.3l-3.81-3.83A5.93 5.93 0 0 0 13 6c0-3.31-2.69-6-6-6S1 2.69 1 6s2.69 6 6 6c1.3 0 2.48-.41 3.47-1.11l3.83 3.81c.19.2.45.3.7.3.25 0 .52-.09.7-.3a.996.996 0 0 0 0-1.41v.01zM7 10.7c-2.59 0-4.7-2.11-4.7-4.7 0-2.59 2.11-4.7 4.7-4.7 2.59 0 4.7 2.11 4.7 4.7 0 2.59-2.11 4.7-4.7 4.7z"/></svg>
    </div>

    <img class="avatar mr-2 flex-shrink-0 js-jump-to-suggestion-avatar d-none" alt="" aria-label="Team" src="" width="28" height="28">

    <div class="jump-to-suggestion-name js-jump-to-suggestion-name flex-auto overflow-hidden text-left no-wrap css-truncate css-truncate-target">
    </div>

    <div class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none js-jump-to-badge-search">
      <span class="js-jump-to-badge-search-text-default d-none" aria-label="in this repository">
        In this repository
      </span>
      <span class="js-jump-to-badge-search-text-global d-none" aria-label="in all of GitHub">
        All GitHub
      </span>
      <span aria-hidden="true" class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>

    <div aria-hidden="true" class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none d-on-nav-focus js-jump-to-badge-jump">
      Jump to
      <span class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>
  </a>
</li>


    <li class="d-flex flex-justify-center flex-items-center p-0 f5 js-jump-to-suggestion">
      <img src="https://github.githubassets.com/images/spinners/octocat-spinner-128.gif" alt="Octocat Spinner Icon" class="m-2" width="28">
    </li>
</ul>

            </div>
      </label>
</form>  </div>
</div>


      <nav class="d-flex flex-column flex-lg-row flex-self-stretch flex-lg-self-auto" aria-label="Global">
    <a class="Header-link d-block d-lg-none py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15" data-ga-click="Header, click, Nav menu - item:dashboard:user" aria-label="Dashboard" href="/dashboard">
      Dashboard
</a>
  <a class="js-selected-navigation-item Header-link  mr-0 mr-lg-3 py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15" data-hotkey="g p" data-ga-click="Header, click, Nav menu - item:pulls context:user" aria-label="Pull requests you created" data-selected-links="/pulls /pulls/assigned /pulls/mentioned /pulls" href="/pulls">
    Pull requests
</a>
  <a class="js-selected-navigation-item Header-link  mr-0 mr-lg-3 py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15" data-hotkey="g i" data-ga-click="Header, click, Nav menu - item:issues context:user" aria-label="Issues you created" data-selected-links="/issues /issues/assigned /issues/mentioned /issues" href="/issues">
    Issues
</a>
    <div class="mr-0 mr-lg-3 py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15">
      <a class="js-selected-navigation-item Header-link" data-ga-click="Header, click, Nav menu - item:marketplace context:user" data-octo-click="marketplace_click" data-octo-dimensions="location:nav_bar" data-selected-links=" /marketplace" href="/marketplace">
        Marketplace
</a>      

    </div>

  <a class="js-selected-navigation-item Header-link  mr-0 mr-lg-3 py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15" data-ga-click="Header, click, Nav menu - item:explore" data-selected-links="/explore /trending /trending/developers /integrations /integrations/feature/code /integrations/feature/collaborate /integrations/feature/ship showcases showcases_search showcases_landing /explore" href="/explore">
    Explore
</a>


    <a class="Header-link d-block d-lg-none mr-0 mr-lg-3 py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15" href="https://github.com/diskya">
      <img class="avatar" height="20" width="20" alt="@diskya" src="https://avatars0.githubusercontent.com/u/52539335?s=60&amp;v=4" />
      diskya
</a>
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form action="/logout" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="uRnqafLufdSyC600GKD/JFv8S26d33dh7dxfb11nhrnob2KT7aEimFhZZl2A35hfXR53wYlhiWxFlZ2VlUfgVg==" />
      <button type="submit" class="Header-link mr-0 mr-lg-3 py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15 d-lg-none btn-link d-block width-full text-left" data-ga-click="Header, sign out, icon:logout" style="padding-left: 2px;">
        <svg class="octicon octicon-sign-out v-align-middle" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 9V7H8V5h4V3l4 3-4 3zm-2 3H6V3L2 1h8v3h1V1c0-.55-.45-1-1-1H1C.45 0 0 .45 0 1v11.38c0 .39.22.73.55.91L6 16.01V13h4c.55 0 1-.45 1-1V8h-1v4z"/></svg>
        Sign out
      </button>
</form></nav>

    </div>

    <div class="Header-item Header-item--full flex-justify-center d-lg-none position-relative">
      <div class="css-truncate css-truncate-target width-fit position-absolute left-0 right-0 text-center">
              <svg class="octicon octicon-repo" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
    <a class="Header-link" href="/requests">requests</a>
    /
    <a class="Header-link" href="/requests/requests-docs-cn">requests-docs-cn</a>

</div>
    </div>

    <div class="Header-item position-relative d-none d-lg-flex">
      

    </div>

    <div class="Header-item mr-0 mr-lg-3 flex-order-1 flex-lg-order-none">
      

    <a aria-label="You have no unread notifications" class="Header-link notification-indicator position-relative tooltipped tooltipped-s js-socket-channel js-notification-indicator" data-hotkey="g n" data-ga-click="Header, go to notifications, icon:read" data-channel="notification-changed:52539335" href="/notifications">
        <span class="mail-status "></span>
        <svg class="octicon octicon-bell" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M14 12v1H0v-1l.73-.58c.77-.77.81-2.55 1.19-4.42C2.69 3.23 6 2 6 2c0-.55.45-1 1-1s1 .45 1 1c0 0 3.39 1.23 4.16 5 .38 1.88.42 3.66 1.19 4.42l.66.58H14zm-7 4c1.11 0 2-.89 2-2H5c0 1.11.89 2 2 2z"/></svg>
</a>
    </div>


    <div class="Header-item position-relative d-none d-lg-flex">
      <details class="details-overlay details-reset">
  <summary class="Header-link"
      aria-label="Create new…"
      data-ga-click="Header, create new, icon:add">
    <svg class="octicon octicon-plus" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 9H7v5H5V9H0V7h5V2h2v5h5v2z"/></svg> <span class="dropdown-caret"></span>
  </summary>
  <details-menu class="dropdown-menu dropdown-menu-sw">
    
<a role="menuitem" class="dropdown-item" href="/new" data-ga-click="Header, create new repository">
  New repository
</a>

  <a role="menuitem" class="dropdown-item" href="/new/import" data-ga-click="Header, import a repository">
    Import repository
  </a>

<a role="menuitem" class="dropdown-item" href="https://gist.github.com/" data-ga-click="Header, create new gist">
  New gist
</a>

  <a role="menuitem" class="dropdown-item" href="/organizations/new" data-ga-click="Header, create new organization">
    New organization
  </a>


  <div role="none" class="dropdown-divider"></div>
  <div class="dropdown-header">
    <span title="requests/requests-docs-cn">This repository</span>
  </div>
    <a role="menuitem" class="dropdown-item" href="/requests/requests-docs-cn/issues/new" data-ga-click="Header, create new issue" data-skip-pjax>
      New issue
    </a>


  </details-menu>
</details>

    </div>

    <div class="Header-item position-relative mr-0 d-none d-lg-flex">
      
<details class="details-overlay details-reset">
  <summary class="Header-link"
    aria-label="View profile and more"
    data-ga-click="Header, show menu, icon:avatar">
    <img alt="@diskya" class="avatar" src="https://avatars3.githubusercontent.com/u/52539335?s=40&amp;v=4" height="20" width="20">
    <span class="dropdown-caret"></span>
  </summary>
  <details-menu class="dropdown-menu dropdown-menu-sw mt-2" style="width: 180px">
    <div class="header-nav-current-user css-truncate"><a role="menuitem" class="no-underline user-profile-link px-3 pt-2 pb-2 mb-n2 mt-n1 d-block" href="/diskya" data-ga-click="Header, go to profile, text:Signed in as">Signed in as <strong class="css-truncate-target">diskya</strong></a></div>
    <div role="none" class="dropdown-divider"></div>

      <div class="pl-3 pr-3 f6 user-status-container js-user-status-context pb-1" data-url="/users/status?compact=1&amp;link_mentions=0&amp;truncate=1">
        
<div class="js-user-status-container
    user-status-compact rounded-1 px-2 py-1 mt-2
    border
  " data-team-hovercards-enabled>
  <details class="js-user-status-details details-reset details-overlay details-overlay-dark">
    <summary class="btn-link btn-block link-gray no-underline js-toggle-user-status-edit toggle-user-status-edit " aria-haspopup="dialog" role="menuitem" data-hydro-click="{&quot;event_type&quot;:&quot;user_profile.click&quot;,&quot;payload&quot;:{&quot;profile_user_id&quot;:2805331,&quot;target&quot;:&quot;EDIT_USER_STATUS&quot;,&quot;user_id&quot;:52539335,&quot;client_id&quot;:&quot;1044834388.1564799025&quot;,&quot;originating_request_id&quot;:&quot;BC05:7BB4:AB475E:F5B953:5D5E69B2&quot;,&quot;originating_url&quot;:&quot;https://github.com/requests/requests-docs-cn/blob/master/docs/user/advanced.rst&quot;,&quot;referrer&quot;:&quot;https://github.com/requests/requests-docs-cn/tree/master/docs/user&quot;}}" data-hydro-click-hmac="abe25723288ed16b329ed0fe14acb1e2ffd914a6daa298ade4b8c1a56c51a4a9">
      <div class="d-flex">
        <div class="f6 lh-condensed user-status-header
          d-inline-block v-align-middle
            user-status-emoji-only-header circle
            pr-2
"
            style="max-width: 29px"
          >
          <div class="user-status-emoji-container flex-shrink-0 mr-1 mt-1 lh-condensed-ultra v-align-bottom" style="">
            <svg class="octicon octicon-smiley" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8s3.58 8 8 8 8-3.58 8-8-3.58-8-8-8zm4.81 12.81a6.72 6.72 0 0 1-2.17 1.45c-.83.36-1.72.53-2.64.53-.92 0-1.81-.17-2.64-.53-.81-.34-1.55-.83-2.17-1.45a6.773 6.773 0 0 1-1.45-2.17A6.59 6.59 0 0 1 1.21 8c0-.92.17-1.81.53-2.64.34-.81.83-1.55 1.45-2.17.62-.62 1.36-1.11 2.17-1.45A6.59 6.59 0 0 1 8 1.21c.92 0 1.81.17 2.64.53.81.34 1.55.83 2.17 1.45.62.62 1.11 1.36 1.45 2.17.36.83.53 1.72.53 2.64 0 .92-.17 1.81-.53 2.64-.34.81-.83 1.55-1.45 2.17zM4 6.8v-.59c0-.66.53-1.19 1.2-1.19h.59c.66 0 1.19.53 1.19 1.19v.59c0 .67-.53 1.2-1.19 1.2H5.2C4.53 8 4 7.47 4 6.8zm5 0v-.59c0-.66.53-1.19 1.2-1.19h.59c.66 0 1.19.53 1.19 1.19v.59c0 .67-.53 1.2-1.19 1.2h-.59C9.53 8 9 7.47 9 6.8zm4 3.2c-.72 1.88-2.91 3-5 3s-4.28-1.13-5-3c-.14-.39.23-1 .66-1h8.59c.41 0 .89.61.75 1z"/></svg>
          </div>
        </div>
        <div class="
          d-inline-block v-align-middle
          
          
           css-truncate css-truncate-target 
           user-status-message-wrapper f6"
           style="line-height: 20px;" >
          <div class="d-inline-block text-gray-dark v-align-text-top text-left">
              <span class="text-gray ml-2">Set status</span>
          </div>
        </div>
      </div>
</summary>    <details-dialog class="details-dialog rounded-1 anim-fade-in fast Box Box--overlay" role="dialog" tabindex="-1">
      <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="position-relative flex-auto js-user-status-form" action="/users/status?compact=1&amp;link_mentions=0&amp;truncate=1" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="_method" value="put" /><input type="hidden" name="authenticity_token" value="kRd/OhtIlwfFRHJ4CTMjU0OMOSyh3EAVNeysY24MZbnPW4cSZjH0E7pSrsQJmhEhNBUOOUwzXsJNQfKTlWu5Mw==" />
        <div class="Box-header bg-gray border-bottom p-3">
          <button class="Box-btn-octicon js-toggle-user-status-edit btn-octicon float-right" type="reset" aria-label="Close dialog" data-close-dialog>
            <svg class="octicon octicon-x" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"/></svg>
          </button>
          <h3 class="Box-title f5 text-bold text-gray-dark">Edit status</h3>
        </div>
        <input type="hidden" name="emoji" class="js-user-status-emoji-field" value="">
        <input type="hidden" name="organization_id" class="js-user-status-org-id-field" value="">
        <div class="px-3 py-2 text-gray-dark">
          <div class="js-characters-remaining-container position-relative mt-2">
            <div class="input-group d-table form-group my-0 js-user-status-form-group">
              <span class="input-group-button d-table-cell v-align-middle" style="width: 1%">
                <button type="button" aria-label="Choose an emoji" class="btn-outline btn js-toggle-user-status-emoji-picker btn-open-emoji-picker p-0">
                  <span class="js-user-status-original-emoji" hidden></span>
                  <span class="js-user-status-custom-emoji"></span>
                  <span class="js-user-status-no-emoji-icon" >
                    <svg class="octicon octicon-smiley" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8s3.58 8 8 8 8-3.58 8-8-3.58-8-8-8zm4.81 12.81a6.72 6.72 0 0 1-2.17 1.45c-.83.36-1.72.53-2.64.53-.92 0-1.81-.17-2.64-.53-.81-.34-1.55-.83-2.17-1.45a6.773 6.773 0 0 1-1.45-2.17A6.59 6.59 0 0 1 1.21 8c0-.92.17-1.81.53-2.64.34-.81.83-1.55 1.45-2.17.62-.62 1.36-1.11 2.17-1.45A6.59 6.59 0 0 1 8 1.21c.92 0 1.81.17 2.64.53.81.34 1.55.83 2.17 1.45.62.62 1.11 1.36 1.45 2.17.36.83.53 1.72.53 2.64 0 .92-.17 1.81-.53 2.64-.34.81-.83 1.55-1.45 2.17zM4 6.8v-.59c0-.66.53-1.19 1.2-1.19h.59c.66 0 1.19.53 1.19 1.19v.59c0 .67-.53 1.2-1.19 1.2H5.2C4.53 8 4 7.47 4 6.8zm5 0v-.59c0-.66.53-1.19 1.2-1.19h.59c.66 0 1.19.53 1.19 1.19v.59c0 .67-.53 1.2-1.19 1.2h-.59C9.53 8 9 7.47 9 6.8zm4 3.2c-.72 1.88-2.91 3-5 3s-4.28-1.13-5-3c-.14-.39.23-1 .66-1h8.59c.41 0 .89.61.75 1z"/></svg>
                  </span>
                </button>
              </span>
              <text-expander keys=": @" data-mention-url="/autocomplete/user-suggestions" data-emoji-url="/autocomplete/emoji">
                <input
                  type="text"
                  autocomplete="off"
                  data-no-org-url="/autocomplete/user-suggestions"
                  data-org-url="/suggestions?mention_suggester=1"
                  data-maxlength="80"
                  class="d-table-cell width-full form-control js-user-status-message-field js-characters-remaining-field"
                  placeholder="What's happening?"
                  name="message"
                  value=""
                  aria-label="What is your current status?">
              </text-expander>
              <div class="error">Could not update your status, please try again.</div>
            </div>
            <div style="margin-left: 53px" class="my-1 text-small label-characters-remaining js-characters-remaining" data-suffix="remaining" hidden>
              80 remaining
            </div>
          </div>
          <include-fragment class="js-user-status-emoji-picker" data-url="/users/status/emoji"></include-fragment>
          <div class="overflow-auto ml-n3 mr-n3 px-3 border-bottom" style="max-height: 33vh">
            <div class="user-status-suggestions js-user-status-suggestions collapsed overflow-hidden">
              <h4 class="f6 text-normal my-3">Suggestions:</h4>
              <div class="mx-3 mt-2 clearfix">
                  <div class="float-left col-6">
                      <button type="button" value=":palm_tree:" class="d-flex flex-items-baseline flex-items-stretch lh-condensed f6 btn-link link-gray no-underline js-predefined-user-status mb-1">
                        <div class="emoji-status-width mr-2 v-align-middle js-predefined-user-status-emoji">
                          <g-emoji alias="palm_tree" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f334.png">🌴</g-emoji>
                        </div>
                        <div class="d-flex flex-items-center no-underline js-predefined-user-status-message ws-normal text-left" style="border-left: 1px solid transparent">
                          On vacation
                        </div>
                      </button>
                      <button type="button" value=":face_with_thermometer:" class="d-flex flex-items-baseline flex-items-stretch lh-condensed f6 btn-link link-gray no-underline js-predefined-user-status mb-1">
                        <div class="emoji-status-width mr-2 v-align-middle js-predefined-user-status-emoji">
                          <g-emoji alias="face_with_thermometer" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f912.png">🤒</g-emoji>
                        </div>
                        <div class="d-flex flex-items-center no-underline js-predefined-user-status-message ws-normal text-left" style="border-left: 1px solid transparent">
                          Out sick
                        </div>
                      </button>
                  </div>
                  <div class="float-left col-6">
                      <button type="button" value=":house:" class="d-flex flex-items-baseline flex-items-stretch lh-condensed f6 btn-link link-gray no-underline js-predefined-user-status mb-1">
                        <div class="emoji-status-width mr-2 v-align-middle js-predefined-user-status-emoji">
                          <g-emoji alias="house" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f3e0.png">🏠</g-emoji>
                        </div>
                        <div class="d-flex flex-items-center no-underline js-predefined-user-status-message ws-normal text-left" style="border-left: 1px solid transparent">
                          Working from home
                        </div>
                      </button>
                      <button type="button" value=":dart:" class="d-flex flex-items-baseline flex-items-stretch lh-condensed f6 btn-link link-gray no-underline js-predefined-user-status mb-1">
                        <div class="emoji-status-width mr-2 v-align-middle js-predefined-user-status-emoji">
                          <g-emoji alias="dart" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f3af.png">🎯</g-emoji>
                        </div>
                        <div class="d-flex flex-items-center no-underline js-predefined-user-status-message ws-normal text-left" style="border-left: 1px solid transparent">
                          Focusing
                        </div>
                      </button>
                  </div>
              </div>
            </div>
            <div class="user-status-limited-availability-container">
              <div class="form-checkbox my-0">
                <input type="checkbox" name="limited_availability" value="1" class="js-user-status-limited-availability-checkbox" data-default-message="I may be slow to respond." aria-describedby="limited-availability-help-text-truncate-true-compact-true" id="limited-availability-truncate-true-compact-true">
                <label class="d-block f5 text-gray-dark mb-1" for="limited-availability-truncate-true-compact-true">
                  Busy
                </label>
                <p class="note" id="limited-availability-help-text-truncate-true-compact-true">
                  When others mention you, assign you, or request your review,
                  GitHub will let them know that you have limited availability.
                </p>
              </div>
            </div>
          </div>
            

<div class="d-inline-block f5 mr-2 pt-3 pb-2" >
  <div class="d-inline-block mr-1">
    Clear status
  </div>

  <details class="js-user-status-expire-drop-down f6 dropdown details-reset details-overlay d-inline-block mr-2">
    <summary class="f5 btn-link link-gray-dark border px-2 py-1 rounded-1" aria-haspopup="true">
      <div class="js-user-status-expiration-interval-selected d-inline-block v-align-baseline">
        Never
      </div>
      <div class="dropdown-caret"></div>
    </summary>

    <ul class="dropdown-menu dropdown-menu-se pl-0 overflow-auto" style="width: 220px; max-height: 15.5em">
      <li>
        <button type="button" class="btn-link dropdown-item js-user-status-expire-button ws-normal" title="Never">
          <span class="d-inline-block text-bold mb-1">Never</span>
          <div class="f6 lh-condensed">Keep this status until you clear your status or edit your status.</div>
        </button>
      </li>
      <li class="dropdown-divider" role="none"></li>
        <li>
          <button type="button" class="btn-link dropdown-item ws-normal js-user-status-expire-button" title="in 30 minutes" value="2019-08-22T18:38:54+08:00">
            in 30 minutes
          </button>
        </li>
        <li>
          <button type="button" class="btn-link dropdown-item ws-normal js-user-status-expire-button" title="in 1 hour" value="2019-08-22T19:08:54+08:00">
            in 1 hour
          </button>
        </li>
        <li>
          <button type="button" class="btn-link dropdown-item ws-normal js-user-status-expire-button" title="in 4 hours" value="2019-08-22T22:08:54+08:00">
            in 4 hours
          </button>
        </li>
        <li>
          <button type="button" class="btn-link dropdown-item ws-normal js-user-status-expire-button" title="today" value="2019-08-22T23:59:59+08:00">
            today
          </button>
        </li>
        <li>
          <button type="button" class="btn-link dropdown-item ws-normal js-user-status-expire-button" title="this week" value="2019-08-25T23:59:59+08:00">
            this week
          </button>
        </li>
    </ul>
  </details>
  <input class="js-user-status-expiration-date-input" type="hidden" name="expires_at" value="">
</div>

          <include-fragment class="js-user-status-org-picker" data-url="/users/status/organizations"></include-fragment>
        </div>
        <div class="d-flex flex-items-center flex-justify-between p-3 border-top">
          <button type="submit" disabled class="width-full btn btn-primary mr-2 js-user-status-submit">
            Set status
          </button>
          <button type="button" disabled class="width-full js-clear-user-status-button btn ml-2 ">
            Clear status
          </button>
        </div>
</form>    </details-dialog>
  </details>
</div>

      </div>
      <div role="none" class="dropdown-divider"></div>


    <a role="menuitem" class="dropdown-item" href="/diskya" data-ga-click="Header, go to profile, text:your profile">Your profile</a>



    <a role="menuitem" class="dropdown-item" href="/diskya?tab=repositories" data-ga-click="Header, go to repositories, text:your repositories">Your repositories</a>

    <a role="menuitem" class="dropdown-item" href="/diskya?tab=projects" data-ga-click="Header, go to projects, text:your projects">Your projects</a>

    <a role="menuitem" class="dropdown-item" href="/diskya?tab=stars" data-ga-click="Header, go to starred repos, text:your stars">Your stars</a>
      <a role="menuitem" class="dropdown-item" href="https://gist.github.com/mine" data-ga-click="Header, your gists, text:your gists">Your gists</a>


    <div role="none" class="dropdown-divider"></div>
    <a role="menuitem" class="dropdown-item" href="https://help.github.com" data-ga-click="Header, go to help, text:help">Help</a>
    <a role="menuitem" class="dropdown-item" href="/settings/profile" data-ga-click="Header, go to settings, icon:settings">Settings</a>
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="logout-form" action="/logout" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="cUY2zC3gzuePwfEC6SFhdVyj27ecgFnZm1etfTU9g+wgML42Mq+Rq2WTOmtxXgYOWkHnGIg+p9QzHm+H/R3lAw==" />
      
      <button type="submit" class="dropdown-item dropdown-signout" data-ga-click="Header, sign out, icon:logout" role="menuitem">
        Sign out
      </button>
</form>  </details-menu>
</details>

    </div>

  </header>

      

  </div>

  <div id="start-of-content" class="show-on-focus"></div>


    <div id="js-flash-container">

</div>



  <div class="application-main " data-commit-hovercards-enabled>
        <div itemscope itemtype="http://schema.org/SoftwareSourceCode" class="">
    <main  >
      


  



  








  <div class="pagehead repohead instapaper_ignore readability-menu experiment-repo-nav pt-0 pt-lg-4 ">
    <div class="repohead-details-container clearfix container-lg p-responsive d-none d-lg-block">

      <ul class="pagehead-actions">




  <li>
    
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form data-remote="true" class="clearfix js-social-form js-social-container" action="/notifications/subscribe" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="ZrFKbPTHQrBrnff6EhtegHNyOjRjRWv9KHyzZuBOcqNEh+IW+R/SLGuI50AYbJB9yhf8Qd9UvlUlfheiBG5mpg==" />      <input type="hidden" name="repository_id" value="8642896">

      <details class="details-reset details-overlay select-menu float-left">
        <summary class="select-menu-button float-left btn btn-sm btn-with-count" data-hydro-click="{&quot;event_type&quot;:&quot;repository.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;WATCH_BUTTON&quot;,&quot;repository_id&quot;:8642896,&quot;client_id&quot;:&quot;1044834388.1564799025&quot;,&quot;originating_request_id&quot;:&quot;BC05:7BB4:AB475E:F5B953:5D5E69B2&quot;,&quot;originating_url&quot;:&quot;https://github.com/requests/requests-docs-cn/blob/master/docs/user/advanced.rst&quot;,&quot;referrer&quot;:&quot;https://github.com/requests/requests-docs-cn/tree/master/docs/user&quot;,&quot;user_id&quot;:52539335}}" data-hydro-click-hmac="427f73981c5769dd0446e85c4533ca53f7d766381df507345b3ec062babaf93c" data-ga-click="Repository, click Watch settings, action:blob#show">          <span data-menu-button>
              <svg class="octicon octicon-eye v-align-text-bottom" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
              Watch
          </span>
</summary>        <details-menu
          class="select-menu-modal position-absolute mt-5"
          style="z-index: 99;">
          <div class="select-menu-header">
            <span class="select-menu-title">Notifications</span>
          </div>
          <div class="select-menu-list">
            <button type="submit" name="do" value="included" class="select-menu-item width-full" aria-checked="true" role="menuitemradio">
              <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z"/></svg>
              <div class="select-menu-item-text">
                <span class="select-menu-item-heading">Not watching</span>
                <span class="description">Be notified only when participating or @mentioned.</span>
                <span class="hidden-select-button-text" data-menu-button-contents>
                  <svg class="octicon octicon-eye v-align-text-bottom" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
                  Watch
                </span>
              </div>
            </button>

            <button type="submit" name="do" value="release_only" class="select-menu-item width-full" aria-checked="false" role="menuitemradio">
              <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z"/></svg>
              <div class="select-menu-item-text">
                <span class="select-menu-item-heading">Releases only</span>
                <span class="description">Be notified of new releases, and when participating or @mentioned.</span>
                <span class="hidden-select-button-text" data-menu-button-contents>
                  <svg class="octicon octicon-eye v-align-text-bottom" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
                  Unwatch releases
                </span>
              </div>
            </button>

            <button type="submit" name="do" value="subscribed" class="select-menu-item width-full" aria-checked="false" role="menuitemradio">
              <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z"/></svg>
              <div class="select-menu-item-text">
                <span class="select-menu-item-heading">Watching</span>
                <span class="description">Be notified of all conversations.</span>
                <span class="hidden-select-button-text" data-menu-button-contents>
                  <svg class="octicon octicon-eye v-align-text-bottom" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
                  Unwatch
                </span>
              </div>
            </button>

            <button type="submit" name="do" value="ignore" class="select-menu-item width-full" aria-checked="false" role="menuitemradio">
              <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z"/></svg>
              <div class="select-menu-item-text">
                <span class="select-menu-item-heading">Ignoring</span>
                <span class="description">Never be notified.</span>
                <span class="hidden-select-button-text" data-menu-button-contents>
                  <svg class="octicon octicon-mute v-align-text-bottom" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8 2.81v10.38c0 .67-.81 1-1.28.53L3 10H1c-.55 0-1-.45-1-1V7c0-.55.45-1 1-1h2l3.72-3.72C7.19 1.81 8 2.14 8 2.81zm7.53 3.22l-1.06-1.06-1.97 1.97-1.97-1.97-1.06 1.06L11.44 8 9.47 9.97l1.06 1.06 1.97-1.97 1.97 1.97 1.06-1.06L13.56 8l1.97-1.97z"/></svg>
                  Stop ignoring
                </span>
              </div>
            </button>
          </div>
        </details-menu>
      </details>
        <a class="social-count js-social-count"
          href="/requests/requests-docs-cn/watchers"
          aria-label="16 users are watching this repository">
          16
        </a>
</form>
  </li>

  <li>
      <div class="js-toggler-container js-social-container starring-container ">
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="starred js-social-form" action="/requests/requests-docs-cn/unstar" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="wlzshjVVvV9HyDeRuMbzkI3FFDpInw8kTyYOTo7C6mn/mJtR2HVbpybjuOTPe6tBgFqBE/1vPraAiAQhF/e1wA==" />
      <input type="hidden" name="context" value="repository"></input>
      <button type="submit" class="btn btn-sm btn-with-count js-toggler-target" aria-label="Unstar this repository" title="Unstar requests/requests-docs-cn" data-hydro-click="{&quot;event_type&quot;:&quot;repository.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;UNSTAR_BUTTON&quot;,&quot;repository_id&quot;:8642896,&quot;client_id&quot;:&quot;1044834388.1564799025&quot;,&quot;originating_request_id&quot;:&quot;BC05:7BB4:AB475E:F5B953:5D5E69B2&quot;,&quot;originating_url&quot;:&quot;https://github.com/requests/requests-docs-cn/blob/master/docs/user/advanced.rst&quot;,&quot;referrer&quot;:&quot;https://github.com/requests/requests-docs-cn/tree/master/docs/user&quot;,&quot;user_id&quot;:52539335}}" data-hydro-click-hmac="9ccf7c4e92be958db0324fa7cbdb51aaa2510a8b849aea625d679649b6340638" data-ga-click="Repository, click unstar button, action:blob#show; text:Unstar">        <svg class="octicon octicon-star v-align-text-bottom" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M14 6l-4.9-.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14 7 11.67 11.33 14l-.93-4.74L14 6z"/></svg>
        Unstar
</button>        <a class="social-count js-social-count" href="/requests/requests-docs-cn/stargazers"
           aria-label="57 users starred this repository">
           57
        </a>
</form>
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="unstarred js-social-form" action="/requests/requests-docs-cn/star" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="P09xefDe7pILpnAROX8iDwPNcHaTsN27iXuW7Mr0SO4HvmgI/a+/Cxkvgq+njbRl8fnB7WT4iS/gfQBV3Hh8+Q==" />
      <input type="hidden" name="context" value="repository"></input>
      <button type="submit" class="btn btn-sm btn-with-count js-toggler-target" aria-label="Unstar this repository" title="Star requests/requests-docs-cn" data-hydro-click="{&quot;event_type&quot;:&quot;repository.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;STAR_BUTTON&quot;,&quot;repository_id&quot;:8642896,&quot;client_id&quot;:&quot;1044834388.1564799025&quot;,&quot;originating_request_id&quot;:&quot;BC05:7BB4:AB475E:F5B953:5D5E69B2&quot;,&quot;originating_url&quot;:&quot;https://github.com/requests/requests-docs-cn/blob/master/docs/user/advanced.rst&quot;,&quot;referrer&quot;:&quot;https://github.com/requests/requests-docs-cn/tree/master/docs/user&quot;,&quot;user_id&quot;:52539335}}" data-hydro-click-hmac="68f05680a07ca928fbb31c1a695422cea6dc134003dbfa93944dd7487db95162" data-ga-click="Repository, click star button, action:blob#show; text:Star">        <svg class="octicon octicon-star v-align-text-bottom" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M14 6l-4.9-.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14 7 11.67 11.33 14l-.93-4.74L14 6z"/></svg>
        Star
</button>        <a class="social-count js-social-count" href="/requests/requests-docs-cn/stargazers"
           aria-label="57 users starred this repository">
          57
        </a>
</form>  </div>

  </li>

  <li>
          <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="btn-with-count" action="/requests/requests-docs-cn/fork" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="wCNbmHob6sbGUupTfZ5ifnHE8u13izYNRviFbfAXgwGiMbUD7QTuQ99e2tp7iCXJGQF87VXNk/LVVXpY5ubrgA==" />
            <button class="btn btn-sm btn-with-count" data-hydro-click="{&quot;event_type&quot;:&quot;repository.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;FORK_BUTTON&quot;,&quot;repository_id&quot;:8642896,&quot;client_id&quot;:&quot;1044834388.1564799025&quot;,&quot;originating_request_id&quot;:&quot;BC05:7BB4:AB475E:F5B953:5D5E69B2&quot;,&quot;originating_url&quot;:&quot;https://github.com/requests/requests-docs-cn/blob/master/docs/user/advanced.rst&quot;,&quot;referrer&quot;:&quot;https://github.com/requests/requests-docs-cn/tree/master/docs/user&quot;,&quot;user_id&quot;:52539335}}" data-hydro-click-hmac="ffb3fce20de86f1c129029a5941f4efbe199588a3b71781300ee85c65824673c" data-ga-click="Repository, show fork modal, action:blob#show; text:Fork" type="submit" title="Fork your own copy of requests/requests-docs-cn to your account" aria-label="Fork your own copy of requests/requests-docs-cn to your account">              <svg class="octicon octicon-repo-forked v-align-text-bottom" viewBox="0 0 10 16" version="1.1" width="10" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8 1a1.993 1.993 0 0 0-1 3.72V6L5 8 3 6V4.72A1.993 1.993 0 0 0 2 1a1.993 1.993 0 0 0-1 3.72V6.5l3 3v1.78A1.993 1.993 0 0 0 5 15a1.993 1.993 0 0 0 1-3.72V9.5l3-3V4.72A1.993 1.993 0 0 0 8 1zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3 10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3-10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
              Fork
</button></form>
    <a href="/requests/requests-docs-cn/network/members" class="social-count"
       aria-label="35 users forked this repository">
      35
    </a>
  </li>
</ul>

      <h1 class="public ">
    <svg class="octicon octicon-repo" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
  <span class="author" itemprop="author"><a class="url fn" rel="author" data-hovercard-type="organization" data-hovercard-url="/orgs/requests/hovercard" href="/requests">requests</a></span><!--
--><span class="path-divider">/</span><!--
--><strong itemprop="name"><a data-pjax="#js-repo-pjax-container" href="/requests/requests-docs-cn">requests-docs-cn</a></strong>
  

</h1>

    </div>
    
<nav class="hx_reponav reponav js-repo-nav js-sidenav-container-pjax container-lg p-responsive d-none d-lg-block"
     itemscope
     itemtype="http://schema.org/BreadcrumbList"
    aria-label="Repository"
     data-pjax="#js-repo-pjax-container">

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a class="js-selected-navigation-item selected reponav-item" itemprop="url" data-hotkey="g c" aria-current="page" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches repo_packages /requests/requests-docs-cn" href="/requests/requests-docs-cn">
      <svg class="octicon octicon-code" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M9.5 3L8 4.5 11.5 8 8 11.5 9.5 13 14 8 9.5 3zm-5 0L0 8l4.5 5L6 11.5 2.5 8 6 4.5 4.5 3z"/></svg>
      <span itemprop="name">Code</span>
      <meta itemprop="position" content="1">
</a>  </span>

    <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
      <a itemprop="url" data-hotkey="g i" class="js-selected-navigation-item reponav-item" data-selected-links="repo_issues repo_labels repo_milestones /requests/requests-docs-cn/issues" href="/requests/requests-docs-cn/issues">
        <svg class="octicon octicon-issue-opened" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7 2.3c3.14 0 5.7 2.56 5.7 5.7s-2.56 5.7-5.7 5.7A5.71 5.71 0 0 1 1.3 8c0-3.14 2.56-5.7 5.7-5.7zM7 1C3.14 1 0 4.14 0 8s3.14 7 7 7 7-3.14 7-7-3.14-7-7-7zm1 3H6v5h2V4zm0 6H6v2h2v-2z"/></svg>
        <span itemprop="name">Issues</span>
        <span class="Counter">0</span>
        <meta itemprop="position" content="2">
</a>    </span>

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a data-hotkey="g p" itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="repo_pulls checks /requests/requests-docs-cn/pulls" href="/requests/requests-docs-cn/pulls">
      <svg class="octicon octicon-git-pull-request" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M11 11.28V5c-.03-.78-.34-1.47-.94-2.06C9.46 2.35 8.78 2.03 8 2H7V0L4 3l3 3V4h1c.27.02.48.11.69.31.21.2.3.42.31.69v6.28A1.993 1.993 0 0 0 10 15a1.993 1.993 0 0 0 1-3.72zm-1 2.92c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zM4 3c0-1.11-.89-2-2-2a1.993 1.993 0 0 0-1 3.72v6.56A1.993 1.993 0 0 0 2 15a1.993 1.993 0 0 0 1-3.72V4.72c.59-.34 1-.98 1-1.72zm-.8 10c0 .66-.55 1.2-1.2 1.2-.65 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
      <span itemprop="name">Pull requests</span>
      <span class="Counter">0</span>
      <meta itemprop="position" content="3">
</a>  </span>


    <a data-hotkey="g b" class="js-selected-navigation-item reponav-item" data-selected-links="repo_projects new_repo_project repo_project /requests/requests-docs-cn/projects" href="/requests/requests-docs-cn/projects">
      <svg class="octicon octicon-project" viewBox="0 0 15 16" version="1.1" width="15" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M10 12h3V2h-3v10zm-4-2h3V2H6v8zm-4 4h3V2H2v12zm-1 1h13V1H1v14zM14 0H1a1 1 0 0 0-1 1v14a1 1 0 0 0 1 1h13a1 1 0 0 0 1-1V1a1 1 0 0 0-1-1z"/></svg>
      Projects
      <span class="Counter" >0</span>
</a>

    <a class="js-selected-navigation-item reponav-item" data-hotkey="g w" data-selected-links="repo_wiki /requests/requests-docs-cn/wiki" href="/requests/requests-docs-cn/wiki">
      <svg class="octicon octicon-book" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M3 5h4v1H3V5zm0 3h4V7H3v1zm0 2h4V9H3v1zm11-5h-4v1h4V5zm0 2h-4v1h4V7zm0 2h-4v1h4V9zm2-6v9c0 .55-.45 1-1 1H9.5l-1 1-1-1H2c-.55 0-1-.45-1-1V3c0-.55.45-1 1-1h5.5l1 1 1-1H15c.55 0 1 .45 1 1zm-8 .5L7.5 3H2v9h6V3.5zm7-.5H9.5l-.5.5V12h6V3z"/></svg>
      Wiki
</a>
    <a data-skip-pjax="true" class="js-selected-navigation-item reponav-item" data-selected-links="security alerts policy /requests/requests-docs-cn/security/advisories" href="/requests/requests-docs-cn/security/advisories">
      <svg class="octicon octicon-shield" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M0 2l7-2 7 2v6.02C14 12.69 8.69 16 7 16c-1.69 0-7-3.31-7-7.98V2zm1 .75L7 1l6 1.75v5.268C13 12.104 8.449 15 7 15c-1.449 0-6-2.896-6-6.982V2.75zm1 .75L7 2v12c-1.207 0-5-2.482-5-5.985V3.5z"/></svg>
      Security
</a>
    <a class="js-selected-navigation-item reponav-item" data-selected-links="repo_graphs repo_contributors dependency_graph pulse people /requests/requests-docs-cn/pulse" href="/requests/requests-docs-cn/pulse">
      <svg class="octicon octicon-graph" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M16 14v1H0V0h1v14h15zM5 13H3V8h2v5zm4 0H7V3h2v10zm4 0h-2V6h2v7z"/></svg>
      Insights
</a>

</nav>

  <div class="reponav-wrapper reponav-small d-lg-none">
  <nav class="reponav js-reponav text-center no-wrap"
       itemscope
       itemtype="http://schema.org/BreadcrumbList">

    <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
      <a class="js-selected-navigation-item selected reponav-item" itemprop="url" aria-current="page" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches repo_packages /requests/requests-docs-cn" href="/requests/requests-docs-cn">
        <span itemprop="name">Code</span>
        <meta itemprop="position" content="1">
</a>    </span>

      <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
        <a itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="repo_issues repo_labels repo_milestones /requests/requests-docs-cn/issues" href="/requests/requests-docs-cn/issues">
          <span itemprop="name">Issues</span>
          <span class="Counter">0</span>
          <meta itemprop="position" content="2">
</a>      </span>

    <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
      <a itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="repo_pulls checks /requests/requests-docs-cn/pulls" href="/requests/requests-docs-cn/pulls">
        <span itemprop="name">Pull requests</span>
        <span class="Counter">0</span>
        <meta itemprop="position" content="3">
</a>    </span>

      <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
        <a itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="repo_projects new_repo_project repo_project /requests/requests-docs-cn/projects" href="/requests/requests-docs-cn/projects">
          <span itemprop="name">Projects</span>
          <span class="Counter">0</span>
          <meta itemprop="position" content="4">
</a>      </span>

      <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
        <a itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="repo_wiki /requests/requests-docs-cn/wiki" href="/requests/requests-docs-cn/wiki">
          <span itemprop="name">Wiki</span>
          <meta itemprop="position" content="5">
</a>      </span>

      <a itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="security alerts policy /requests/requests-docs-cn/security/advisories" href="/requests/requests-docs-cn/security/advisories">
        <span itemprop="name">Security</span>
        <meta itemprop="position" content="6">
</a>
      <a class="js-selected-navigation-item reponav-item" data-selected-links="pulse /requests/requests-docs-cn/pulse" href="/requests/requests-docs-cn/pulse">
        Pulse
</a>
      <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
        <a itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="community /requests/requests-docs-cn/community" href="/requests/requests-docs-cn/community">
          Community
</a>      </span>

  </nav>
</div>


  </div>
<div class="container-lg clearfix new-discussion-timeline experiment-repo-nav  p-responsive">
  <div class="repository-content ">

    
    


  


    <a class="d-none js-permalink-shortcut" data-hotkey="y" href="/requests/requests-docs-cn/blob/6175fad9210928652c59d4ea0673c9ed1e969773/docs/user/advanced.rst">Permalink</a>

    <!-- blob contrib key: blob_contributors:v21:7ead8a7340e3ecae4beb695d19d5a93a -->
      

    <div class="d-flex flex-items-start flex-shrink-0 pb-3 flex-column flex-md-row">
      <span class="d-flex flex-justify-between width-full width-md-auto">
        
<details class="details-reset details-overlay select-menu branch-select-menu  hx_rsm" id="branch-select-menu">
  <summary class="btn btn-sm select-menu-button css-truncate"
           data-hotkey="w"
           title="Switch branches or tags">
    <i>Branch:</i>
    <span class="css-truncate-target" data-menu-button>master</span>
  </summary>

  <details-menu class="select-menu-modal hx_rsm-modal position-absolute" style="z-index: 99;" src="/requests/requests-docs-cn/ref-list/master/docs/user/advanced.rst?source_action=show&amp;source_controller=blob" preload>
    <include-fragment class="select-menu-loading-overlay anim-pulse">
      <svg height="32" class="octicon octicon-octoface" viewBox="0 0 16 16" version="1.1" width="32" aria-hidden="true"><path fill-rule="evenodd" d="M14.7 5.34c.13-.32.55-1.59-.13-3.31 0 0-1.05-.33-3.44 1.3-1-.28-2.07-.32-3.13-.32s-2.13.04-3.13.32c-2.39-1.64-3.44-1.3-3.44-1.3-.68 1.72-.26 2.99-.13 3.31C.49 6.21 0 7.33 0 8.69 0 13.84 3.33 15 7.98 15S16 13.84 16 8.69c0-1.36-.49-2.48-1.3-3.35zM8 14.02c-3.3 0-5.98-.15-5.98-3.35 0-.76.38-1.48 1.02-2.07 1.07-.98 2.9-.46 4.96-.46 2.07 0 3.88-.52 4.96.46.65.59 1.02 1.3 1.02 2.07 0 3.19-2.68 3.35-5.98 3.35zM5.49 9.01c-.66 0-1.2.8-1.2 1.78s.54 1.79 1.2 1.79c.66 0 1.2-.8 1.2-1.79s-.54-1.78-1.2-1.78zm5.02 0c-.66 0-1.2.79-1.2 1.78s.54 1.79 1.2 1.79c.66 0 1.2-.8 1.2-1.79s-.53-1.78-1.2-1.78z"/></svg>
    </include-fragment>
  </details-menu>
</details>

        <div class="BtnGroup flex-shrink-0 d-md-none">
          <a href="/requests/requests-docs-cn/find/master"
                class="js-pjax-capture-input btn btn-sm BtnGroup-item"
                data-pjax
                data-hotkey="t">
            Find file
          </a>
          <clipboard-copy value="docs/user/advanced.rst" class="btn btn-sm BtnGroup-item">
            Copy path
          </clipboard-copy>
        </div>
      </span>
      <h2 id="blob-path" class="breadcrumb flex-auto min-width-0 text-normal flex-md-self-center ml-md-2 mr-md-3 my-2 my-md-0">
        <span class="js-repo-root text-bold"><span class="js-path-segment"><a data-pjax="true" href="/requests/requests-docs-cn"><span>requests-docs-cn</span></a></span></span><span class="separator">/</span><span class="js-path-segment"><a data-pjax="true" href="/requests/requests-docs-cn/tree/master/docs"><span>docs</span></a></span><span class="separator">/</span><span class="js-path-segment"><a data-pjax="true" href="/requests/requests-docs-cn/tree/master/docs/user"><span>user</span></a></span><span class="separator">/</span><strong class="final-path">advanced.rst</strong>
      </h2>

      <div class="BtnGroup flex-shrink-0 d-none d-md-inline-block">
        <a href="/requests/requests-docs-cn/find/master"
              class="js-pjax-capture-input btn btn-sm BtnGroup-item"
              data-pjax
              data-hotkey="t">
          Find file
        </a>
        <clipboard-copy value="docs/user/advanced.rst" class="btn btn-sm BtnGroup-item">
          Copy path
        </clipboard-copy>
      </div>
    </div>



    
  <div class="Box Box--condensed d-flex flex-column flex-shrink-0">
      <div class="Box-body d-flex flex-justify-between bg-blue-light flex-column flex-md-row flex-items-start flex-md-items-center">
        <span class="pr-md-4 f6">
          <img class="avatar" width="20" height="20" alt="" src="https://camo.githubusercontent.com/4af5359b2f795dccecdc7e23c32d8ffcce89828b/68747470733a2f2f302e67726176617461722e636f6d2f6176617461722f39613065636139653063393965313366666333626530393434363135653237643f643d68747470732533412532462532466769746875622e6769746875626173736574732e636f6d253246696d6167657325324667726176617461727325324667726176617461722d757365722d3432302e706e6726723d6726733d313430" data-canonical-src="https://0.gravatar.com/avatar/9a0eca9e0c99e13ffc3be0944615e27d?d=https%3A%2F%2Fgithub.githubassets.com%2Fimages%2Fgravatars%2Fgravatar-user-420.png&amp;r=g&amp;s=140" />
          <span class="text-bold link-gray-dark lh-default v-align-middle">pokerhy</span>
            <span class="lh-default v-align-middle">
              <a data-pjax="true" title="edit line 295 ’相应‘ --&gt; ’响应‘" class="link-gray" href="/requests/requests-docs-cn/commit/311f7d813cc66bba07a370780afe888890d2ca41">edit line 295 ’相应‘ --&gt; ’响应‘</a>
            </span>
        </span>
        <span class="d-inline-block flex-shrink-0 v-align-bottom f6 mt-2 mt-md-0">
          <a class="pr-2 text-mono link-gray" href="/requests/requests-docs-cn/commit/311f7d813cc66bba07a370780afe888890d2ca41" data-pjax>311f7d8</a>
          <relative-time datetime="2018-08-07T00:25:06Z">Aug 7, 2018</relative-time>
        </span>
      </div>

    <div class="Box-body d-flex flex-items-center flex-auto f6 border-bottom-0 flex-wrap" >
      <details class="details-reset details-overlay details-overlay-dark lh-default text-gray-dark float-left mr-2" id="blob_contributors_box">
        <summary class="btn-link" aria-haspopup="dialog">
          <span><strong>35</strong> contributors</span>
        </summary>
        <details-dialog
          class="Box Box--overlay d-flex flex-column anim-fade-in fast"
          aria-label="Users who have contributed to this file"
          src="/requests/requests-docs-cn/contributors/master/docs/user/advanced.rst/list" preload>
          <div class="Box-header">
            <button class="Box-btn-octicon btn-octicon float-right" type="button" aria-label="Close dialog" data-close-dialog>
              <svg class="octicon octicon-x" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"/></svg>
            </button>
            <h3 class="Box-title">
              Users who have contributed to this file
            </h3>
          </div>
          <include-fragment class="octocat-spinner my-3" aria-label="Loading..."></include-fragment>
        </details-dialog>
      </details>
        <span class="">
    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=31764" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/requests/requests-docs-cn/commits/master/docs/user/advanced.rst?author=gastlygem">
      <img class="avatar mr-1" src="https://avatars1.githubusercontent.com/u/31764?s=40&amp;v=4" width="20" height="20" alt="@gastlygem" /> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=1382556" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/requests/requests-docs-cn/commits/master/docs/user/advanced.rst?author=Lukasa">
      <img class="avatar mr-1" src="https://avatars0.githubusercontent.com/u/1382556?s=40&amp;v=4" width="20" height="20" alt="@Lukasa" /> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=1164112" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/requests/requests-docs-cn/commits/master/docs/user/advanced.rst?author=mikeholler">
      <img class="avatar mr-1" src="https://avatars3.githubusercontent.com/u/1164112?s=40&amp;v=4" width="20" height="20" alt="@mikeholler" /> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=834231" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/requests/requests-docs-cn/commits/master/docs/user/advanced.rst?author=youngsterxyf">
      <img class="avatar mr-1" src="https://avatars1.githubusercontent.com/u/834231?s=40&amp;v=4" width="20" height="20" alt="@youngsterxyf" /> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=2456854" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/requests/requests-docs-cn/commits/master/docs/user/advanced.rst?author=mapleray">
      <img class="avatar mr-1" src="https://avatars2.githubusercontent.com/u/2456854?s=40&amp;v=4" width="20" height="20" alt="@mapleray" /> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=413772" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/requests/requests-docs-cn/commits/master/docs/user/advanced.rst?author=graingert">
      <img class="avatar mr-1" src="https://avatars1.githubusercontent.com/u/413772?s=40&amp;v=4" width="20" height="20" alt="@graingert" /> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=1618875" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/requests/requests-docs-cn/commits/master/docs/user/advanced.rst?author=muhtasib">
      <img class="avatar mr-1" src="https://avatars1.githubusercontent.com/u/1618875?s=40&amp;v=4" width="20" height="20" alt="@muhtasib" /> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=503584" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/requests/requests-docs-cn/commits/master/docs/user/advanced.rst?author=joequery">
      <img class="avatar mr-1" src="https://avatars1.githubusercontent.com/u/503584?s=40&amp;v=4" width="20" height="20" alt="@joequery" /> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=863286" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/requests/requests-docs-cn/commits/master/docs/user/advanced.rst?author=dalanmiller">
      <img class="avatar mr-1" src="https://avatars1.githubusercontent.com/u/863286?s=40&amp;v=4" width="20" height="20" alt="@dalanmiller" /> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=22761" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/requests/requests-docs-cn/commits/master/docs/user/advanced.rst?author=passos">
      <img class="avatar mr-1" src="https://avatars1.githubusercontent.com/u/22761?s=40&amp;v=4" width="20" height="20" alt="@passos" /> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=313932" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/requests/requests-docs-cn/commits/master/docs/user/advanced.rst?author=tomhogans">
      <img class="avatar mr-1" src="https://avatars3.githubusercontent.com/u/313932?s=40&amp;v=4" width="20" height="20" alt="@tomhogans" /> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=717901" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/requests/requests-docs-cn/commits/master/docs/user/advanced.rst?author=t-8ch">
      <img class="avatar mr-1" src="https://avatars0.githubusercontent.com/u/717901?s=40&amp;v=4" width="20" height="20" alt="@t-8ch" /> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=120119" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/requests/requests-docs-cn/commits/master/docs/user/advanced.rst?author=sharat87">
      <img class="avatar mr-1" src="https://avatars3.githubusercontent.com/u/120119?s=40&amp;v=4" width="20" height="20" alt="@sharat87" /> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=6292" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/requests/requests-docs-cn/commits/master/docs/user/advanced.rst?author=shazow">
      <img class="avatar mr-1" src="https://avatars2.githubusercontent.com/u/6292?s=40&amp;v=4" width="20" height="20" alt="@shazow" /> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=20295772" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/requests/requests-docs-cn/commits/master/docs/user/advanced.rst?author=CarGod">
      <img class="avatar mr-1" src="https://avatars1.githubusercontent.com/u/20295772?s=40&amp;v=4" width="20" height="20" alt="@CarGod" /> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=912849" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/requests/requests-docs-cn/commits/master/docs/user/advanced.rst?author=LucianU">
      <img class="avatar mr-1" src="https://avatars3.githubusercontent.com/u/912849?s=40&amp;v=4" width="20" height="20" alt="@LucianU" /> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=9675939" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/requests/requests-docs-cn/commits/master/docs/user/advanced.rst?author=laixintao">
      <img class="avatar mr-1" src="https://avatars1.githubusercontent.com/u/9675939?s=40&amp;v=4" width="20" height="20" alt="@laixintao" /> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=830800" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/requests/requests-docs-cn/commits/master/docs/user/advanced.rst?author=johtso">
      <img class="avatar mr-1" src="https://avatars1.githubusercontent.com/u/830800?s=40&amp;v=4" width="20" height="20" alt="@johtso" /> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=195266" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/requests/requests-docs-cn/commits/master/docs/user/advanced.rst?author=jgorset">
      <img class="avatar mr-1" src="https://avatars3.githubusercontent.com/u/195266?s=40&amp;v=4" width="20" height="20" alt="@jgorset" /> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=18160" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/requests/requests-docs-cn/commits/master/docs/user/advanced.rst?author=jemerick">
      <img class="avatar mr-1" src="https://avatars2.githubusercontent.com/u/18160?s=40&amp;v=4" width="20" height="20" alt="@jemerick" /> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=22723" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/requests/requests-docs-cn/commits/master/docs/user/advanced.rst?author=idan">
      <img class="avatar mr-1" src="https://avatars2.githubusercontent.com/u/22723?s=40&amp;v=4" width="20" height="20" alt="@idan" /> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=325146" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/requests/requests-docs-cn/commits/master/docs/user/advanced.rst?author=gareth-lloyd">
      <img class="avatar mr-1" src="https://avatars2.githubusercontent.com/u/325146?s=40&amp;v=4" width="20" height="20" alt="@gareth-lloyd" /> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=1141204" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/requests/requests-docs-cn/commits/master/docs/user/advanced.rst?author=ekatsah">
      <img class="avatar mr-1" src="https://avatars2.githubusercontent.com/u/1141204?s=40&amp;v=4" width="20" height="20" alt="@ekatsah" /> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=162275" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/requests/requests-docs-cn/commits/master/docs/user/advanced.rst?author=dasevilla">
      <img class="avatar mr-1" src="https://avatars2.githubusercontent.com/u/162275?s=40&amp;v=4" width="20" height="20" alt="@dasevilla" /> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=1476" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/requests/requests-docs-cn/commits/master/docs/user/advanced.rst?author=thedaniel">
      <img class="avatar mr-1" src="https://avatars2.githubusercontent.com/u/1476?s=40&amp;v=4" width="20" height="20" alt="@thedaniel" /> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=30053" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/requests/requests-docs-cn/commits/master/docs/user/advanced.rst?author=cwvh">
      <img class="avatar mr-1" src="https://avatars3.githubusercontent.com/u/30053?s=40&amp;v=4" width="20" height="20" alt="@cwvh" /> 
</a>
    <button type="button" class="btn-link lh-default" data-toggle-for="blob_contributors_box">and others</button>
</span>

    </div>
  </div>





    <div class="Box mt-3 position-relative">
      
<div class="Box-header py-2 d-flex flex-column flex-shrink-0 flex-md-row flex-md-items-center">

  <div class="text-mono f6 flex-auto pr-3 flex-order-2 flex-md-order-1 mt-2 mt-md-0">
      961 lines (620 sloc)
      <span class="file-info-divider"></span>
    33.8 KB
  </div>

  <div class="d-flex py-1 py-md-0 flex-auto flex-order-1 flex-md-order-2 flex-sm-grow-0 flex-justify-between">

    <div class="BtnGroup">
      <a id="raw-url" class="btn btn-sm BtnGroup-item" href="/requests/requests-docs-cn/raw/master/docs/user/advanced.rst">Raw</a>
        <a class="btn btn-sm js-update-url-with-hash BtnGroup-item" data-hotkey="b" href="/requests/requests-docs-cn/blame/master/docs/user/advanced.rst">Blame</a>
      <a rel="nofollow" class="btn btn-sm BtnGroup-item" href="/requests/requests-docs-cn/commits/master/docs/user/advanced.rst">History</a>
    </div>


    <div>
            <a class="btn-octicon tooltipped tooltipped-nw hide-sm"
               href="https://desktop.github.com"
               aria-label="Open this file in GitHub Desktop"
               data-ga-click="Repository, open with desktop, type:windows">
                <svg class="octicon octicon-device-desktop" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M15 2H1c-.55 0-1 .45-1 1v9c0 .55.45 1 1 1h5.34c-.25.61-.86 1.39-2.34 2h8c-1.48-.61-2.09-1.39-2.34-2H15c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm0 9H1V3h14v8z"/></svg>
            </a>

            <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="inline-form js-update-url-with-hash" action="/requests/requests-docs-cn/edit/master/docs/user/advanced.rst" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="fZ7BrWlWqEDRLVZIwF5OQIut/99SFymTAWQEVuO+HVXj7AORQJXoAm/rt4TBkhPZ5VLN5M0qb59YDeZ0U8qcCw==" />
              <button class="btn-octicon tooltipped tooltipped-nw" type="submit"
                aria-label="Fork this project and edit the file" data-hotkey="e" data-disable-with>
                <svg class="octicon octicon-pencil" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M0 12v3h3l8-8-3-3-8 8zm3 2H1v-2h1v1h1v1zm10.3-9.3L12 6 9 3l1.3-1.3a.996.996 0 0 1 1.41 0l1.59 1.59c.39.39.39 1.02 0 1.41z"/></svg>
              </button>
</form>
          <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="inline-form" action="/requests/requests-docs-cn/delete/master/docs/user/advanced.rst" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="3uJbQTqhrQ9kIiusZryAMVNx+TKbBXC8n+jzdOFffqANFpGmNxZyv3vbH4xAzuMDrowI1xllzthQqbhkj8wYCw==" />
            <button class="btn-octicon btn-octicon-danger tooltipped tooltipped-nw" type="submit"
              aria-label="Fork this project and delete the file" data-disable-with>
              <svg class="octicon octicon-trashcan" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M11 2H9c0-.55-.45-1-1-1H5c-.55 0-1 .45-1 1H2c-.55 0-1 .45-1 1v1c0 .55.45 1 1 1v9c0 .55.45 1 1 1h7c.55 0 1-.45 1-1V5c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm-1 12H3V5h1v8h1V5h1v8h1V5h1v8h1V5h1v9zm1-10H2V3h9v1z"/></svg>
            </button>
</form>    </div>
  </div>
</div>




      
  <div id="readme" class="Box-body readme blob instapaper_body js-code-block-container">
    <article class="markdown-body entry-content p-3 p-md-6" itemprop="text"><h1><a id="user-content-高级用法" class="anchor" aria-hidden="true" href="#高级用法"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>高级用法</h1>
<p>本篇文档涵盖了 Requests 的一些高级特性。</p>
<a name="user-content-id2"></a>
<h2><a id="user-content-会话对象" class="anchor" aria-hidden="true" href="#会话对象"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>会话对象</h2>
<p>会话对象让你能够跨请求保持某些参数。它也会在同一个 Session 实例发出的所有请求之间保持 cookie，
期间使用 <code>urllib3</code> 的 <a href="http://urllib3.readthedocs.io/en/latest/reference/index.html#module-urllib3.connectionpool" rel="nofollow">connection pooling</a> 功能。所以如果你向同一主机发送多个请求，底层的 TCP 连接将会被重用，从而带来显著的性能提升。 (参见 <a href="https://en.wikipedia.org/wiki/HTTP_persistent_connection" rel="nofollow">HTTP persistent connection</a>).</p>
<p>会话对象具有主要的 Requests API 的所有方法。</p>
<p>我们来跨请求保持一些 cookie:</p>
<pre>s = requests.Session()

s.get('http://httpbin.org/cookies/set/sessioncookie/123456789')
r = s.get("http://httpbin.org/cookies")

print(r.text)
# '{"cookies": {"sessioncookie": "123456789"}}'
</pre>
<p>会话也可用来为请求方法提供缺省数据。这是通过为会话对象的属性提供数据来实现的：</p>
<pre>s = requests.Session()
s.auth = ('user', 'pass')
s.headers.update({'x-test': 'true'})

# both 'x-test' and 'x-test2' are sent
s.get('http://httpbin.org/headers', headers={'x-test2': 'true'})
</pre>
<p>任何你传递给请求方法的字典都会与已设置会话层数据合并。方法层的参数覆盖会话的参数。</p>
<p>不过需要注意，就算使用了会话，方法级别的参数也不会被跨请求保持。下面的例子只会和第一个请求发送 cookie
，而非第二个：</p>
<pre>s = requests.Session()

r = s.get('http://httpbin.org/cookies', cookies={'from-my': 'browser'})
print(r.text)
# '{"cookies": {"from-my": "browser"}}'

r = s.get('http://httpbin.org/cookies')
print(r.text)
# '{"cookies": {}}'
</pre>
<p>如果你要手动为会话添加 cookie，就使用 <a href="#id3"><span id="user-content-id4">:ref:`Cookie utility 函数 &lt;api-cookies&gt;`</span></a> 来操纵
<a href="#id5"><span id="user-content-id6">:attr:`Session.cookies &lt;requests.Session.cookies&gt;`</span></a>。</p>
<p>会话还可以用作前后文管理器：</p>
<pre>with requests.Session() as s:
    s.get('http://httpbin.org/cookies/set/sessioncookie/123456789')
</pre>
<p>这样就能确保 <code>with</code> 区块退出后会话能被关闭，即使发生了异常也一样。</p>
<div>
<p>从字典参数中移除一个值</p>
<p>有时你会想省略字典参数中一些会话层的键。要做到这一点，你只需简单地在方法层参数中将那个键的值设置为 <code>None</code> ，那个键就会被自动省略掉。</p>
</div>
<p>包含在一个会话中的所有数据你都可以直接使用。学习更多细节请阅读 <a href="#id7"><span id="user-content-id8">:ref:`会话 API 文档 &lt;sessionapi&gt;`</span></a>。</p>
<a name="user-content-id9"></a>
<h2><a id="user-content-请求与响应对象" class="anchor" aria-hidden="true" href="#请求与响应对象"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>请求与响应对象</h2>
<p>任何时候进行了类似 requests.get() 的调用，你都在做两件主要的事情。其一，你在构建一个 Request 对象，
该对象将被发送到某个服务器请求或查询一些资源。其二，一旦 <code>requests</code> 得到一个从服务器返回的响应就会产生一个 <code>Response</code> 对象。该响应对象包含服务器返回的所有信息，也包含你原来创建的 <code>Request</code> 对象。如下是一个简单的请求，从 Wikipedia 的服务器得到一些非常重要的信息：</p>
<pre>&gt;&gt;&gt; r = requests.get('http://en.wikipedia.org/wiki/Monty_Python')
</pre>
<p>如果想访问服务器返回给我们的响应头部信息，可以这样做：</p>
<pre>&gt;&gt;&gt; r.headers
{'content-length': '56170', 'x-content-type-options': 'nosniff', 'x-cache':
'HIT from cp1006.eqiad.wmnet, MISS from cp1010.eqiad.wmnet', 'content-encoding':
'gzip', 'age': '3080', 'content-language': 'en', 'vary': 'Accept-Encoding,Cookie',
'server': 'Apache', 'last-modified': 'Wed, 13 Jun 2012 01:33:50 GMT',
'connection': 'close', 'cache-control': 'private, s-maxage=0, max-age=0,
must-revalidate', 'date': 'Thu, 14 Jun 2012 12:59:39 GMT', 'content-type':
'text/html; charset=UTF-8', 'x-cache-lookup': 'HIT from cp1006.eqiad.wmnet:3128,
MISS from cp1010.eqiad.wmnet:80'}
</pre>
<p>然而，如果想得到发送到服务器的请求的头部，我们可以简单地访问该请求，然后是该请求的头部：</p>
<pre>&gt;&gt;&gt; r.request.headers
{'Accept-Encoding': 'identity, deflate, compress, gzip',
'Accept': '*/*', 'User-Agent': 'python-requests/0.13.1'}
</pre>
<a name="user-content-prepared-request"></a>
<h2><a id="user-content-准备的请求-prepared-request" class="anchor" aria-hidden="true" href="#准备的请求-prepared-request"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>准备的请求 （Prepared Request）</h2>
<p>当你从 API 或者会话调用中收到一个 <a href="#id10"><span id="user-content-id11">:class:`Response &lt;requests.Response&gt;`</span></a>
对象时，<code>request</code> 属性其实是使用了 <code>PreparedRequest</code>。有时在发送请求之前，你需要对
body 或者 header （或者别的什么东西）做一些额外处理，下面演示了一个简单的做法：</p>
<pre>from requests import Request, Session

s = Session()
req = Request('GET', url,
    data=data,
    headers=header
)
prepped = req.prepare()

# do something with prepped.body
# do something with prepped.headers

resp = s.send(prepped,
    stream=stream,
    verify=verify,
    proxies=proxies,
    cert=cert,
    timeout=timeout
)

print(resp.status_code)
</pre>
<p>由于你没有对 <code>Request</code> 对象做什么特殊事情，你立即准备和修改了 <code>PreparedRequest</code>
对象，然后把它和别的参数一起发送到 <code>requests.*</code> 或者 <code>Session.*</code>。</p>
<p>然而，上述代码会失去 Requests <a href="#id12"><span id="user-content-id13">:class:`Session &lt;requests.Session&gt;`</span></a> 对象的一些优势，
尤其 <a href="#id14"><span id="user-content-id15">:class:`Session &lt;requests.Session&gt;`</span></a> 级别的状态，例如 cookie 就不会被应用到你的请求上去。要获取一个带有状态的 <a href="#id16"><span id="user-content-id17">:class:`PreparedRequest &lt;requests.PreparedRequest&gt;`</span></a>，
请用 <a href="#id18"><span id="user-content-id19">:meth:`Session.prepare_request() &lt;requests.Session.prepare_request&gt;`</span></a> 取代
<a href="#id20"><span id="user-content-id21">:meth:`Request.prepare() &lt;requests.Request.prepare&gt;`</span></a> 的调用，如下所示：</p>
<pre>from requests import Request, Session

s = Session()
req = Request('GET',  url,
    data=data
    headers=headers
)

prepped = s.prepare_request(req)

# do something with prepped.body
# do something with prepped.headers

resp = s.send(prepped,
    stream=stream,
    verify=verify,
    proxies=proxies,
    cert=cert,
    timeout=timeout
)

print(resp.status_code)
</pre>
<a name="user-content-ssl"></a>
<h2><a id="user-content-ssl-证书验证" class="anchor" aria-hidden="true" href="#ssl-证书验证"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>SSL 证书验证</h2>
<p>Requests 可以为 HTTPS 请求验证 SSL 证书，就像 web 浏览器一样。SSL 验证默认是开启的，如果证书验证失败，Requests 会抛出 SSLError:</p>
<pre>&gt;&gt;&gt; requests.get('https://requestb.in')
requests.exceptions.SSLError: hostname 'requestb.in' doesn't match either of '*.herokuapp.com', 'herokuapp.com'
</pre>
<p>在该域名上我没有设置 SSL，所以失败了。但 Github 设置了 SSL:</p>
<pre>&gt;&gt;&gt; requests.get('https://github.com', verify=True)
&lt;Response [200]&gt;
</pre>
<p>你可以为 <code>verify</code> 传入 CA_BUNDLE 文件的路径，或者包含可信任 CA 证书文件的文件夹路径：</p>
<pre>&gt;&gt;&gt; requests.get('https://github.com', verify='/path/to/certfile')
</pre>
<p>或者将其保持在会话中：</p>
<pre>s = requests.Session()
s.verify = '/path/to/certfile'
</pre>
<div>
<p>Note</p>
<p>如果 <code>verify</code> 设为文件夹路径，文件夹必须通过 OpenSSL 提供的 c_rehash 工具处理。</p>
</div>
<p>你还可以通过 <code>REQUESTS_CA_BUNDLE</code> 环境变量定义可信任 CA 列表。</p>
<p>如果你将 <code>verify</code> 设置为 False，Requests 也能忽略对 SSL 证书的验证。</p>
<pre>&gt;&gt;&gt; requests.get('https://kennethreitz.org', verify=False)
&lt;Response [200]&gt;
</pre>
<p>默认情况下， <code>verify</code> 是设置为 True 的。选项 <code>verify</code> 仅应用于主机证书。</p>
<p># 对于私有证书，你也可以传递一个 CA_BUNDLE 文件的路径给 <code>verify</code>。你也可以设置
# <code>REQUEST_CA_BUNDLE</code> 环境变量。</p>
<a name="user-content-id22"></a>
<h2><a id="user-content-客户端证书" class="anchor" aria-hidden="true" href="#客户端证书"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>客户端证书</h2>
<p>你也可以指定一个本地证书用作客户端证书，可以是单个文件（包含密钥和证书）或一个包含两个文件路径的元组：</p>
<pre>&gt;&gt;&gt; requests.get('https://kennethreitz.org', cert=('/path/client.cert', '/path/client.key'))
&lt;Response [200]&gt;
</pre>
<p>或者保持在会话中：</p>
<pre>s = requests.Session()
s.cert = '/path/client.cert'
</pre>
<p>如果你指定了一个错误路径或一个无效的证书:</p>
<pre>&gt;&gt;&gt; requests.get('https://kennethreitz.org', cert='/wrong_path/client.pem')
SSLError: [Errno 336265225] _ssl.c:347: error:140B0009:SSL routines:SSL_CTX_use_PrivateKey_file:PEM lib
</pre>
<div>
<p>Warning</p>
<p>警告</p>
<p>本地证书的私有 key 必须是解密状态。目前，Requests 不支持使用加密的 key。</p>
</div>
<a name="user-content-ca"></a>
<h2><a id="user-content-ca-证书" class="anchor" aria-hidden="true" href="#ca-证书"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>CA 证书</h2>
<p>Requests 默认附带了一套它信任的根证书，来自于 <a href="https://hg.mozilla.org/mozilla-central/raw-file/tip/security/nss/lib/ckfw/builtins/certdata.txt" rel="nofollow">Mozilla trust store</a>。然而它们在每次
Requests 更新时才会更新。这意味着如果你固定使用某一版本的 Requests，你的证书有可能已经
太旧了。</p>
<p>从 Requests 2.4.0 版之后，如果系统中装了 <a href="http://certifi.io/" rel="nofollow">certifi</a>  包，Requests 会试图使用它里边的
证书。这样用户就可以在不修改代码的情况下更新他们的可信任证书。</p>
<p>为了安全起见，我们建议你经常更新 certifi！</p>
<a name="user-content-id23"></a>
<h2><a id="user-content-响应体内容工作流" class="anchor" aria-hidden="true" href="#响应体内容工作流"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>响应体内容工作流</h2>
<p>默认情况下，当你进行网络请求后，响应体会立即被下载。你可以通过 <code>stream</code> 参数覆盖这个行为，推迟下载响应体直到访问 <a href="#id24"><span id="user-content-id25">:attr:`Response.content &lt;requests.Response.content&gt;`</span></a> 属性：</p>
<pre>tarball_url = 'https://github.com/kennethreitz/requests/tarball/master'
r = requests.get(tarball_url, stream=True)
</pre>
<p>此时仅有响应头被下载下来了，连接保持打开状态，因此允许我们根据条件获取内容：</p>
<pre>if int(r.headers['content-length']) &lt; TOO_LONG:
  content = r.content
  ...
</pre>
<p>你可以进一步使用 <a href="#id26"><span id="user-content-id27">:class:`Response.iter_content &lt;requests.Response.iter_content&gt;`</span></a>
和 <a href="#id28"><span id="user-content-id29">:class:`Response.iter_lines &lt;requests.Response.iter_lines&gt;`</span></a>
方法来控制工作流，或者以 <a href="#id30"><span id="user-content-id31">:class:`Response.raw &lt;requests.Response.raw&gt;`</span></a>
从底层 urllib3 的 <a href="#id32"><span id="user-content-id33">:class:`urllib3.HTTPResponse &lt;urllib3.response.HTTPResponse`</span></a> 读取未解码的响应体。</p>
<p>如果你在请求中把 <code>stream</code> 设为 <code>True</code>，Requests 无法将连接释放回连接池，除非你
消耗了所有的数据，或者调用了 <a href="#id34"><span id="user-content-id35">:class:`Response.close &lt;requests.Response.close&gt;`</span></a>。
这样会带来连接效率低下的问题。如果你发现你在使用 <code>stream=True</code> 的同时还在部分读取请求的
body（或者完全没有读取 body），那么你就应该考虑使用 with 语句发送请求，这样可以保证请求一定会被关闭：</p>
<pre>with requests.get('http://httpbin.org/get', stream=True) as r:
    # 在此处理响应。
</pre>
<a name="user-content-id37"></a>
<h2><a id="user-content-保持活动状态持久连接" class="anchor" aria-hidden="true" href="#保持活动状态持久连接"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>保持活动状态（持久连接）</h2>
<p>好消息——归功于 urllib3，同一会话内的持久连接是完全自动处理的！同一会话内你发出的任何请求都会自动复用恰当的连接！</p>
<p>注意：只有所有的响应体数据被读取完毕连接才会被释放为连接池；所以确保将 <code>stream</code>
设置为 <code>False</code> 或读取 <code>Response</code> 对象的 <code>content</code> 属性。</p>
<a name="user-content-id38"></a>
<h2><a id="user-content-流式上传" class="anchor" aria-hidden="true" href="#流式上传"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>流式上传</h2>
<p>Requests支持流式上传，这允许你发送大的数据流或文件而无需先把它们读入内存。要使用流式上传，仅需为你的请求体提供一个类文件对象即可：</p>
<pre>with open('massive-body') as f:
    requests.post('http://some.url/streamed', data=f)
</pre>
<div>
<p>Warning</p>
<p>警告</p>
<p>我们强烈建议你用二进制模式（<a href="https://docs.python.org/2/tutorial/inputoutput.html#reading-and-writing-files" rel="nofollow">binary mode</a>）打开文件。这是因为 requests 可能会为你提供 header
中的 <code>Content-Length</code>，在这种情况下该值会被设为文件的<strong>字节数</strong>。如果你用<strong>文本模式</strong>打开文件，就可能碰到错误。</p>
</div>
<a name="user-content-id39"></a>
<h2><a id="user-content-块编码请求" class="anchor" aria-hidden="true" href="#块编码请求"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>块编码请求</h2>
<p>对于出去和进来的请求，Requests 也支持分块传输编码。要发送一个块编码的请求，仅需为你的请求体提供一个生成器（或任意没有具体长度的迭代器）：</p>
<pre>def gen():
    yield 'hi'
    yield 'there'

requests.post('http://some.url/chunked', data=gen())
</pre>
<p>对于分块的编码请求，我们最好使用 <a href="#id40"><span id="user-content-id41">:meth:`Response.iter_content() &lt;requests.models.Response.iter_content&gt;`</span></a>
对其数据进行迭代。在理想情况下，你的 request 会设置 <code>stream=True</code>，这样你就可以通过调用
<code>iter_content</code> 并将分块大小参数设为 <code>None</code>，从而进行分块的迭代。如果你要设置分块的最大体积，你可以把分块大小参数设为任意整数。</p>
<a name="user-content-post"></a>
<h2><a id="user-content-post-多个分块编码的文件" class="anchor" aria-hidden="true" href="#post-多个分块编码的文件"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>POST 多个分块编码的文件</h2>
<p>你可以在一个请求中发送多个文件。例如，假设你要上传多个图像文件到一个 HTML 表单，使用一个多文件 field 叫做 "images":</p>
<pre>&lt;input type="file" name="images" multiple="true" required="true"/&gt;
</pre>
<p>要实现，只要把文件设到一个元组的列表中，其中元组结构为 <code>(form_field_name, file_info)</code>:</p>
<pre>&gt;&gt;&gt; url = 'http://httpbin.org/post'
&gt;&gt;&gt; multiple_files = [
        ('images', ('foo.png', open('foo.png', 'rb'), 'image/png')),
        ('images', ('bar.png', open('bar.png', 'rb'), 'image/png'))]
&gt;&gt;&gt; r = requests.post(url, files=multiple_files)
&gt;&gt;&gt; r.text
{
  ...
  'files': {'images': 'data:image/png;base64,iVBORw ....'}
  'Content-Type': 'multipart/form-data; boundary=3131623adb2043caaeb5538cc7aa0b3a',
  ...
}
</pre>
<div>
<p>Warning</p>
<p>警告</p>
<p>我们强烈建议你用二进制模式（<a href="https://docs.python.org/2/tutorial/inputoutput.html#reading-and-writing-files" rel="nofollow">binary mode</a>）打开文件。这是因为 requests 可能会为你提供 header
中的 <code>Content-Length</code>，在这种情况下该值会被设为文件的<strong>字节数</strong>。如果你用<strong>文本模式</strong>打开文件，就可能碰到错误。</p>
</div>
<a name="user-content-id43"></a>
<h2><a id="user-content-事件挂钩" class="anchor" aria-hidden="true" href="#事件挂钩"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>事件挂钩</h2>
<p>Requests有一个钩子系统，你可以用来操控部分请求过程，或信号事件处理。</p>
<p>可用的钩子:</p>
<dl>
<dt><code>response</code>:</dt>
<dd>从一个请求产生的响应</dd>
</dl>
<p>你可以通过传递一个 <code>{hook_name: callback_function}</code> 字典给 <code>hooks</code> 请求参数为每个请求分配一个钩子函数：</p>
<pre>hooks=dict(response=print_url)
</pre>
<p><code>callback_function</code> 会接受一个数据块作为它的第一个参数。</p>
<pre>def print_url(r, *args, **kwargs):
    print(r.url)
</pre>
<p>若执行你的回调函数期间发生错误，系统会给出一个警告。</p>
<p>若回调函数返回一个值，默认以该值替换传进来的数据。若函数未返回任何东西，也没有什么其他的影响。</p>
<p>我们来在运行期间打印一些请求方法的参数：</p>
<pre>&gt;&gt;&gt; requests.get('http://httpbin.org', hooks=dict(response=print_url))
http://httpbin.org
&lt;Response [200]&gt;
</pre>
<a name="user-content-id44"></a>
<h2><a id="user-content-自定义身份验证" class="anchor" aria-hidden="true" href="#自定义身份验证"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>自定义身份验证</h2>
<p>Requests 允许你使用自己指定的身份验证机制。</p>
<p>任何传递给请求方法的 <code>auth</code> 参数的可调用对象，在请求发出之前都有机会修改请求。</p>
<p>自定义的身份验证机制是作为 <code>requests.auth.AuthBase</code> 的子类来实现的，也非常容易定义。Requests
在 <code>requests.auth</code> 中提供了两种常见的的身份验证方案： <code>HTTPBasicAuth</code> 和 <code>HTTPDigestAuth</code> 。</p>
<p>假设我们有一个web服务，仅在 <code>X-Pizza</code> 头被设置为一个密码值的情况下才会有响应。虽然这不太可能，但就以它为例好了。</p>
<pre>from requests.auth import AuthBase

class PizzaAuth(AuthBase):
    """Attaches HTTP Pizza Authentication to the given Request object."""
    def __init__(self, username):
        # setup any auth-related data here
        self.username = username

    def __call__(self, r):
        # modify and return the request
        r.headers['X-Pizza'] = self.username
        return r
</pre>
<p>然后就可以使用我们的PizzaAuth来进行网络请求:</p>
<pre>&gt;&gt;&gt; requests.get('http://pizzabin.org/admin', auth=PizzaAuth('kenneth'))
&lt;Response [200]&gt;
</pre>
<a name="user-content-id45"></a>
<h2><a id="user-content-流式请求" class="anchor" aria-hidden="true" href="#流式请求"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>流式请求</h2>
<p>使用 <a href="#id46"><span id="user-content-id47">:meth:`Response.iter_lines() &lt;requests.Response.iter_lines&gt;`</span></a> 你可以很方便地对流式 API
（例如 <a href="https://dev.twittercom/docs/streaming-api" rel="nofollow">Twitter 的流式 API</a> ）
进行迭代。简单地设置 <code>stream</code> 为 <code>True</code> 便可以使用 <a href="#id48"><span id="user-content-id49">:meth:`~requests.Response.iter_lines()`</span></a>
对相应进行迭代：</p>
<pre>import json
import requests

r = requests.get('http://httpbin.org/stream/20', stream=True)

for line in r.iter_lines():

    # filter out keep-alive new lines
    if line:
        decoded_line = line.decode('utf-8')
        print(json.loads(decoded_line))
</pre>
<p>当使用 decode_unicode=True 在
<a href="#id50"><span id="user-content-id51">:meth:`Response.iter_lines() &lt;requests.Response.iter_lines&gt;`</span></a> 或
<a href="#id52"><span id="user-content-id53">:meth:`Response.iter_content() &lt;requests.Response.iter_content&gt;`</span></a> 中时，你需要提供一个回退编码方式，以防服务器没有提供默认回退编码，从而导致错误：</p>
<pre>r = requests.get('http://httpbin.org/stream/20', stream=True)

if r.encoding is None:
    r.encoding = 'utf-8'

for line in r.iter_lines(decode_unicode=True):
    if line:
        print(json.loads(line))
</pre>
<div>
<p>Warning</p>
<p>警告</p>
<p><a href="#id54"><span id="user-content-id55">:meth:`~requests.Response.iter_lines()`</span></a> 不保证重进入时的安全性。多次调用该方法
会导致部分收到的数据丢失。如果你要在多处调用它，就应该使用生成的迭代器对象:</p>
<pre>lines = r.iter_lines()
# 保存第一行以供后面使用，或者直接跳过

first_line = next(lines)

for line in lines:
    print(line)
</pre>
</div>
<a name="user-content-id56"></a>
<h2><a id="user-content-代理" class="anchor" aria-hidden="true" href="#代理"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>代理</h2>
<p>如果需要使用代理，你可以通过为任意请求方法提供 <code>proxies</code> 参数来配置单个请求:</p>
<pre>import requests

proxies = {
  "http": "http://10.10.1.10:3128",
  "https": "http://10.10.1.10:1080",
}

requests.get("http://example.org", proxies=proxies)
</pre>
<p>你也可以通过环境变量 <code>HTTP_PROXY</code> 和 <code>HTTPS_PROXY</code> 来配置代理。</p>
<pre>$ export HTTP_PROXY="http://10.10.1.10:3128"
$ export HTTPS_PROXY="http://10.10.1.10:1080"

$ python
&gt;&gt;&gt; import requests
&gt;&gt;&gt; requests.get("http://example.org")
</pre>
<p>若你的代理需要使用HTTP Basic Auth，可以使用 http://user:password@host/ 语法：</p>
<pre>proxies = {
    "http": "http://user:pass@10.10.1.10:3128/",
}
</pre>
<p>要为某个特定的连接方式或者主机设置代理，使用 scheme://hostname 作为 key，
它会针对指定的主机和连接方式进行匹配。</p>
<pre>proxies = {'http://10.20.1.128': 'http://10.10.1.10:5323'}
</pre>
<p>注意，代理 URL 必须包含连接方式。</p>
<a name="user-content-socks"></a>
<h3><a id="user-content-socks" class="anchor" aria-hidden="true" href="#socks"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>SOCKS</h3>
<pre>.. versionadded:: 2.10.0

</pre>
<p>除了基本的 HTTP 代理，Request 还支持 SOCKS 协议的代理。这是一个可选功能，若要使用，
你需要安装第三方库。</p>
<p>你可以用 <code>pip</code> 获取依赖:</p>
<div class="highlight highlight-source-shell"><pre>$ pip install requests[socks]</pre></div>
<p>安装好依赖以后，使用 SOCKS 代理和使用 HTTP 代理一样简单：</p>
<pre>proxies = {
    'http': 'socks5://user:pass@host:port',
    'https': 'socks5://user:pass@host:port'
}
</pre>
<a name="user-content-id57"></a>
<h2><a id="user-content-合规性" class="anchor" aria-hidden="true" href="#合规性"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>合规性</h2>
<p>Requests 符合所有相关的规范和 RFC，这样不会为用户造成不必要的困难。但这种对规范的考虑导致一些行为对于不熟悉相关规范的人来说看似有点奇怪。</p>
<a name="user-content-id58"></a>
<h3><a id="user-content-编码方式" class="anchor" aria-hidden="true" href="#编码方式"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>编码方式</h3>
<p>当你收到一个响应时，Requests 会猜测响应的编码方式，用于在你调用 <a href="#id59"><span id="user-content-id60">:attr:`Response.text
&lt;requests.Response.text&gt;`</span></a> 方法时对响应进行解码。Requests 首先在 HTTP
头部检测是否存在指定的编码方式，如果不存在，则会使用
<a href="http://pypi.python.org/pypi/charade" rel="nofollow">charade</a> 来尝试猜测编码方式。</p>
<p>只有当 HTTP 头部不存在明确指定的字符集，并且 <code>Content-Type</code> 头部字段包含 <code>text</code> 值之时，
Requests 才不去猜测编码方式。在这种情况下，
<a href="http://www.w3.org/Protocols/rfc2616/rfc2616-sec3.html#sec3.7.1" rel="nofollow">RFC 2616</a>
指定默认字符集必须是 <code>ISO-8859-1</code> 。Requests 遵从这一规范。如果你需要一种不同的编码方式，你可以手动设置 <a href="#id61"><span id="user-content-id62">:attr:`Response.encoding &lt;requests.Response.encoding&gt;`</span></a> 属性，或使用原始的
<a href="#id63"><span id="user-content-id64">:attr:`Response.content &lt;requests.Response.content&gt;`</span></a>。</p>
<a name="user-content-http"></a>
<h2><a id="user-content-http动词" class="anchor" aria-hidden="true" href="#http动词"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>HTTP动词</h2>
<p>Requests 提供了几乎所有HTTP动词的功能：GET、OPTIONS、HEAD、POST、PUT、PATCH、DELETE。以下内容为使用 Requests 中的这些动词以及 Github API 提供了详细示例。</p>
<p>我将从最常使用的动词 GET 开始。HTTP GET 是一个幂等方法，从给定的 URL 返回一个资源。因而，当你试图从一个 web 位置获取数据之时，你应该使用这个动词。一个使用示例是尝试从 Github 上获取关于一个特定 commit 的信息。假设我们想获取 Requests 的 commit <code>a050faf</code> 的信息。我们可以这样去做：</p>
<pre>&gt;&gt;&gt; import requests
&gt;&gt;&gt; r = requests.get('https://api.github.com/repos/requests/requests/git/commits/a050faf084662f3a352dd1a941f2c7c9f886d4ad')
</pre>
<p>我们应该确认 GitHub 是否正确响应。如果正确响应，我们想弄清响应内容是什么类型的。像这样去做：</p>
<pre>&gt;&gt;&gt; if (r.status_code == requests.codes.ok):
...     print r.headers['content-type']
...
application/json; charset=utf-8
</pre>
<p>可见，GitHub 返回了 JSON 数据，非常好，这样就可以使用 <code>r.json</code> 方法把这个返回的数据解析成
Python 对象。</p>
<pre>&gt;&gt;&gt; commit_data = r.json()

&gt;&gt;&gt; print commit_data.keys()
[u'committer', u'author', u'url', u'tree', u'sha', u'parents', u'message']

&gt;&gt;&gt; print commit_data[u'committer']
{u'date': u'2012-05-10T11:10:50-07:00', u'email': u'me@kennethreitz.com', u'name': u'Kenneth Reitz'}

&gt;&gt;&gt; print commit_data[u'message']
makin' history
</pre>
<p>到目前为止，一切都非常简单。嗯，我们来研究一下 GitHub 的 API。我们可以去看看文档，但如果使用 Requests 来研究也许会更有意思一点。我们可以借助 Requests 的 OPTIONS
动词来看看我们刚使用过的 url 支持哪些 HTTP 方法。</p>
<pre>&gt;&gt;&gt; verbs = requests.options(r.url)
&gt;&gt;&gt; verbs.status_code
500
</pre>
<p>额，这是怎么回事？毫无帮助嘛！原来 GitHub，与许多 API 提供方一样，实际上并未实现
OPTIONS 方法。这是一个恼人的疏忽，但没关系，那我们可以使用枯燥的文档。然而，如果
GitHub 正确实现了 OPTIONS，那么服务器应该在响应头中返回允许用户使用的 HTTP 方法，例如：</p>
<pre>&gt;&gt;&gt; verbs = requests.options('http://a-good-website.com/api/cats')
&gt;&gt;&gt; print verbs.headers['allow']
GET,HEAD,POST,OPTIONS
</pre>
<p>转而去查看文档，我们看到对于提交信息，另一个允许的方法是 POST，它会创建一个新的提交。由于我们正在使用 Requests 代码库，我们应尽可能避免对它发送笨拙的 POST。作为替代，我们来玩玩 GitHub 的 Issue 特性。</p>
<p>本篇文档是回应 <a href="https://github.com/requests/requests/issues/482">Issue #482</a>
而添加的。鉴于该问题已经存在，我们就以它为例。先获取它。</p>
<pre>&gt;&gt;&gt; r = requests.get('https://api.github.com/requests/kennethreitz/requests/issues/482')
&gt;&gt;&gt; r.status_code
200

&gt;&gt;&gt; issue = json.loads(r.text)

&gt;&gt;&gt; print(issue[u'title'])
Feature any http verb in docs

&gt;&gt;&gt; print(issue[u'comments'])
3
</pre>
<p>Cool，有 3 个评论。我们来看一下最后一个评论。</p>
<pre>&gt;&gt;&gt; r = requests.get(r.url + u'/comments')
&gt;&gt;&gt; r.status_code
200
&gt;&gt;&gt; comments = r.json()
&gt;&gt;&gt; print comments[0].keys()
[u'body', u'url', u'created_at', u'updated_at', u'user', u'id']
&gt;&gt;&gt; print comments[2][u'body']
Probably in the "advanced" section
</pre>
<p>嗯，那看起来似乎是个愚蠢之处。我们发表个评论来告诉这个评论者他自己的愚蠢。那么，这个评论者是谁呢？</p>
<pre>&gt;&gt;&gt; print comments[2][u'user'][u'login']
kennethreitz
</pre>
<p>好，我们来告诉这个叫 Kenneth 的家伙，这个例子应该放在快速上手指南中。根据 GitHub API
文档，其方法是 POST 到该话题。我们来试试看。</p>
<pre>&gt;&gt;&gt; body = json.dumps({u"body": u"Sounds great! I'll get right on it!"})
&gt;&gt;&gt; url = u"https://api.github.com/repos/requests/requests/issues/482/comments"

&gt;&gt;&gt; r = requests.post(url=url, data=body)
&gt;&gt;&gt; r.status_code
404
</pre>
<p>额，这有点古怪哈。可能我们需要验证身份。那就有点纠结了，对吧？不对。Requests
简化了多种身份验证形式的使用，包括非常常见的 Basic Auth。</p>
<pre>&gt;&gt;&gt; from requests.auth import HTTPBasicAuth
&gt;&gt;&gt; auth = HTTPBasicAuth('fake@example.com', 'not_a_real_password')

&gt;&gt;&gt; r = requests.post(url=url, data=body, auth=auth)
&gt;&gt;&gt; r.status_code
201

&gt;&gt;&gt; content = r.json()
&gt;&gt;&gt; print(content[u'body'])
Sounds great! I'll get right on it.
</pre>
<p>太棒了！噢，不！我原本是想说等我一会，因为我得去喂我的猫。如果我能够编辑这条评论那就好了！幸运的是，GitHub 允许我们使用另一个 HTTP 动词 PATCH 来编辑评论。我们来试试。</p>
<pre>&gt;&gt;&gt; print(content[u"id"])
5804413

&gt;&gt;&gt; body = json.dumps({u"body": u"Sounds great! I'll get right on it once I feed my cat."})
&gt;&gt;&gt; url = u"https://api.github.com/repos/requests/requests/issues/comments/5804413"

&gt;&gt;&gt; r = requests.patch(url=url, data=body, auth=auth)
&gt;&gt;&gt; r.status_code
200
</pre>
<p>非常好。现在，我们来折磨一下这个叫 Kenneth 的家伙，我决定要让他急得团团转，也不告诉他是我在捣蛋。这意味着我想删除这条评论。GitHub 允许我们使用完全名副其实的 DELETE 方法来删除评论。我们来清除该评论。</p>
<pre>&gt;&gt;&gt; r = requests.delete(url=url, auth=auth)
&gt;&gt;&gt; r.status_code
204
&gt;&gt;&gt; r.headers['status']
'204 No Content'
</pre>
<p>很好。不见了。最后一件我想知道的事情是我已经使用了多少限额（ratelimit）。查查看，GitHub
在响应头部发送这个信息，因此不必下载整个网页，我将使用一个 HEAD 请求来获取响应头。</p>
<pre>&gt;&gt;&gt; r = requests.head(url=url, auth=auth)
&gt;&gt;&gt; print r.headers
...
'x-ratelimit-remaining': '4995'
'x-ratelimit-limit': '5000'
...
</pre>
<p>很好。是时候写个 Python 程序以各种刺激的方式滥用 GitHub 的 API，还可以使用 4995 次呢。</p>
<a name="user-content-id65"></a>
<h2><a id="user-content-定制动词" class="anchor" aria-hidden="true" href="#定制动词"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>定制动词</h2>
<p>有时候你会碰到一些服务器，处于某些原因，它们允许或者要求用户使用上述 HTTP 动词之外的定制动词。比如说 WEBDAV 服务器会要求你使用 MKCOL 方法。别担心，Requests 一样可以搞定它们。你可以使用内建的 <code>.request</code> 方法，例如：</p>
<pre>&gt;&gt;&gt; r = requests.request('MKCOL', url, data=data)
&gt;&gt;&gt; r.status_code
200 # Assuming your call was correct
</pre>
<p>这样你就可以使用服务器要求的任意方法动词了。</p>
<a name="user-content-id66"></a>
<h2><a id="user-content-响应头链接字段" class="anchor" aria-hidden="true" href="#响应头链接字段"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>响应头链接字段</h2>
<p>许多 HTTP API 都有响应头链接字段的特性，它们使得 API 能够更好地自我描述和自我显露。</p>
<p>GitHub 在 API 中为 <a href="http://developer.github.com/v3/#pagination">分页</a> 使用这些特性，例如:</p>
<pre>&gt;&gt;&gt; url = 'https://api.github.com/users/kennethreitz/repos?page=1&amp;per_page=10'
&gt;&gt;&gt; r = requests.head(url=url)
&gt;&gt;&gt; r.headers['link']
'&lt;https://api.github.com/users/kennethreitz/repos?page=2&amp;per_page=10&gt;; rel="next", &lt;https://api.github.com/users/kennethreitz/repos?page=6&amp;per_page=10&gt;; rel="last"'
</pre>
<p>Requests 会自动解析这些响应头链接字段，并使得它们非常易于使用:</p>
<pre>&gt;&gt;&gt; r.links["next"]
{'url': 'https://api.github.com/users/kennethreitz/repos?page=2&amp;per_page=10', 'rel': 'next'}

&gt;&gt;&gt; r.links["last"]
{'url': 'https://api.github.com/users/kennethreitz/repos?page=7&amp;per_page=10', 'rel': 'last'}
</pre>
<a name="user-content-id68"></a>
<h2><a id="user-content-传输适配器" class="anchor" aria-hidden="true" href="#传输适配器"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>传输适配器</h2>
<p>从 v1.0.0 以后，Requests 的内部采用了模块化设计。部分原因是为了实现传输适配器（Transport Adapter），你可以看看关于它的<a href="http://www.kennethreitz.org/essays/the-future-of-python-http" rel="nofollow">最早描述</a>。传输适配器提供了一个机制，让你可以为 HTTP 服务定义交互方法。尤其是它允许你应用服务前的配置。</p>
<p>Requests 自带了一个传输适配器，也就是 <a href="#id69"><span id="user-content-id70">:class:`HTTPAdapter &lt;requests.adapters.HTTPAdapter&gt;`</span></a>。
这个适配器使用了强大的 <a href="https://github.com/shazow/urllib3">urllib3</a>，为 Requests 提供了默认的 HTTP 和 HTTPS 交互。每当 <a href="#id71"><span id="user-content-id72">:class:`Session &lt;requests.Session&gt;`</span></a> 被初始化，就会有适配器附着在 <a href="#id73"><span id="user-content-id74">:class:`Session &lt;requests.Session&gt;`</span></a>
上，其中一个供 HTTP 使用，另一个供 HTTPS 使用。</p>
<p>Request 允许用户创建和使用他们自己的传输适配器，实现他们需要的特殊功能。创建好以后，传输适配器可以被加载到一个会话对象上，附带着一个说明，告诉会话适配器应该应用在哪个 web
服务上。</p>
<pre>&gt;&gt;&gt; s = requests.Session()
&gt;&gt;&gt; s.mount('http://www.github.com', MyAdapter())
</pre>
<p>这个 mount 调用会注册一个传输适配器的特定实例到一个前缀上面。加载以后，任何使用该会话的 HTTP
请求，只要其 URL 是以给定的前缀开头，该传输适配器就会被使用到。</p>
<p>传输适配器的众多实现细节不在本文档的覆盖范围内，不过你可以看看接下来这个简单的 SSL
用例。更多的用法，你也许该考虑为 <a href="#id75"><span id="user-content-id76">:class:`BaseAdapter &lt;requests.adapters.BaseAdapter&gt;`</span></a> 创建子类。</p>
<a name="user-content-id77"></a>
<h3><a id="user-content-示例-指定的-ssl-版本" class="anchor" aria-hidden="true" href="#示例-指定的-ssl-版本"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>示例: 指定的 SSL 版本</h3>
<p>Requests 开发团队刻意指定了内部库（<a href="https://github.com/shazow/urllib3">urllib3</a>）的默认 SSL 版本。一般情况下这样做没有问题，不过是不是你可能会需要连接到一个服务节点，而该节点使用了和默认不同的 SSL 版本。</p>
<p>你可以使用传输适配器解决这个问题，通过利用 HTTPAdapter 现有的大部分实现，再加上一个
<em>ssl_version</em> 参数并将它传递到 <code>urllib3</code> 中。我们会创建一个传输适配器，用来告诉
<code>urllib3</code> 让它使用 SSLv3：</p>
<pre>import ssl

from requests.adapters import HTTPAdapter
from requests.packages.urllib3.poolmanager import PoolManager


class Ssl3HttpAdapter(HTTPAdapter):
    """"Transport adapter" that allows us to use SSLv3."""

    def init_poolmanager(self, connections, maxsize, block=False):
        self.poolmanager = PoolManager(num_pools=connections,
                                       maxsize=maxsize,
                                       block=block,
                                       ssl_version=ssl.PROTOCOL_SSLv3)
</pre>
<a name="user-content-id79"></a>
<h2><a id="user-content-阻塞和非阻塞" class="anchor" aria-hidden="true" href="#阻塞和非阻塞"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>阻塞和非阻塞</h2>
<p>使用默认的传输适配器，Requests 不提供任何形式的非阻塞 IO。
<a href="#id80"><span id="user-content-id81">:attr:`Response.content &lt;requests.Response.content&gt;`</span></a> 属性会阻塞，直到整个响应下载完成。如果你需要更多精细控制，该库的数据流功能（见 <a href="#id82"><span id="user-content-id83">:ref:`streaming-requests`</span></a>）
允许你每次接受少量的一部分响应，不过这些调用依然是阻塞式的。</p>
<p>如果你对于阻塞式 IO 有所顾虑，还有很多项目可以供你使用，它们结合了 Requests 和 Python
的某个异步框架。典型的优秀例子是 <a href="https://github.com/kennethreitz/grequests">grequests</a> 和 <a href="https://github.com/ross/requests-futures">requests-futures</a>。</p>
<a name="user-content-header"></a>
<h2><a id="user-content-header-排序" class="anchor" aria-hidden="true" href="#header-排序"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Header 排序</h2>
<p>在某些特殊情况下你也许需要按照次序来提供 header，如果你向 <code>headers</code> 关键字参数传入一个
<code>OrderedDict</code>，就可以向提供一个带排序的 header。<strong>然而</strong>，Requests 使用的默认
header 的次序会被优先选择，这意味着如果你在 <code>headers</code> 关键字参数中覆盖了默认 header，和关键字参数中别的 header 相比，它们也许看上去会是次序错误的。</p>
<p>如果这个对你来说是个问题，那么用户应该考虑在 <a href="#id84"><span id="user-content-id85">:class:`Session &lt;requests.Session&gt;`</span></a>
对象上面设置默认 header，只要将 <a href="#id86"><span id="user-content-id87">:data:`Session &lt;requests.Session.headers&gt;`</span></a>
设为一个定制的  <code>OrderedDict</code> 即可。这样就会让它成为优选的次序。</p>
<a name="user-content-timeout"></a>
<h2><a id="user-content-超时timeout" class="anchor" aria-hidden="true" href="#超时timeout"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>超时（timeout）</h2>
<p>为防止服务器不能及时响应，大部分发至外部服务器的请求都应该带着 timeout 参数。在默认情况下，除非显式指定了 timeout 值，requests 是不会自动进行超时处理的。如果没有 timeout，你的代码可能会挂起若干分钟甚至更长时间。</p>
<p><strong>连接</strong>超时指的是在你的客户端实现到远端机器端口的连接时（对应的是`connect()`_），Request 会等待的秒数。一个很好的实践方法是把连接超时设为比 3 的倍数略大的一个数值，因为 <a href="http://www.hjp.at/doc/rfc/rfc2988.txt" rel="nofollow">TCP 数据包重传窗口 (TCP packet retransmission window)</a>
的默认大小是 3。</p>
<p>一旦你的客户端连接到了服务器并且发送了 HTTP 请求，<strong>读取</strong>超时指的就是客户端等待服务器发送请求的时间。（特定地，它指的是客户端要等待服务器发送字节<strong>之间</strong>的时间。在 99.9%
的情况下这指的是服务器发送第一个字节之前的时间）。</p>
<p>如果你制订了一个单一的值作为 timeout，如下所示：</p>
<pre>r = requests.get('https://github.com', timeout=5)
</pre>
<p>这一 timeout 值将会用作 <code>connect</code> 和 <code>read</code> 二者的 timeout。如果要分别制定，就传入一个元组：</p>
<pre>r = requests.get('https://github.com', timeout=(3.05, 27))
</pre>
<p>如果远端服务器很慢，你可以让 Request 永远等待，传入一个 None 作为 timeout 值，然后就冲咖啡去吧。</p>
<div class="highlight highlight-source-python"><pre>r <span class="pl-k">=</span> requests.get(<span class="pl-s"><span class="pl-pds">'</span>https://github.com<span class="pl-pds">'</span></span>, <span class="pl-v">timeout</span><span class="pl-k">=</span><span class="pl-c1">None</span>)</pre></div>

</article>
  </div>

    </div>

  

  <details class="details-reset details-overlay details-overlay-dark">
    <summary data-hotkey="l" aria-label="Jump to line"></summary>
    <details-dialog class="Box Box--overlay d-flex flex-column anim-fade-in fast linejump" aria-label="Jump to line">
      <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="js-jump-to-line-form Box-body d-flex" action="" accept-charset="UTF-8" method="get"><input name="utf8" type="hidden" value="&#x2713;" />
        <input class="form-control flex-auto mr-3 linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" aria-label="Jump to line" autofocus>
        <button type="submit" class="btn" data-close-dialog>Go</button>
</form>    </details-dialog>
  </details>



  </div>
</div>

    </main>
  </div>
  

  </div>

        
<div class="footer container-lg width-full p-responsive" role="contentinfo">
  <div class="position-relative d-flex flex-row-reverse flex-lg-row flex-wrap flex-lg-nowrap flex-justify-center flex-lg-justify-between pt-6 pb-2 mt-6 f6 text-gray border-top border-gray-light ">
    <ul class="list-style-none d-flex flex-wrap col-12 col-lg-5 flex-justify-center flex-lg-justify-between mb-2 mb-lg-0">
      <li class="mr-3 mr-lg-0">&copy; 2019 <span title="0.38937s from unicorn-7685555bfd-q8sd2">GitHub</span>, Inc.</li>
        <li class="mr-3 mr-lg-0"><a data-ga-click="Footer, go to terms, text:terms" href="https://github.com/site/terms">Terms</a></li>
        <li class="mr-3 mr-lg-0"><a data-ga-click="Footer, go to privacy, text:privacy" href="https://github.com/site/privacy">Privacy</a></li>
        <li class="mr-3 mr-lg-0"><a data-ga-click="Footer, go to security, text:security" href="https://github.com/security">Security</a></li>
        <li class="mr-3 mr-lg-0"><a href="https://githubstatus.com/" data-ga-click="Footer, go to status, text:status">Status</a></li>
        <li><a data-ga-click="Footer, go to help, text:help" href="https://help.github.com">Help</a></li>
    </ul>

    <a aria-label="Homepage" title="GitHub" class="footer-octicon d-none d-lg-block mx-lg-4" href="https://github.com">
      <svg height="24" class="octicon octicon-mark-github" viewBox="0 0 16 16" version="1.1" width="24" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"/></svg>
</a>
   <ul class="list-style-none d-flex flex-wrap col-12 col-lg-5 flex-justify-center flex-lg-justify-between mb-2 mb-lg-0">
        <li class="mr-3 mr-lg-0"><a data-ga-click="Footer, go to contact, text:contact" href="https://github.com/contact">Contact GitHub</a></li>
        <li class="mr-3 mr-lg-0"><a href="https://github.com/pricing" data-ga-click="Footer, go to Pricing, text:Pricing">Pricing</a></li>
      <li class="mr-3 mr-lg-0"><a href="https://developer.github.com" data-ga-click="Footer, go to api, text:api">API</a></li>
      <li class="mr-3 mr-lg-0"><a href="https://training.github.com" data-ga-click="Footer, go to training, text:training">Training</a></li>
        <li class="mr-3 mr-lg-0"><a href="https://github.blog" data-ga-click="Footer, go to blog, text:blog">Blog</a></li>
        <li><a data-ga-click="Footer, go to about, text:about" href="https://github.com/about">About</a></li>

    </ul>
  </div>
  <div class="d-flex flex-justify-center pb-6">
    <span class="f6 text-gray-light"></span>
  </div>
</div>



  <div id="ajax-error-message" class="ajax-error-message flash flash-error">
    <svg class="octicon octicon-alert" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.893 1.5c-.183-.31-.52-.5-.887-.5s-.703.19-.886.5L.138 13.499a.98.98 0 0 0 0 1.001c.193.31.53.501.886.501h13.964c.367 0 .704-.19.877-.5a1.03 1.03 0 0 0 .01-1.002L8.893 1.5zm.133 11.497H6.987v-2.003h2.039v2.003zm0-3.004H6.987V5.987h2.039v4.006z"/></svg>
    <button type="button" class="flash-close js-ajax-error-dismiss" aria-label="Dismiss error">
      <svg class="octicon octicon-x" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"/></svg>
    </button>
    You can’t perform that action at this time.
  </div>


    
    <script crossorigin="anonymous" integrity="sha512-87Pu+LHeTMadjEvfF88jnEFgqAEME57RFbnvij/gFd1C0w2R5K4CrOEJ5F0rCECH/rR85+TAF6Hw8ZNTH0tZ8Q==" type="application/javascript" src="https://github.githubassets.com/assets/frameworks-86315523.js"></script>
    
    <script crossorigin="anonymous" async="async" integrity="sha512-frM9+HmRRFzqYpDZfN90t/U7HTm0ZGvsJyK2IAnkkvZDSb9Hwyarss1CSRX7vetcNZ2XnmMrOIMCNcgDI81H0g==" type="application/javascript" src="https://github.githubassets.com/assets/github-bootstrap-1d407193.js"></script>
    
    
    
  <div class="js-stale-session-flash stale-session-flash flash flash-warn flash-banner" hidden
    >
    <svg class="octicon octicon-alert" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.893 1.5c-.183-.31-.52-.5-.887-.5s-.703.19-.886.5L.138 13.499a.98.98 0 0 0 0 1.001c.193.31.53.501.886.501h13.964c.367 0 .704-.19.877-.5a1.03 1.03 0 0 0 .01-1.002L8.893 1.5zm.133 11.497H6.987v-2.003h2.039v2.003zm0-3.004H6.987V5.987h2.039v4.006z"/></svg>
    <span class="signed-in-tab-flash">You signed in with another tab or window. <a href="">Reload</a> to refresh your session.</span>
    <span class="signed-out-tab-flash">You signed out in another tab or window. <a href="">Reload</a> to refresh your session.</span>
  </div>
  <template id="site-details-dialog">
  <details class="details-reset details-overlay details-overlay-dark lh-default text-gray-dark hx_rsm" open>
    <summary role="button" aria-label="Close dialog"></summary>
    <details-dialog class="Box Box--overlay d-flex flex-column anim-fade-in fast hx_rsm-dialog hx_rsm-modal">
      <button class="Box-btn-octicon m-0 btn-octicon position-absolute right-0 top-0" type="button" aria-label="Close dialog" data-close-dialog>
        <svg class="octicon octicon-x" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"/></svg>
      </button>
      <div class="octocat-spinner my-6 js-details-dialog-spinner"></div>
    </details-dialog>
  </details>
</template>

  <div class="Popover js-hovercard-content position-absolute" style="display: none; outline: none;" tabindex="0">
  <div class="Popover-message Popover-message--bottom-left Popover-message--large Box box-shadow-large" style="width:360px;">
  </div>
</div>

  <div aria-live="polite" class="js-global-screen-reader-notice sr-only"></div>

  </body>
</html>

