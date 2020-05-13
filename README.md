## test

Blah


### test
function initializeViz() {
  // JS object that points at empty div in the html
  var placeholderDiv = document.getElementById("tableauViz");
  // URL of the viz to be embedded
  var url = "http://public.tableau.com/views/WorldIndicators/GDPpercapita";
  // An object that contains options specifying how to embed the viz
  var options = {
    width: '600px',
    height: '600px',
    hideTabs: true,
    hideToolbar: true,
  };
  viz = new tableau.Viz(placeholderDiv, url, options);
}

### test
<iframe src="https://public.tableau.com/views/COVID-19CommunityProfilesMay11/Dashboard1?:embed=y&:display_count=y&publish=yes&:origin=viz_share_link"
 width="645" height="955"></iframe>
