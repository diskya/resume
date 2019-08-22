





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
  
  <title>requests-docs-cn/quickstart.rst at master · requests/requests-docs-cn</title>
    <meta name="description" content="Chinese translation of Requests&#39; documentation. Contribute to requests/requests-docs-cn development by creating an account on GitHub.">
    <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
  <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
  <meta property="fb:app_id" content="1401488693436528">

    <meta name="twitter:image:src" content="https://avatars2.githubusercontent.com/u/2805331?s=400&amp;v=4" /><meta name="twitter:site" content="@github" /><meta name="twitter:card" content="summary" /><meta name="twitter:title" content="requests/requests-docs-cn" /><meta name="twitter:description" content="Chinese translation of Requests&#39; documentation. Contribute to requests/requests-docs-cn development by creating an account on GitHub." />
    <meta property="og:image" content="https://avatars2.githubusercontent.com/u/2805331?s=400&amp;v=4" /><meta property="og:site_name" content="GitHub" /><meta property="og:type" content="object" /><meta property="og:title" content="requests/requests-docs-cn" /><meta property="og:url" content="https://github.com/requests/requests-docs-cn" /><meta property="og:description" content="Chinese translation of Requests&#39; documentation. Contribute to requests/requests-docs-cn development by creating an account on GitHub." />

  <link rel="assets" href="https://github.githubassets.com/">
  <link rel="web-socket" href="wss://live.github.com/_sockets/VjI6NDMxNDE3Njg1OmVjMDg1ZjJhMzVkMGMzN2VlNDIxNzA4NzBjZDUxZDRkYWFmNzNkNzg3YzJiM2FlMTdkNDJjZWQ1YzZmMTA1YzI=--221e8ec420cb4d364bf5d1e0649d2a967d1c1f47">
  <meta name="pjax-timeout" content="1000">
  <link rel="sudo-modal" href="/sessions/sudo_modal">
  <meta name="request-id" content="BC05:7BB4:AB4330:F5B3EE:5D5E69A5" data-pjax-transient>


  

  <meta name="selected-link" value="repo_source" data-pjax-transient>

      <meta name="google-site-verification" content="KT5gs8h0wvaagLKAVWq8bbeNwnZZK1r1XQysX3xurLU">
    <meta name="google-site-verification" content="ZzhVyEFwb7w3e0-uOTltm8Jsck2F5StVihD0exw2fsA">
    <meta name="google-site-verification" content="GXs5KoUUkNCoaAZn7wPN-t01Pywp9M3sEjnt_3_ZWPc">

  <meta name="octolytics-host" content="collector.githubapp.com" /><meta name="octolytics-app-id" content="github" /><meta name="octolytics-event-url" content="https://collector.githubapp.com/github-external/browser_event" /><meta name="octolytics-dimension-request_id" content="BC05:7BB4:AB4330:F5B3EE:5D5E69A5" /><meta name="octolytics-dimension-region_edge" content="ap-southeast-1" /><meta name="octolytics-dimension-region_render" content="iad" /><meta name="octolytics-dimension-ga_id" content="" class="js-octo-ga-id" /><meta name="octolytics-dimension-visitor_id" content="4487529527760973873" /><meta name="octolytics-actor-id" content="52539335" /><meta name="octolytics-actor-login" content="diskya" /><meta name="octolytics-actor-hash" content="f1dee13116218c1520fe186a204d230fce81e30c5d23c7028f9d107bf0d84fe3" />
<meta name="analytics-location" content="/&lt;user-name&gt;/&lt;repo-name&gt;/blob/show" data-pjax-transient="true" />



    <meta name="google-analytics" content="UA-3769691-2">

  <meta class="js-ga-set" name="userId" content="30fae021130ca43b6ebcbc4616bb5d5e">

<meta class="js-ga-set" name="dimension1" content="Logged In">



  

      <meta name="hostname" content="github.com">
    <meta name="user-login" content="diskya">

      <meta name="expected-hostname" content="github.com">
    <meta name="js-proxy-site-detection-payload" content="MDc0MGFmNjgyYzMzMDA5YjY4NjdjMDgyMmRiOWIzNWJkMjNlYmQ1ZWY4OTNhNTZmZTM2MTk1NjYzYzJkOTZhOXx7InJlbW90ZV9hZGRyZXNzIjoiNTIuNzYuODcuNTQiLCJyZXF1ZXN0X2lkIjoiQkMwNTo3QkI0OkFCNDMzMDpGNUIzRUU6NUQ1RTY5QTUiLCJ0aW1lc3RhbXAiOjE1NjY0Njg1MjAsImhvc3QiOiJnaXRodWIuY29tIn0=">

    <meta name="enabled-features" content="ACTIONS_V2_ON_MARKETPLACE,MARKETPLACE_FEATURED_BLOG_POSTS,MARKETPLACE_INVOICED_BILLING,MARKETPLACE_SOCIAL_PROOF_CUSTOMERS,MARKETPLACE_TRENDING_SOCIAL_PROOF,MARKETPLACE_RECOMMENDATIONS,MARKETPLACE_PENDING_INSTALLATIONS,NOTIFY_ON_BLOCK,RELATED_ISSUES,GHE_CLOUD_TRIAL">

  <meta name="html-safe-nonce" content="1c13858d4e39c8968c8858d9a0551451e1f4cc19">

  <meta http-equiv="x-pjax-version" content="d9e76c4c13adffb60a475a702b588e42">
  

      <link href="https://github.com/requests/requests-docs-cn/commits/master.atom" rel="alternate" title="Recent Commits to requests-docs-cn:master" type="application/atom+xml">

  <meta name="go-import" content="github.com/requests/requests-docs-cn git https://github.com/requests/requests-docs-cn.git">

  <meta name="octolytics-dimension-user_id" content="2805331" /><meta name="octolytics-dimension-user_login" content="requests" /><meta name="octolytics-dimension-repository_id" content="8642896" /><meta name="octolytics-dimension-repository_nwo" content="requests/requests-docs-cn" /><meta name="octolytics-dimension-repository_public" content="true" /><meta name="octolytics-dimension-repository_is_fork" content="false" /><meta name="octolytics-dimension-repository_network_root_id" content="8642896" /><meta name="octolytics-dimension-repository_network_root_nwo" content="requests/requests-docs-cn" /><meta name="octolytics-dimension-repository_explore_github_marketplace_ci_cta_shown" content="false" />


    <link rel="canonical" href="https://github.com/requests/requests-docs-cn/blob/master/docs/user/quickstart.rst" data-pjax-transient>


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
          data-jump-to-suggestions-path="/_graphql/GetSuggestedNavigationDestinations#csrf-token=ITRImf5o+5ew1UUOoPIWQd4fdIp3Ge4yELlUZ+eWb2uaJZXHuYGWnf+e9rOKtpiNcyhBuQCROxdJLuyG1lIvFw=="
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
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form action="/logout" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="9kctPc5mV4g6XTVGz6xHxdSUTpUzN2+OJwS+tyUUp8enMaXH0SkIxNAP/i9X0yC+0nZyOieJkYOPTXxN7TTBKA==" />
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
    <summary class="btn-link btn-block link-gray no-underline js-toggle-user-status-edit toggle-user-status-edit " aria-haspopup="dialog" role="menuitem" data-hydro-click="{&quot;event_type&quot;:&quot;user_profile.click&quot;,&quot;payload&quot;:{&quot;profile_user_id&quot;:2805331,&quot;target&quot;:&quot;EDIT_USER_STATUS&quot;,&quot;user_id&quot;:52539335,&quot;client_id&quot;:&quot;1044834388.1564799025&quot;,&quot;originating_request_id&quot;:&quot;BC05:7BB4:AB4330:F5B3EE:5D5E69A5&quot;,&quot;originating_url&quot;:&quot;https://github.com/requests/requests-docs-cn/blob/master/docs/user/quickstart.rst&quot;,&quot;referrer&quot;:&quot;https://github.com/requests/requests-docs-cn/tree/master/docs/user&quot;}}" data-hydro-click-hmac="57cf377c69ed09a5df2040bdbbf1a15dea4bbb4da8ca28e9875773995fae9f81">
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
      <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="position-relative flex-auto js-user-status-form" action="/users/status?compact=1&amp;link_mentions=0&amp;truncate=1" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="_method" value="put" /><input type="hidden" name="authenticity_token" value="O7RtXLqaNwI1o4uqSu8pIauI4ARi5zLMBYPbyaHZxYJl+JV0x+NUFkq1VxZKRhtT3BHXEY8ILBt9LoU5Wr4ZCA==" />
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
          <button type="button" class="btn-link dropdown-item ws-normal js-user-status-expire-button" title="in 30 minutes" value="2019-08-22T18:38:40+08:00">
            in 30 minutes
          </button>
        </li>
        <li>
          <button type="button" class="btn-link dropdown-item ws-normal js-user-status-expire-button" title="in 1 hour" value="2019-08-22T19:08:40+08:00">
            in 1 hour
          </button>
        </li>
        <li>
          <button type="button" class="btn-link dropdown-item ws-normal js-user-status-expire-button" title="in 4 hours" value="2019-08-22T22:08:40+08:00">
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
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="logout-form" action="/logout" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="QyUVtHKUX5HK6FJyYxmGX3XL8kdh095jZYOqscDup6MSU51ObdsA3SC6mRv7ZuEkcynO6HVtIG7NymhLCM7BTA==" />
      
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
    
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form data-remote="true" class="clearfix js-social-form js-social-container" action="/notifications/subscribe" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="fhhP4VSD+Q2YIqsqGgRgOGCpOB31q2iFMyAR6Os5TAdcLuebWVtpkZg3u5AQc67F2cz+aEm6vS0+IrUsDxlYAg==" />      <input type="hidden" name="repository_id" value="8642896">

      <details class="details-reset details-overlay select-menu float-left">
        <summary class="select-menu-button float-left btn btn-sm btn-with-count" data-hydro-click="{&quot;event_type&quot;:&quot;repository.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;WATCH_BUTTON&quot;,&quot;repository_id&quot;:8642896,&quot;client_id&quot;:&quot;1044834388.1564799025&quot;,&quot;originating_request_id&quot;:&quot;BC05:7BB4:AB4330:F5B3EE:5D5E69A5&quot;,&quot;originating_url&quot;:&quot;https://github.com/requests/requests-docs-cn/blob/master/docs/user/quickstart.rst&quot;,&quot;referrer&quot;:&quot;https://github.com/requests/requests-docs-cn/tree/master/docs/user&quot;,&quot;user_id&quot;:52539335}}" data-hydro-click-hmac="702e3e15f1935fd2d130879fbbad1e16c55e49a4e43433e8cad1af05646ec149" data-ga-click="Repository, click Watch settings, action:blob#show">          <span data-menu-button>
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
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="starred js-social-form" action="/requests/requests-docs-cn/unstar" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="U14JlC6oK1MdUQRQ7JxEoz5JG7GroA4uzMz4Z07ejk5umn5Dw4jNq3x6iyWbIRxyM9aOmB5QP7wDYvII1+vR5w==" />
      <input type="hidden" name="context" value="repository"></input>
      <button type="submit" class="btn btn-sm btn-with-count js-toggler-target" aria-label="Unstar this repository" title="Unstar requests/requests-docs-cn" data-hydro-click="{&quot;event_type&quot;:&quot;repository.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;UNSTAR_BUTTON&quot;,&quot;repository_id&quot;:8642896,&quot;client_id&quot;:&quot;1044834388.1564799025&quot;,&quot;originating_request_id&quot;:&quot;BC05:7BB4:AB4330:F5B3EE:5D5E69A5&quot;,&quot;originating_url&quot;:&quot;https://github.com/requests/requests-docs-cn/blob/master/docs/user/quickstart.rst&quot;,&quot;referrer&quot;:&quot;https://github.com/requests/requests-docs-cn/tree/master/docs/user&quot;,&quot;user_id&quot;:52539335}}" data-hydro-click-hmac="1c2923ce124260c40f4b54b8154d38828e3dafe7e45aa1fb2edbc30fe418d158" data-ga-click="Repository, click unstar button, action:blob#show; text:Unstar">        <svg class="octicon octicon-star v-align-text-bottom" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M14 6l-4.9-.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14 7 11.67 11.33 14l-.93-4.74L14 6z"/></svg>
        Unstar
</button>        <a class="social-count js-social-count" href="/requests/requests-docs-cn/stargazers"
           aria-label="57 users starred this repository">
           57
        </a>
</form>
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="unstarred js-social-form" action="/requests/requests-docs-cn/star" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="d7dG8Hl1xyWJxRG6mJrk88wyf6F7qOv7p7RCBdfFckNPRl+BdASWvJtM4wQGaHKZPgbOOozgv2/OstS8wUlGVA==" />
      <input type="hidden" name="context" value="repository"></input>
      <button type="submit" class="btn btn-sm btn-with-count js-toggler-target" aria-label="Unstar this repository" title="Star requests/requests-docs-cn" data-hydro-click="{&quot;event_type&quot;:&quot;repository.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;STAR_BUTTON&quot;,&quot;repository_id&quot;:8642896,&quot;client_id&quot;:&quot;1044834388.1564799025&quot;,&quot;originating_request_id&quot;:&quot;BC05:7BB4:AB4330:F5B3EE:5D5E69A5&quot;,&quot;originating_url&quot;:&quot;https://github.com/requests/requests-docs-cn/blob/master/docs/user/quickstart.rst&quot;,&quot;referrer&quot;:&quot;https://github.com/requests/requests-docs-cn/tree/master/docs/user&quot;,&quot;user_id&quot;:52539335}}" data-hydro-click-hmac="8b420cc00df779c3d72b3a2a92fb9504405a09d1a1e50b7081be8ee1697e7f60" data-ga-click="Repository, click star button, action:blob#show; text:Star">        <svg class="octicon octicon-star v-align-text-bottom" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M14 6l-4.9-.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14 7 11.67 11.33 14l-.93-4.74L14 6z"/></svg>
        Star
</button>        <a class="social-count js-social-count" href="/requests/requests-docs-cn/stargazers"
           aria-label="57 users starred this repository">
          57
        </a>
</form>  </div>

  </li>

  <li>
          <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="btn-with-count" action="/requests/requests-docs-cn/fork" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="tVlNGiV7oig2EElJtRUd3LfC/0UMbz9Ac8OMLEBxo1jXS6OBsmSmrS8cecCzA1pr3wdxRS4pmr/gbnMZVoDL2Q==" />
            <button class="btn btn-sm btn-with-count" data-hydro-click="{&quot;event_type&quot;:&quot;repository.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;FORK_BUTTON&quot;,&quot;repository_id&quot;:8642896,&quot;client_id&quot;:&quot;1044834388.1564799025&quot;,&quot;originating_request_id&quot;:&quot;BC05:7BB4:AB4330:F5B3EE:5D5E69A5&quot;,&quot;originating_url&quot;:&quot;https://github.com/requests/requests-docs-cn/blob/master/docs/user/quickstart.rst&quot;,&quot;referrer&quot;:&quot;https://github.com/requests/requests-docs-cn/tree/master/docs/user&quot;,&quot;user_id&quot;:52539335}}" data-hydro-click-hmac="50be365916a2f2342b7f47cb3816dae4b4a2a538c37036f34784e162f5da22dc" data-ga-click="Repository, show fork modal, action:blob#show; text:Fork" type="submit" title="Fork your own copy of requests/requests-docs-cn to your account" aria-label="Fork your own copy of requests/requests-docs-cn to your account">              <svg class="octicon octicon-repo-forked v-align-text-bottom" viewBox="0 0 10 16" version="1.1" width="10" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8 1a1.993 1.993 0 0 0-1 3.72V6L5 8 3 6V4.72A1.993 1.993 0 0 0 2 1a1.993 1.993 0 0 0-1 3.72V6.5l3 3v1.78A1.993 1.993 0 0 0 5 15a1.993 1.993 0 0 0 1-3.72V9.5l3-3V4.72A1.993 1.993 0 0 0 8 1zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3 10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3-10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
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

    
    


  


    <a class="d-none js-permalink-shortcut" data-hotkey="y" href="/requests/requests-docs-cn/blob/6175fad9210928652c59d4ea0673c9ed1e969773/docs/user/quickstart.rst">Permalink</a>

    <!-- blob contrib key: blob_contributors:v21:01a1d8ebde9c6da35cf530d641d2d2f6 -->
      

    <div class="d-flex flex-items-start flex-shrink-0 pb-3 flex-column flex-md-row">
      <span class="d-flex flex-justify-between width-full width-md-auto">
        
<details class="details-reset details-overlay select-menu branch-select-menu  hx_rsm" id="branch-select-menu">
  <summary class="btn btn-sm select-menu-button css-truncate"
           data-hotkey="w"
           title="Switch branches or tags">
    <i>Branch:</i>
    <span class="css-truncate-target" data-menu-button>master</span>
  </summary>

  <details-menu class="select-menu-modal hx_rsm-modal position-absolute" style="z-index: 99;" src="/requests/requests-docs-cn/ref-list/master/docs/user/quickstart.rst?source_action=show&amp;source_controller=blob" preload>
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
          <clipboard-copy value="docs/user/quickstart.rst" class="btn btn-sm BtnGroup-item">
            Copy path
          </clipboard-copy>
        </div>
      </span>
      <h2 id="blob-path" class="breadcrumb flex-auto min-width-0 text-normal flex-md-self-center ml-md-2 mr-md-3 my-2 my-md-0">
        <span class="js-repo-root text-bold"><span class="js-path-segment"><a data-pjax="true" href="/requests/requests-docs-cn"><span>requests-docs-cn</span></a></span></span><span class="separator">/</span><span class="js-path-segment"><a data-pjax="true" href="/requests/requests-docs-cn/tree/master/docs"><span>docs</span></a></span><span class="separator">/</span><span class="js-path-segment"><a data-pjax="true" href="/requests/requests-docs-cn/tree/master/docs/user"><span>user</span></a></span><span class="separator">/</span><strong class="final-path">quickstart.rst</strong>
      </h2>

      <div class="BtnGroup flex-shrink-0 d-none d-md-inline-block">
        <a href="/requests/requests-docs-cn/find/master"
              class="js-pjax-capture-input btn btn-sm BtnGroup-item"
              data-pjax
              data-hotkey="t">
          Find file
        </a>
        <clipboard-copy value="docs/user/quickstart.rst" class="btn btn-sm BtnGroup-item">
          Copy path
        </clipboard-copy>
      </div>
    </div>



    
  <div class="Box Box--condensed d-flex flex-column flex-shrink-0">
      <div class="Box-body d-flex flex-justify-between bg-blue-light flex-column flex-md-row flex-items-start flex-md-items-center">
        <span class="pr-md-4 f6">
          <a rel="contributor" data-skip-pjax="true" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=15180122" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/houbaron"><img class="avatar" src="https://avatars1.githubusercontent.com/u/15180122?s=40&amp;v=4" width="20" height="20" alt="@houbaron" /></a>
          <a class="text-bold link-gray-dark lh-default v-align-middle" rel="contributor" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=15180122" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/houbaron">houbaron</a>
            <span class="lh-default v-align-middle">
              <a data-pjax="true" title="「界面」-&gt;「接口」

私以为此处使用「接口」一词更为合适，虽然英语皆为 interface。" class="link-gray" href="/requests/requests-docs-cn/commit/d095479220bc0ea2174b153f7002470eb84b7db2">「界面」-&gt;「接口」</a>
            </span>
        </span>
        <span class="d-inline-block flex-shrink-0 v-align-bottom f6 mt-2 mt-md-0">
          <a class="pr-2 text-mono link-gray" href="/requests/requests-docs-cn/commit/d095479220bc0ea2174b153f7002470eb84b7db2" data-pjax>d095479</a>
          <relative-time datetime="2018-05-03T07:09:19Z">May 3, 2018</relative-time>
        </span>
      </div>

    <div class="Box-body d-flex flex-items-center flex-auto f6 border-bottom-0 flex-wrap" >
      <details class="details-reset details-overlay details-overlay-dark lh-default text-gray-dark float-left mr-2" id="blob_contributors_box">
        <summary class="btn-link" aria-haspopup="dialog">
          <span><strong>26</strong> contributors</span>
        </summary>
        <details-dialog
          class="Box Box--overlay d-flex flex-column anim-fade-in fast"
          aria-label="Users who have contributed to this file"
          src="/requests/requests-docs-cn/contributors/master/docs/user/quickstart.rst/list" preload>
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
    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=1382556" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/requests/requests-docs-cn/commits/master/docs/user/quickstart.rst?author=Lukasa">
      <img class="avatar mr-1" src="https://avatars0.githubusercontent.com/u/1382556?s=40&amp;v=4" width="20" height="20" alt="@Lukasa" /> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=31764" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/requests/requests-docs-cn/commits/master/docs/user/quickstart.rst?author=gastlygem">
      <img class="avatar mr-1" src="https://avatars1.githubusercontent.com/u/31764?s=40&amp;v=4" width="20" height="20" alt="@gastlygem" /> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=503584" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/requests/requests-docs-cn/commits/master/docs/user/quickstart.rst?author=joequery">
      <img class="avatar mr-1" src="https://avatars1.githubusercontent.com/u/503584?s=40&amp;v=4" width="20" height="20" alt="@joequery" /> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=2456854" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/requests/requests-docs-cn/commits/master/docs/user/quickstart.rst?author=mapleray">
      <img class="avatar mr-1" src="https://avatars2.githubusercontent.com/u/2456854?s=40&amp;v=4" width="20" height="20" alt="@mapleray" /> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=542728" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/requests/requests-docs-cn/commits/master/docs/user/quickstart.rst?author=dicato">
      <img class="avatar mr-1" src="https://avatars2.githubusercontent.com/u/542728?s=40&amp;v=4" width="20" height="20" alt="@dicato" /> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=834231" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/requests/requests-docs-cn/commits/master/docs/user/quickstart.rst?author=youngsterxyf">
      <img class="avatar mr-1" src="https://avatars1.githubusercontent.com/u/834231?s=40&amp;v=4" width="20" height="20" alt="@youngsterxyf" /> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=20295772" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/requests/requests-docs-cn/commits/master/docs/user/quickstart.rst?author=CarGod">
      <img class="avatar mr-1" src="https://avatars1.githubusercontent.com/u/20295772?s=40&amp;v=4" width="20" height="20" alt="@CarGod" /> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=22723" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/requests/requests-docs-cn/commits/master/docs/user/quickstart.rst?author=idan">
      <img class="avatar mr-1" src="https://avatars2.githubusercontent.com/u/22723?s=40&amp;v=4" width="20" height="20" alt="@idan" /> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=240830" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/requests/requests-docs-cn/commits/master/docs/user/quickstart.rst?author=sigmavirus24">
      <img class="avatar mr-1" src="https://avatars2.githubusercontent.com/u/240830?s=40&amp;v=4" width="20" height="20" alt="@sigmavirus24" /> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=105168" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/requests/requests-docs-cn/commits/master/docs/user/quickstart.rst?author=dbrgn">
      <img class="avatar mr-1" src="https://avatars0.githubusercontent.com/u/105168?s=40&amp;v=4" width="20" height="20" alt="@dbrgn" /> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=15180122" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/requests/requests-docs-cn/commits/master/docs/user/quickstart.rst?author=houbaron">
      <img class="avatar mr-1" src="https://avatars1.githubusercontent.com/u/15180122?s=40&amp;v=4" width="20" height="20" alt="@houbaron" /> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=7036121" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/requests/requests-docs-cn/commits/master/docs/user/quickstart.rst?author=Windfarer">
      <img class="avatar mr-1" src="https://avatars3.githubusercontent.com/u/7036121?s=40&amp;v=4" width="20" height="20" alt="@Windfarer" /> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=376448" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/requests/requests-docs-cn/commits/master/docs/user/quickstart.rst?author=slingamn">
      <img class="avatar mr-1" src="https://avatars2.githubusercontent.com/u/376448?s=40&amp;v=4" width="20" height="20" alt="@slingamn" /> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=1530877" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/requests/requests-docs-cn/commits/master/docs/user/quickstart.rst?author=kayzhu">
      <img class="avatar mr-1" src="https://avatars1.githubusercontent.com/u/1530877?s=40&amp;v=4" width="20" height="20" alt="@kayzhu" /> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=9845170" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/requests/requests-docs-cn/commits/master/docs/user/quickstart.rst?author=lzskyline">
      <img class="avatar mr-1" src="https://avatars1.githubusercontent.com/u/9845170?s=40&amp;v=4" width="20" height="20" alt="@lzskyline" /> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=505230" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/requests/requests-docs-cn/commits/master/docs/user/quickstart.rst?author=karlcow">
      <img class="avatar mr-1" src="https://avatars1.githubusercontent.com/u/505230?s=40&amp;v=4" width="20" height="20" alt="@karlcow" /> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=58618" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/requests/requests-docs-cn/commits/master/docs/user/quickstart.rst?author=kisielk">
      <img class="avatar mr-1" src="https://avatars1.githubusercontent.com/u/58618?s=40&amp;v=4" width="20" height="20" alt="@kisielk" /> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=94069" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/requests/requests-docs-cn/commits/master/docs/user/quickstart.rst?author=JDrosdeck">
      <img class="avatar mr-1" src="https://avatars2.githubusercontent.com/u/94069?s=40&amp;v=4" width="20" height="20" alt="@JDrosdeck" /> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=33829" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/requests/requests-docs-cn/commits/master/docs/user/quickstart.rst?author=edsu">
      <img class="avatar mr-1" src="https://avatars1.githubusercontent.com/u/33829?s=40&amp;v=4" width="20" height="20" alt="@edsu" /> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=147840" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/requests/requests-docs-cn/commits/master/docs/user/quickstart.rst?author=anentropic">
      <img class="avatar mr-1" src="https://avatars0.githubusercontent.com/u/147840?s=40&amp;v=4" width="20" height="20" alt="@anentropic" /> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=185043" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/requests/requests-docs-cn/commits/master/docs/user/quickstart.rst?author=davidfischer">
      <img class="avatar mr-1" src="https://avatars3.githubusercontent.com/u/185043?s=40&amp;v=4" width="20" height="20" alt="@davidfischer" /> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=26015" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/requests/requests-docs-cn/commits/master/docs/user/quickstart.rst?author=rmax">
      <img class="avatar mr-1" src="https://avatars1.githubusercontent.com/u/26015?s=40&amp;v=4" width="20" height="20" alt="@rmax" /> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=2891235" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/requests/requests-docs-cn/commits/master/docs/user/quickstart.rst?author=caizixian">
      <img class="avatar mr-1" src="https://avatars3.githubusercontent.com/u/2891235?s=40&amp;v=4" width="20" height="20" alt="@caizixian" /> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=31269" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/requests/requests-docs-cn/commits/master/docs/user/quickstart.rst?author=brutasse">
      <img class="avatar mr-1" src="https://avatars1.githubusercontent.com/u/31269?s=40&amp;v=4" width="20" height="20" alt="@brutasse" /> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=534177" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/requests/requests-docs-cn/commits/master/docs/user/quickstart.rst?author=bryanhelmig">
      <img class="avatar mr-1" src="https://avatars0.githubusercontent.com/u/534177?s=40&amp;v=4" width="20" height="20" alt="@bryanhelmig" /> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=503436" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/requests/requests-docs-cn/commits/master/docs/user/quickstart.rst?author=barberj">
      <img class="avatar mr-1" src="https://avatars3.githubusercontent.com/u/503436?s=40&amp;v=4" width="20" height="20" alt="@barberj" /> 
</a>
</span>

    </div>
  </div>





    <div class="Box mt-3 position-relative">
      
<div class="Box-header py-2 d-flex flex-column flex-shrink-0 flex-md-row flex-md-items-center">

  <div class="text-mono f6 flex-auto pr-3 flex-order-2 flex-md-order-1 mt-2 mt-md-0">
      564 lines (372 sloc)
      <span class="file-info-divider"></span>
    17.5 KB
  </div>

  <div class="d-flex py-1 py-md-0 flex-auto flex-order-1 flex-md-order-2 flex-sm-grow-0 flex-justify-between">

    <div class="BtnGroup">
      <a id="raw-url" class="btn btn-sm BtnGroup-item" href="/requests/requests-docs-cn/raw/master/docs/user/quickstart.rst">Raw</a>
        <a class="btn btn-sm js-update-url-with-hash BtnGroup-item" data-hotkey="b" href="/requests/requests-docs-cn/blame/master/docs/user/quickstart.rst">Blame</a>
      <a rel="nofollow" class="btn btn-sm BtnGroup-item" href="/requests/requests-docs-cn/commits/master/docs/user/quickstart.rst">History</a>
    </div>


    <div>
            <a class="btn-octicon tooltipped tooltipped-nw hide-sm"
               href="https://desktop.github.com"
               aria-label="Open this file in GitHub Desktop"
               data-ga-click="Repository, open with desktop, type:windows">
                <svg class="octicon octicon-device-desktop" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M15 2H1c-.55 0-1 .45-1 1v9c0 .55.45 1 1 1h5.34c-.25.61-.86 1.39-2.34 2h8c-1.48-.61-2.09-1.39-2.34-2H15c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm0 9H1V3h14v8z"/></svg>
            </a>

            <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="inline-form js-update-url-with-hash" action="/requests/requests-docs-cn/edit/master/docs/user/quickstart.rst" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="ZPi1ZUzLz/g2OB7qbVMFug5o8+3T5/sxSwQ/Myf8uoUk/DUeJU8yGV2o2ouy0kt0hyTYzcOPKepygH7lD5wwaA==" />
              <button class="btn-octicon tooltipped tooltipped-nw" type="submit"
                aria-label="Fork this project and edit the file" data-hotkey="e" data-disable-with>
                <svg class="octicon octicon-pencil" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M0 12v3h3l8-8-3-3-8 8zm3 2H1v-2h1v1h1v1zm10.3-9.3L12 6 9 3l1.3-1.3a.996.996 0 0 1 1.41 0l1.59 1.59c.39.39.39 1.02 0 1.41z"/></svg>
              </button>
</form>
          <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="inline-form" action="/requests/requests-docs-cn/delete/master/docs/user/quickstart.rst" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="6PHtT8UUYKABSr3Id49mQ0xU0hP2P4WpTT1S9yRWAjkwTeglpSSaC/C4WEauSEGw87v/I6tKp9Fqbfvc+Kt7Eg==" />
            <button class="btn-octicon btn-octicon-danger tooltipped tooltipped-nw" type="submit"
              aria-label="Fork this project and delete the file" data-disable-with>
              <svg class="octicon octicon-trashcan" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M11 2H9c0-.55-.45-1-1-1H5c-.55 0-1 .45-1 1H2c-.55 0-1 .45-1 1v1c0 .55.45 1 1 1v9c0 .55.45 1 1 1h7c.55 0 1-.45 1-1V5c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm-1 12H3V5h1v8h1V5h1v8h1V5h1v8h1V5h1v9zm1-10H2V3h9v1z"/></svg>
            </button>
</form>    </div>
  </div>
</div>




      
  <div id="readme" class="Box-body readme blob instapaper_body js-code-block-container">
    <article class="markdown-body entry-content p-3 p-md-6" itemprop="text"><h1><a id="user-content-快速上手" class="anchor" aria-hidden="true" href="#快速上手"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>快速上手</h1>
<pre>.. module:: requests.models

</pre>
<p>迫不及待了吗？本页内容为如何入门 Requests 提供了很好的指引。其假设你已经安装了 Requests。如果还没有，去<a href="#id2"><span id="user-content-id3">:ref:`安装 &lt;install&gt;`</span></a>一节看看吧。</p>
<p>首先，确认一下：</p>
<ul>
<li>Requests <a href="#id4"><span id="user-content-id5">:ref:`已安装 &lt;install&gt;`</span></a></li>
<li>Requests <a href="#id6"><span id="user-content-id7">:ref:`是最新的 &lt;updates&gt;`</span></a></li>
</ul>
<p>让我们从一些简单的示例开始吧。</p>
<a name="user-content-id8"></a>
<h2><a id="user-content-发送请求" class="anchor" aria-hidden="true" href="#发送请求"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>发送请求</h2>
<p>使用 Requests 发送网络请求非常简单。</p>
<p>一开始要导入 Requests 模块：</p>
<pre>&gt;&gt;&gt; import requests
</pre>
<p>然后，尝试获取某个网页。本例子中，我们来获取 Github 的公共时间线：</p>
<pre>&gt;&gt;&gt; r = requests.get('https://api.github.com/events')
</pre>
<p>现在，我们有一个名为 <code>r</code> 的 <a href="#id9"><span id="user-content-id10">:class:`Response &lt;requests.Response&gt;`</span></a>
对象。我们可以从这个对象中获取所有我们想要的信息。</p>
<p>Requests 简便的 API 意味着所有 HTTP 请求类型都是显而易见的。例如，你可以这样发送一个
HTTP POST 请求：</p>
<pre>&gt;&gt;&gt; r = requests.post('http://httpbin.org/post', data = {'key':'value'})
</pre>
<p>漂亮，对吧？那么其他 HTTP 请求类型：PUT，DELETE，HEAD 以及 OPTIONS 又是如何的呢？都是一样的简单：</p>
<pre>&gt;&gt;&gt; r = requests.put('http://httpbin.org/put', data = {'key':'value'})
&gt;&gt;&gt; r = requests.delete('http://httpbin.org/delete')
&gt;&gt;&gt; r = requests.head('http://httpbin.org/get')
&gt;&gt;&gt; r = requests.options('http://httpbin.org/get')
</pre>
<p>都很不错吧，但这也仅是 Requests 的冰山一角呢。</p>
<a name="user-content-url"></a>
<h2><a id="user-content-传递-url-参数" class="anchor" aria-hidden="true" href="#传递-url-参数"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>传递 URL 参数</h2>
<p>你也许经常想为 URL 的查询字符串(query string)传递某种数据。如果你是手工构建 URL，那么数据会以键/值对的形式置于 URL 中，跟在一个问号的后面。例如， <code>httpbin.org/get?key=val</code>。
Requests 允许你使用 <code>params</code> 关键字参数，以一个字符串字典来提供这些参数。举例来说，如果你想传递
<code>key1=value1</code> 和 <code>key2=value2</code> 到 <code>httpbin.org/get</code> ，那么你可以使用如下代码：</p>
<pre>&gt;&gt;&gt; payload = {'key1': 'value1', 'key2': 'value2'}
&gt;&gt;&gt; r = requests.get("http://httpbin.org/get", params=payload)
</pre>
<p>通过打印输出该 URL，你能看到 URL 已被正确编码：</p>
<pre>&gt;&gt;&gt; print(r.url)
http://httpbin.org/get?key2=value2&amp;key1=value1
</pre>
<p>注意字典里值为 <code>None</code> 的键都不会被添加到 URL 的查询字符串里。</p>
<p>你还可以将一个列表作为值传入：</p>
<pre>&gt;&gt;&gt; payload = {'key1': 'value1', 'key2': ['value2', 'value3']}

&gt;&gt;&gt; r = requests.get('http://httpbin.org/get', params=payload)
&gt;&gt;&gt; print(r.url)
http://httpbin.org/get?key1=value1&amp;key2=value2&amp;key2=value3
</pre>
<a name="user-content-id11"></a>
<h2><a id="user-content-响应内容" class="anchor" aria-hidden="true" href="#响应内容"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>响应内容</h2>
<p>我们能读取服务器响应的内容。再次以 GitHub 时间线为例：</p>
<pre>&gt;&gt;&gt; import requests
&gt;&gt;&gt; r = requests.get('https://api.github.com/events')
&gt;&gt;&gt; r.text
u'[{"repository":{"open_issues":0,"url":"https://github.com/...
</pre>
<p>Requests 会自动解码来自服务器的内容。大多数 unicode 字符集都能被无缝地解码。</p>
<p>请求发出后，Requests 会基于 HTTP 头部对响应的编码作出有根据的推测。当你访问 <code>r.text</code>
之时，Requests 会使用其推测的文本编码。你可以找出 Requests 使用了什么编码，并且能够使用
<code>r.encoding</code> 属性来改变它：</p>
<pre>&gt;&gt;&gt; r.encoding
'utf-8'
&gt;&gt;&gt; r.encoding = 'ISO-8859-1'
</pre>
<p>如果你改变了编码，每当你访问 <code>r.text</code> ，Request 都将会使用 <code>r.encoding</code>
的新值。你可能希望在使用特殊逻辑计算出文本的编码的情况下来修改编码。比如 HTTP 和 XML
自身可以指定编码。这样的话，你应该使用 <code>r.content</code> 来找到编码，然后设置 <code>r.encoding</code>
为相应的编码。这样就能使用正确的编码解析 <code>r.text</code> 了。</p>
<p>在你需要的情况下，Requests 也可以使用定制的编码。如果你创建了自己的编码，并使用
<code>codecs</code> 模块进行注册，你就可以轻松地使用这个解码器名称作为 <code>r.encoding</code> 的值，
然后由 Requests 来为你处理编码。</p>
<a name="user-content-id12"></a>
<h2><a id="user-content-二进制响应内容" class="anchor" aria-hidden="true" href="#二进制响应内容"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>二进制响应内容</h2>
<p>你也能以字节的方式访问请求响应体，对于非文本请求：</p>
<pre>&gt;&gt;&gt; r.content
b'[{"repository":{"open_issues":0,"url":"https://github.com/...
</pre>
<p>Requests 会自动为你解码 <code>gzip</code> 和 <code>deflate</code> 传输编码的响应数据。</p>
<p>例如，以请求返回的二进制数据创建一张图片，你可以使用如下代码：</p>
<pre>&gt;&gt;&gt; from PIL import Image
&gt;&gt;&gt; from io import BytesIO

&gt;&gt;&gt; i = Image.open(BytesIO(r.content))
</pre>
<a name="user-content-json"></a>
<h2><a id="user-content-json-响应内容" class="anchor" aria-hidden="true" href="#json-响应内容"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>JSON 响应内容</h2>
<p>Requests 中也有一个内置的 JSON 解码器，助你处理 JSON 数据：</p>
<pre>&gt;&gt;&gt; import requests

&gt;&gt;&gt; r = requests.get('https://api.github.com/events')
&gt;&gt;&gt; r.json()
[{u'repository': {u'open_issues': 0, u'url': 'https://github.com/...
</pre>
<p>如果 JSON 解码失败， <code>r.json()</code> 就会抛出一个异常。例如，响应内容是 401 (Unauthorized)，尝试访问 <code>r.json()</code> 将会抛出 <code>ValueError: No JSON object could be decoded</code> 异常。</p>
<p>需要注意的是，成功调用 <code>r.json()</code> 并**不**意味着响应的成功。有的服务器会在失败的响应中包含一个 JSON 对象（比如 HTTP 500 的错误细节）。这种 JSON 会被解码返回。要检查请求是否成功，请使用 <code>r.raise_for_status()</code> 或者检查 <code>r.status_code</code> 是否和你的期望相同。</p>
<a name="user-content-id13"></a>
<h2><a id="user-content-原始响应内容" class="anchor" aria-hidden="true" href="#原始响应内容"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>原始响应内容</h2>
<p>在罕见的情况下，你可能想获取来自服务器的原始套接字响应，那么你可以访问 <code>r.raw</code>。
如果你确实想这么干，那请你确保在初始请求中设置了 <code>stream=True</code>。具体你可以这么做：</p>
<pre>&gt;&gt;&gt; r = requests.get('https://api.github.com/events', stream=True)
&gt;&gt;&gt; r.raw
&lt;requests.packages.urllib3.response.HTTPResponse object at 0x101194810&gt;
&gt;&gt;&gt; r.raw.read(10)
'\x1f\x8b\x08\x00\x00\x00\x00\x00\x00\x03'
</pre>
<p>但一般情况下，你应该以下面的模式将文本流保存到文件：</p>
<pre>with open(filename, 'wb') as fd:
    for chunk in r.iter_content(chunk_size):
        fd.write(chunk)
</pre>
<p>使用 <code>Response.iter_content</code> 将会处理大量你直接使用 <code>Response.raw</code> 不得不处理的。
当流下载时，上面是优先推荐的获取内容方式。 Note that <code>chunk_size</code> can be freely adjusted to a number that
may better fit your use cases.</p>
<a name="user-content-id14"></a>
<h2><a id="user-content-定制请求头" class="anchor" aria-hidden="true" href="#定制请求头"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>定制请求头</h2>
<p>如果你想为请求添加 HTTP 头部，只要简单地传递一个 <code>dict</code> 给 <code>headers</code> 参数就可以了。</p>
<p>例如，在前一个示例中我们没有指定 content-type:</p>
<pre>&gt;&gt;&gt; url = 'https://api.github.com/some/endpoint'
&gt;&gt;&gt; headers = {'user-agent': 'my-app/0.0.1'}

&gt;&gt;&gt; r = requests.get(url, headers=headers)
</pre>
<p>注意: 定制 header 的优先级低于某些特定的信息源，例如：</p>
<ul>
<li>如果在 <code>.netrc</code> 中设置了用户认证信息，使用 headers= 设置的授权就不会生效。而如果设置了
<code>auth=</code> 参数，``.netrc`` 的设置就无效了。</li>
<li>如果被重定向到别的主机，授权 header 就会被删除。</li>
<li>代理授权 header 会被 URL 中提供的代理身份覆盖掉。</li>
<li>在我们能判断内容长度的情况下，header 的 Content-Length 会被改写。</li>
</ul>
<p>更进一步讲，Requests 不会基于定制 header 的具体情况改变自己的行为。只不过在最后的请求中，所有的
header 信息都会被传递进去。</p>
<p>注意: 所有的 header 值必须是 <code>string</code>、bytestring 或者 unicode。尽管传递 unicode
header 也是允许的，但不建议这样做。</p>
<a name="user-content-post"></a>
<h2><a id="user-content-更加复杂的-post-请求" class="anchor" aria-hidden="true" href="#更加复杂的-post-请求"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>更加复杂的 POST 请求</h2>
<p>通常，你想要发送一些编码为表单形式的数据——非常像一个 HTML 表单。要实现这个，只需简单地传递一个字典给 data 参数。你的数据字典在发出请求时会自动编码为表单形式：</p>
<pre>&gt;&gt;&gt; payload = {'key1': 'value1', 'key2': 'value2'}

&gt;&gt;&gt; r = requests.post("http://httpbin.org/post", data=payload)
&gt;&gt;&gt; print(r.text)
{
  ...
  "form": {
    "key2": "value2",
    "key1": "value1"
  },
  ...
}
</pre>
<p>你还可以为 <code>data</code> 参数传入一个元组列表。在表单中多个元素使用同一 key 的时候，这种方式尤其有效：</p>
<pre>&gt;&gt;&gt; payload = (('key1', 'value1'), ('key1', 'value2'))
&gt;&gt;&gt; r = requests.post('http://httpbin.org/post', data=payload)
&gt;&gt;&gt; print(r.text)
{
  ...
  "form": {
    "key1": [
      "value1",
      "value2"
    ]
  },
  ...
}
</pre>
<p>很多时候你想要发送的数据并非编码为表单形式的。如果你传递一个 <code>string</code> 而不是一个 <code>dict</code>，那么数据会被直接发布出去。</p>
<p>例如，Github API v3 接受编码为 JSON 的 POST/PATCH 数据：</p>
<pre>&gt;&gt;&gt; import json

&gt;&gt;&gt; url = 'https://api.github.com/some/endpoint'
&gt;&gt;&gt; payload = {'some': 'data'}

&gt;&gt;&gt; r = requests.post(url, data=json.dumps(payload))
</pre>
<p>此处除了可以自行对 <code>dict</code> 进行编码，你还可以使用 <code>json</code> 参数直接传递，然后它就会被自动编码。这是 2.4.2 版的新加功能：</p>
<pre>&gt;&gt;&gt; url = 'https://api.github.com/some/endpoint'
&gt;&gt;&gt; payload = {'some': 'data'}

&gt;&gt;&gt; r = requests.post(url, json=payload)
</pre>
<a name="user-content-post-multipart-encoded"></a>
<h2><a id="user-content-post一个多部分编码multipart-encoded的文件" class="anchor" aria-hidden="true" href="#post一个多部分编码multipart-encoded的文件"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>POST一个多部分编码(Multipart-Encoded)的文件</h2>
<p>Requests 使得上传多部分编码文件变得很简单：</p>
<pre>&gt;&gt;&gt; url = 'http://httpbin.org/post'
&gt;&gt;&gt; files = {'file': open('report.xls', 'rb')}

&gt;&gt;&gt; r = requests.post(url, files=files)
&gt;&gt;&gt; r.text
{
  ...
  "files": {
    "file": "&lt;censored...binary...data&gt;"
  },
  ...
}
</pre>
<p>你可以显式地设置文件名，文件类型和请求头：</p>
<pre>&gt;&gt;&gt; url = 'http://httpbin.org/post'
&gt;&gt;&gt; files = {'file': ('report.xls', open('report.xls', 'rb'), 'application/vnd.ms-excel', {'Expires': '0'})}

&gt;&gt;&gt; r = requests.post(url, files=files)
&gt;&gt;&gt; r.text
{
  ...
  "files": {
    "file": "&lt;censored...binary...data&gt;"
  },
  ...
}
</pre>
<p>如果你想，你也可以发送作为文件来接收的字符串：</p>
<pre>&gt;&gt;&gt; url = 'http://httpbin.org/post'
&gt;&gt;&gt; files = {'file': ('report.csv', 'some,data,to,send\nanother,row,to,send\n')}

&gt;&gt;&gt; r = requests.post(url, files=files)
&gt;&gt;&gt; r.text
{
  ...
  "files": {
    "file": "some,data,to,send\\nanother,row,to,send\\n"
  },
  ...
}
</pre>
<p>如果你发送一个非常大的文件作为 <code>multipart/form-data</code> 请求，你可能希望将请求做成数据流。默认下 <code>requests</code> 不支持, 但有个第三方包 <code>requests-toolbelt</code> 是支持的。你可以阅读
<a href="https://toolbelt.rtfd.org" rel="nofollow">toolbelt 文档</a> 来了解使用方法。</p>
<p>在一个请求中发送多文件参考 <a href="#id15"><span id="user-content-id16">:ref:`高级用法 &lt;advanced&gt;`</span></a> 一节。</p>
<div>
<p>警告</p>
<p>我们强烈建议你用二进制模式(<a href="https://docs.python.org/2/tutorial/inputoutput.html#reading-and-writing-files" rel="nofollow">binary mode</a>)打开文件。这是因为 Requests 可能会试图为你提供
<code>Content-Length</code> header，在它这样做的时候，这个值会被设为文件的字节数（<em>bytes</em>）。如果用文本模式(text mode)打开文件，就可能会发生错误。</p>
</div>
<a name="user-content-id17"></a>
<h2><a id="user-content-响应状态码" class="anchor" aria-hidden="true" href="#响应状态码"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>响应状态码</h2>
<p>我们可以检测响应状态码：</p>
<pre>&gt;&gt;&gt; r = requests.get('http://httpbin.org/get')
&gt;&gt;&gt; r.status_code
200
</pre>
<p>为方便引用，Requests还附带了一个内置的状态码查询对象：</p>
<pre>&gt;&gt;&gt; r.status_code == requests.codes.ok
True
</pre>
<p>如果发送了一个错误请求(一个 4XX 客户端错误，或者 5XX 服务器错误响应)，我们可以通过
<a href="#id18"><span id="user-content-id19">:meth:`Response.raise_for_status() &lt;requests.Response.raise_for_status&gt;`</span></a>
来抛出异常：</p>
<pre>&gt;&gt;&gt; bad_r = requests.get('http://httpbin.org/status/404')
&gt;&gt;&gt; bad_r.status_code
404

&gt;&gt;&gt; bad_r.raise_for_status()
Traceback (most recent call last):
  File "requests/models.py", line 832, in raise_for_status
    raise http_error
requests.exceptions.HTTPError: 404 Client Error
</pre>
<p>但是，由于我们的例子中 <code>r</code> 的 <code>status_code</code> 是 <code>200</code> ，当我们调用
<code>raise_for_status()</code> 时，得到的是：</p>
<pre>&gt;&gt;&gt; r.raise_for_status()
None
</pre>
<p>一切都挺和谐哈。</p>
<a name="user-content-id20"></a>
<h2><a id="user-content-响应头" class="anchor" aria-hidden="true" href="#响应头"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>响应头</h2>
<p>我们可以查看以一个 Python 字典形式展示的服务器响应头：</p>
<pre>&gt;&gt;&gt; r.headers
{
    'content-encoding': 'gzip',
    'transfer-encoding': 'chunked',
    'connection': 'close',
    'server': 'nginx/1.0.4',
    'x-runtime': '148ms',
    'etag': '"e1ca502697e5c9317743dc078f67693f"',
    'content-type': 'application/json'
}
</pre>
<p>但是这个字典比较特殊：它是仅为 HTTP 头部而生的。根据
<a href="http://www.w3.org/Protocols/rfc2616/rfc2616-sec14.html" rel="nofollow">RFC 2616</a>，
HTTP 头部是大小写不敏感的。</p>
<p>因此，我们可以使用任意大写形式来访问这些响应头字段：</p>
<pre>&gt;&gt;&gt; r.headers['Content-Type']
'application/json'

&gt;&gt;&gt; r.headers.get('content-type')
'application/json'
</pre>
<p>它还有一个特殊点，那就是服务器可以多次接受同一 header，每次都使用不同的值。但 Requests
会将它们合并，这样它们就可以用一个映射来表示出来，参见
<a href="http://tools.ietf.org/html/rfc7230#section-3.2" rel="nofollow">RFC 7230</a>:</p>
<blockquote>
<p>A recipient MAY combine multiple header fields with the same field name
into one "field-name: field-value" pair, without changing the semantics
of the message, by appending each subsequent field value to the combined
field value in order, separated by a comma.</p>
<p>接收者可以合并多个相同名称的 header 栏位，把它们合为一个 "field-name: field-value"
配对，将每个后续的栏位值依次追加到合并的栏位值中，用逗号隔开即可，这样做不会改变信息的语义。</p>
</blockquote>
<a name="user-content-cookie"></a>
<h2><a id="user-content-cookie" class="anchor" aria-hidden="true" href="#cookie"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Cookie</h2>
<p>如果某个响应中包含一些 cookie，你可以快速访问它们：</p>
<pre>&gt;&gt;&gt; url = 'http://example.com/some/cookie/setting/url'
&gt;&gt;&gt; r = requests.get(url)

&gt;&gt;&gt; r.cookies['example_cookie_name']
'example_cookie_value'
</pre>
<p>要想发送你的cookies到服务器，可以使用 <code>cookies</code> 参数：</p>
<pre>&gt;&gt;&gt; url = 'http://httpbin.org/cookies'
&gt;&gt;&gt; cookies = dict(cookies_are='working')

&gt;&gt;&gt; r = requests.get(url, cookies=cookies)
&gt;&gt;&gt; r.text
'{"cookies": {"cookies_are": "working"}}'
</pre>
<p>Cookie 的返回对象为 <a href="#id21"><span id="user-content-id22">:class:`~requests.cookies.RequestsCookieJar`</span></a>，它的行为和字典类似，但接口更为完整，适合跨域名跨路径使用。你还可以把 Cookie Jar 传到 Requests 中：</p>
<pre>&gt;&gt;&gt; jar = requests.cookies.RequestsCookieJar()
&gt;&gt;&gt; jar.set('tasty_cookie', 'yum', domain='httpbin.org', path='/cookies')
&gt;&gt;&gt; jar.set('gross_cookie', 'blech', domain='httpbin.org', path='/elsewhere')
&gt;&gt;&gt; url = 'http://httpbin.org/cookies'
&gt;&gt;&gt; r = requests.get(url, cookies=jar)
&gt;&gt;&gt; r.text
'{"cookies": {"tasty_cookie": "yum"}}'
</pre>
<a name="user-content-id23"></a>
<h2><a id="user-content-重定向与请求历史" class="anchor" aria-hidden="true" href="#重定向与请求历史"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>重定向与请求历史</h2>
<p>默认情况下，除了 HEAD, Requests 会自动处理所有重定向。</p>
<p>可以使用响应对象的 <code>history</code> 方法来追踪重定向。</p>
<p><a href="#id24"><span id="user-content-id25">:attr:`Response.history &lt;requests.Response.history&gt;`</span></a> 是一个
<a href="#id26"><span id="user-content-id27">:class:`Response &lt;requests.Response&gt;`</span></a> 对象的列表，为了完成请求而创建了这些对象。这个对象列表按照从最老到最近的请求进行排序。</p>
<p>例如，Github 将所有的 HTTP 请求重定向到 HTTPS：</p>
<pre>&gt;&gt;&gt; r = requests.get('http://github.com')

&gt;&gt;&gt; r.url
'https://github.com/'

&gt;&gt;&gt; r.status_code
200

&gt;&gt;&gt; r.history
[&lt;Response [301]&gt;]
</pre>
<p>如果你使用的是GET、OPTIONS、POST、PUT、PATCH 或者 DELETE，那么你可以通过 <code>allow_redirects</code>
参数禁用重定向处理：</p>
<pre>&gt;&gt;&gt; r = requests.get('http://github.com', allow_redirects=False)
&gt;&gt;&gt; r.status_code
301
&gt;&gt;&gt; r.history
[]
</pre>
<p>如果你使用了 HEAD，你也可以启用重定向：</p>
<pre>&gt;&gt;&gt; r = requests.head('http://github.com', allow_redirects=True)
&gt;&gt;&gt; r.url
'https://github.com/'
&gt;&gt;&gt; r.history
[&lt;Response [301]&gt;]
</pre>
<a name="user-content-id28"></a>
<h2><a id="user-content-超时" class="anchor" aria-hidden="true" href="#超时"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>超时</h2>
<p>你可以告诉 requests 在经过以 <code>timeout</code> 参数设定的秒数时间之后停止等待响应。基本上所有的生产代码都应该使用这一参数。如果不使用，你的程序可能会永远失去响应：</p>
<pre>&gt;&gt;&gt; requests.get('http://github.com', timeout=0.001)
Traceback (most recent call last):
  File "&lt;stdin&gt;", line 1, in &lt;module&gt;
requests.exceptions.Timeout: HTTPConnectionPool(host='github.com', port=80): Request timed out. (timeout=0.001)
</pre>
<div>
<p>注意</p>
<p><code>timeout</code> 仅对连接过程有效，与响应体的下载无关。 <code>timeout</code> 并不是整个下载响应的时间限制，而是如果服务器在 <code>timeout</code> 秒内没有应答，将会引发一个异常（更精确地说，是在
<code>timeout</code> 秒内没有从基础套接字上接收到任何字节的数据时）If no timeout is specified explicitly, requests do
not time out.</p>
</div>
<a name="user-content-id29"></a>
<h2><a id="user-content-错误与异常" class="anchor" aria-hidden="true" href="#错误与异常"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>错误与异常</h2>
<p>遇到网络问题（如：DNS 查询失败、拒绝连接等）时，Requests 会抛出一个
<a href="#id30"><span id="user-content-id31">:exc:`~requests.exceptions.ConnectionError`</span></a> 异常。</p>
<p>如果 HTTP 请求返回了不成功的状态码， <a href="#id32"><span id="user-content-id33">:meth:`Response.raise_for_status() &lt;requests.Response.raise_for_status&gt;`</span></a>
会抛出一个 <a href="#id34"><span id="user-content-id35">:exc:`~requests.exceptions.HTTPError`</span></a> 异常。</p>
<p>若请求超时，则抛出一个 <a href="#id36"><span id="user-content-id37">:exc:`~requests.exceptions.Timeout`</span></a> 异常。</p>
<p>若请求超过了设定的最大重定向次数，则会抛出一个 <a href="#id38"><span id="user-content-id39">:exc:`~requests.exceptions.TooManyRedirects`</span></a> 异常。</p>
<p>所有Requests显式抛出的异常都继承自 <a href="#id40"><span id="user-content-id41">:exc:`requests.exceptions.RequestException`</span></a> 。</p>
<hr>
<p>准备好学习更多内容了吗？去 <a href="#id42"><span id="user-content-id43">:ref:`高级用法 &lt;advanced&gt;`</span></a> 一节看看吧。</p>

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
      <li class="mr-3 mr-lg-0">&copy; 2019 <span title="0.53700s from unicorn-7685555bfd-dszzc">GitHub</span>, Inc.</li>
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

