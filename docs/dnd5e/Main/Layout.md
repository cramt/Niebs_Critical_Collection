#Main
[[dnd5e/[include\|:css:csi:layout]]]

[[dnd5e/[code\|type="html"]]]
<!---------------------------------------------------------
  Standard Template Layout
  Developed by the Wikidot Community
  Version: 1.02.150114
---------------------------------------------------------->
<a name="page-top"></a>
[[dnd5e/[module\|NaviBar]]]
<div class="container-wrap-wrap">
<div class="container-wrap">
 
<header class="header-wrap" role="banner">
  <div class="container header">
    <div class="site-title">
      <h1><a href="/"><span>[[dnd5e/[site_name\|]]]</span></a></h1>
      [[dnd5e/[if\|site_subtitle]]]<h2><span>[[dnd5e/[site_subtitle\|]]]</span></h2>[[dnd5e/If\|]]]
    </div>
    <div class="login-status">
      [[dnd5e/[module\|LoginStatus]]]
    </div>
    [[dnd5e/[search_box\|]]]
  </div>
 
  [[dnd5e/[if\|topbar]]]
  <nav class="top-bar-wrap navbar navbar-default" role="navigation">
    <div class="container top-bar">
      <div class="navbar-header">
        <button type="button" class="navbar-toggle" data-toggle="collapse" data-target=".navbar-top-target">
          <span class="sr-only">Toggle navigation</span>
          <span class="icon-bar"></span>
          <span class="icon-bar"></span>
          <span class="icon-bar"></span>
        </button>
        <a class="navbar-brand" href="/">Home</a>
      </div>
      <div class="collapse navbar-collapse navbar-top-target">
        [[dnd5e/[topbar\|]]]
      </div>
    </div>
  </nav>
  [[dnd5e/If\|]]]
 
  <div class="header-extra-div-1"><span></span></div>
  <div class="header-extra-div-2"><span></span></div>
  <div class="header-extra-div-3"><span></span></div>
</header>
 
<main class="content-wrap" role="main">
  <div class="container content">
    <div class="row">
    [[dnd5e/[if\|sidebar]]]
      <nav class="side-bar-wrap col-md-3">
        <div class="side-bar">
          <div class="side-bar-header">
            <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target=".navbar-side-target">
              <span>Menu</span>
            </button>
          </div>
          <div class="collapse navbar-collapse navbar-side-target">
            [[dnd5e/[sidebar\|]]]
          </div>
        </div>
      </nav>
      [[dnd5e/If\|]]]
      [[dnd5e/[if\|sidebar]]]<div class="main-content-wrap col-md-9">
      [[dnd5e/[else\|]]]<div class="main-content-wrap col-md-12">[[dnd5e/If\|]]]
        <div class="main-content">
          <div class="page-title page-header"><span>[[dnd5e/[page_title\|]]]</span></div>
          [[dnd5e/[if\|breadcrumbs]]]<div class="breadcrumbs">[[dnd5e/[breadcrumbs\|]]]</div>[[dnd5e/If\|]]]
          [[dnd5e/[content\|]]]
          [[dnd5e/[if\|tags]]]<div class="page-tags">[[dnd5e/[tags\|]]]</div>[[dnd5e/If\|]]]
          <div class="page-info-break"></div>
          <div class="page-options-container">[[dnd5e/[module\|PageOptionsBottom]]]</div>
          [[dnd5e/[action_area\|]]]
        </div>
      </div>
    </div>
  </div>
</main>
 
<footer class="footer-wrap" role="contentinfo">
  <div class="container footer">
    [[dnd5e/[footer\|]]]
    <div class="license-area">[[dnd5e/[license_text\|]]]</div>
  </div>
  <div class="extrac-div-1"><span></span></div>
  <div class="extrac-div-2"><span></span></div>
  <div class="extrac-div-3"><span></span></div>
</footer>
 
[[dnd5e/[module\|FooterBar]]]
</div> <!-- container-wrap -->
 
<div class="extra-div-1"><span></span></div>
<div class="extra-div-2"><span></span></div>
<div class="extra-div-3"><span></span></div>
<div class="extra-div-4"><span></span></div>
<div class="extra-div-5"><span></span></div>
<div class="extra-div-6"><span></span></div>
</div> <!-- container-wrap-wrap -->
[[dnd5e/Code\|]]]