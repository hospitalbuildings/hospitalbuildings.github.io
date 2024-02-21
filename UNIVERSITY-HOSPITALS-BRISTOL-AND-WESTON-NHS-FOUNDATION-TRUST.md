<!DOCTYPE html>

<html>

<head>

<meta charset="utf-8" />
<meta name="generator" content="pandoc" />
<meta http-equiv="X-UA-Compatible" content="IE=EDGE" />




<title>01templateBYTRUST.knit</title>

<script src="libs/header-attrs-2.19/header-attrs.js"></script>
<script src="libs/jquery-3.6.0/jquery-3.6.0.min.js"></script>
<meta name="viewport" content="width=device-width, initial-scale=1" />
<link href="libs/bootstrap-3.3.5/css/bootstrap.min.css" rel="stylesheet" />
<script src="libs/bootstrap-3.3.5/js/bootstrap.min.js"></script>
<script src="libs/bootstrap-3.3.5/shim/html5shiv.min.js"></script>
<script src="libs/bootstrap-3.3.5/shim/respond.min.js"></script>
<style>h1 {font-size: 34px;}
       h1.title {font-size: 38px;}
       h2 {font-size: 30px;}
       h3 {font-size: 24px;}
       h4 {font-size: 18px;}
       h5 {font-size: 16px;}
       h6 {font-size: 12px;}
       code {color: inherit; background-color: rgba(0, 0, 0, 0.04);}
       pre:not([class]) { background-color: white }</style>
<script src="libs/navigation-1.1/tabsets.js"></script>
<link href="libs/highlightjs-9.12.0/default.css" rel="stylesheet" />
<script src="libs/highlightjs-9.12.0/highlight.js"></script>
<script src="libs/htmlwidgets-1.6.1/htmlwidgets.js"></script>
<link href="libs/datatables-css-0.0.0/datatables-crosstalk.css" rel="stylesheet" />
<script src="libs/datatables-binding-0.27/datatables.js"></script>
<link href="libs/dt-core-bootstrap-1.12.1/css/dataTables.bootstrap.min.css" rel="stylesheet" />
<link href="libs/dt-core-bootstrap-1.12.1/css/dataTables.bootstrap.extra.css" rel="stylesheet" />
<script src="libs/dt-core-bootstrap-1.12.1/js/jquery.dataTables.min.js"></script>
<script src="libs/dt-core-bootstrap-1.12.1/js/dataTables.bootstrap.min.js"></script>
<link href="libs/nouislider-7.0.10/jquery.nouislider.min.css" rel="stylesheet" />
<script src="libs/nouislider-7.0.10/jquery.nouislider.min.js"></script>
<link href="libs/selectize-0.12.0/selectize.bootstrap3.css" rel="stylesheet" />
<script src="libs/selectize-0.12.0/selectize.min.js"></script>
<link href="libs/crosstalk-1.2.0/css/crosstalk.min.css" rel="stylesheet" />
<script src="libs/crosstalk-1.2.0/js/crosstalk.min.js"></script>
<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-QE0LKSXVLK"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-QE0LKSXVLK');
</script>

<style type="text/css">
  code{white-space: pre-wrap;}
  span.smallcaps{font-variant: small-caps;}
  span.underline{text-decoration: underline;}
  div.column{display: inline-block; vertical-align: top; width: 50%;}
  div.hanging-indent{margin-left: 1.5em; text-indent: -1.5em;}
  ul.task-list{list-style: none;}
    </style>

<style type="text/css">code{white-space: pre;}</style>
<script type="text/javascript">
if (window.hljs) {
  hljs.configure({languages: []});
  hljs.initHighlightingOnLoad();
  if (document.readyState && document.readyState === "complete") {
    window.setTimeout(function() { hljs.initHighlighting(); }, 0);
  }
}
</script>









<style type = "text/css">
.main-container {
  max-width: 940px;
  margin-left: auto;
  margin-right: auto;
}
img {
  max-width:100%;
}
.tabbed-pane {
  padding-top: 12px;
}
.html-widget {
  margin-bottom: 20px;
}
button.code-folding-btn:focus {
  outline: none;
}
summary {
  display: list-item;
}
details > summary > p:only-child {
  display: inline;
}
pre code {
  padding: 0;
}
</style>



<!-- tabsets -->

<style type="text/css">
.tabset-dropdown > .nav-tabs {
  display: inline-table;
  max-height: 500px;
  min-height: 44px;
  overflow-y: auto;
  border: 1px solid #ddd;
  border-radius: 4px;
}

.tabset-dropdown > .nav-tabs > li.active:before, .tabset-dropdown > .nav-tabs.nav-tabs-open:before {
  content: "\e259";
  font-family: 'Glyphicons Halflings';
  display: inline-block;
  padding: 10px;
  border-right: 1px solid #ddd;
}

.tabset-dropdown > .nav-tabs.nav-tabs-open > li.active:before {
  content: "\e258";
  font-family: 'Glyphicons Halflings';
  border: none;
}

.tabset-dropdown > .nav-tabs > li.active {
  display: block;
}

.tabset-dropdown > .nav-tabs > li > a,
.tabset-dropdown > .nav-tabs > li > a:focus,
.tabset-dropdown > .nav-tabs > li > a:hover {
  border: none;
  display: inline-block;
  border-radius: 4px;
  background-color: transparent;
}

.tabset-dropdown > .nav-tabs.nav-tabs-open > li {
  display: block;
  float: none;
}

.tabset-dropdown > .nav-tabs > li {
  display: none;
}
</style>

<!-- code folding -->




</head>

<body>


<div class="container-fluid main-container">




<div id="header">



<h1 class="title toc-ignore"><p><img
src="https://raw.githubusercontent.com/sduiopc/test1/branch1/LNP%20Header-01.jpg"
style="width:40.0%" align="right" /></p></h1>

</div>


<div id="university-hospitals-bristol-and-weston-nhs-foundation-trust"
class="section level1">
<h1>University Hospitals Bristol And Weston NHS Foundation Trust</h1>
<p>The cost of general acute hospital repairs backlogs at
<strong>University Hospitals Bristol And Weston NHS Foundation
Trust</strong> has <strong>fallen 5.7%</strong> from £69,605,792 to
£65,658,520 in the last financial year, according to analysis of <a
href="https://digital.nhs.uk/data-and-information/publications/statistical/estates-returns-information-collection/england-2022-23">data
released by NHS Digital</a>.</p>
<p>The backlog of high-risk repair costs has also fallen
<strong>68.4%</strong> from £171,017 to £54,059.</p>
<p>At a national level the high risk repairs backlog has risen more than
a third in the last year to £2,078,970,702, while the overall repairs
backlog has risen 8.7% to £9,509,161,437 (figures adjusted for
inflation).</p>
<p>In 2022-23, there were 9 “clinical service incidents caused by
estates and infrastructure failure,” a drop compared to 24 such
incidents in 2021-22.</p>
<p>Clinical service incidents are defined as those leading to “services
being delayed, cancelled or otherwise interfered with owing to problems
or failures related to the estates and infrastructure failure.” An
incident is “considered to be a delay of at least 30 minutes to clinical
services affecting at least 5 patients or equivalent.”</p>
<p>Incidents include problems with electrical, water or ventilation
systems, internal fabric and fixtures, roofs and structures, or lifts
and hoists. See the table at the bottom of this page for a list of the
top three most impactful categories of incident reported by each
hospital, where applicable.</p>
<div id="explore-the-data" class="section level2">
<h2>Explore the data</h2>
<p><img src="UNIVERSITY-HOSPITALS-BRISTOL-AND-WESTON-NHS-FOUNDATION-TRUST_files/figure-html/stacked%20bar%20chart-1.png" width="672" /></p>
</div>
<div id="explore-general-acute-hospitals-in-this-trust"
class="section level2">
<h2>Explore general acute hospitals in this trust</h2>
<p>The interactive table below shows the cost to eradicate the repairs
backlog at all four levels of risk at general acute hospital sites in
<strong>University Hospitals Bristol And Weston NHS Foundation
Trust</strong>. Click on the column titles once to sort by that column,
smallest to largest, and again to sort largest to smallest. Type into
the boxes above each column to filter to results containing the keyword
being typed.</p>
<div class="datatables html-widget html-fill-item-overflow-hidden html-fill-item" id="htmlwidget-aa9b37f125c02636e239" style="width:100%;height:auto;"></div>
<script type="application/json" data-for="htmlwidget-aa9b37f125c02636e239">{"x":{"style":"bootstrap","filter":"top","vertical":false,"filterHTML":"<tr>\n  <td><\/td>\n  <td data-type=\"character\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n  <\/td>\n  <td data-type=\"character\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n  <\/td>\n  <td data-type=\"character\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\" disabled=\"\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n  <\/td>\n  <td data-type=\"character\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n  <\/td>\n  <td data-type=\"character\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n  <\/td>\n  <td data-type=\"character\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n  <\/td>\n<\/tr>","caption":"<caption>Total backlog repair costs at each site (all risk levels)<\/caption>","data":[["1","2"],["BRISTOL ROYAL INFIRMARY","WESTON GENERAL HOSPITAL"],["£26,926,141","£0"],["£0","£0"],["£55,868,385","£25,382,845"],["£47,255,974","£22,349,818"],["£45,646,635","£20,011,885"]],"container":"<table class=\"table table-striped table-hover row-border order-column display\">\n  <thead>\n    <tr>\n      <th> <\/th>\n      <th>Hospital name<\/th>\n      <th>201819<\/th>\n      <th>201920<\/th>\n      <th>202021<\/th>\n      <th>202122<\/th>\n      <th>202223<\/th>\n    <\/tr>\n  <\/thead>\n<\/table>","options":{"pageLength":10,"scrollX":true,"autoWidth":true,"order":[5,"desc"],"columnDefs":[{"orderable":false,"targets":0}],"orderClasses":false,"orderCellsTop":true}},"evals":[],"jsHooks":[]}</script>
</div>
<div id="explore-the-most-common-cause-of-incidents"
class="section level2">
<h2>Explore the most common cause of incidents</h2>
<p>The table below shows the most clinically impactful type of incident
at each hospital site in the trust. In some cases no reason is given, or
‘miscellaneous’ is selected.</p>
<div class="datatables html-widget html-fill-item-overflow-hidden html-fill-item" id="htmlwidget-ada858136db597ddf188" style="width:100%;height:auto;"></div>
<script type="application/json" data-for="htmlwidget-ada858136db597ddf188">{"x":{"style":"bootstrap","filter":"none","vertical":false,"caption":"<caption>Most clinically impactful incident types<\/caption>","data":[["1","2"],["BRISTOL ROYAL INFIRMARY","WESTON GENERAL HOSPITAL"],["Structure","Miscellaneous"],["Lifts & Hoists","Miscellaneous"],["Heating systems","Miscellaneous"]],"container":"<table class=\"table table-striped table-hover row-border order-column display\">\n  <thead>\n    <tr>\n      <th> <\/th>\n      <th>Hospital name<\/th>\n      <th>Most clinically impactful incident type<\/th>\n      <th>Second most clinically impactful incident type<\/th>\n      <th>Third most clinically impactful incident type<\/th>\n    <\/tr>\n  <\/thead>\n<\/table>","options":{"pageLength":10,"scrollX":true,"autoWidth":true,"order":[1,"desc"],"columnDefs":[{"orderable":false,"targets":0}],"orderClasses":false}},"evals":[],"jsHooks":[]}</script>
</div>
</div>




</div>

<script>

// add bootstrap table styles to pandoc tables
function bootstrapStylePandocTables() {
  $('tr.odd').parent('tbody').parent('table').addClass('table table-condensed');
}
$(document).ready(function () {
  bootstrapStylePandocTables();
});


</script>

<!-- tabsets -->

<script>
$(document).ready(function () {
  window.buildTabsets("TOC");
});

$(document).ready(function () {
  $('.tabset-dropdown > .nav-tabs > li').click(function () {
    $(this).parent().toggleClass('nav-tabs-open');
  });
});
</script>

<!-- code folding -->


<!-- dynamically load mathjax for compatibility with self-contained -->
<script>
  (function () {
    var script = document.createElement("script");
    script.type = "text/javascript";
    script.src  = "https://mathjax.rstudio.com/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML";
    document.getElementsByTagName("head")[0].appendChild(script);
  })();
</script>

</body>
</html>
