---
title: "Exploratory Data Analysis"
date: 2021-04-16T23:47:01+02:00
draft: true
weight: 2
---

Text about the plot

<script type="text/javascript" src="https://cdn.bokeh.org/bokeh/release/bokeh-2.3.1.min.js" integrity="sha384-YF85VygJKMVnHE+lLv2AM93Vbstr0yo2TbIu5v8se5Rq3UQAUmcuh4aaJwNlpKwa" crossorigin="anonymous"></script>
<script type="text/javascript">
            Bokeh.set_log_level("info");
</script>
<div class="bk-root" id="43409493-0834-4ab8-8224-45c14214eec9" data-root-id="6818">
</div>
<script type="application/json" id="7367">
          {"879fb4a5-d468-4ae7-919a-a4fe2cfe0b51":{"defs":[],"roots":{"references":[{"attributes":{"below":[{"id":"6828"}],"center":[{"id":"6830"},{"id":"6834"}],"height":500,"left":[{"id":"6831"}],"renderers":[{"id":"6853"}],"title":{"id":"6819"},"toolbar":{"id":"6842"},"toolbar_location":null,"x_range":{"id":"6817"},"x_scale":{"id":"6824"},"y_range":{"id":"6822"},"y_scale":{"id":"6826"}},"id":"6818","subtype":"Figure","type":"Plot"},{"attributes":{},"id":"7097","type":"CategoricalTickFormatter"},{"attributes":{"data_source":{"id":"6849"},"glyph":{"id":"6851"},"hover_glyph":null,"muted_glyph":null,"nonselection_glyph":{"id":"6852"},"view":{"id":"6854"}},"id":"6853","type":"GlyphRenderer"},{"attributes":{},"id":"6836","type":"WheelZoomTool"},{"attributes":{"data":{"cat_type":["Bars","Breakfast &amp; Brunch","Buffets","Burgers","Cafes","Coffee &amp; Tea","Diners","Fast Food","Food","Nightlife","Pizza","Salad","Sandwiches","Steakhouses","Sushi Bars","Vegetarian","Wine Bars"],"stars":[974350,497283,43833,244596,105476,117560,106299,100563,684773,997131,203438,180963,266517,137014,216243,149865,151418]},"selected":{"id":"7104"},"selection_policy":{"id":"7103"}},"id":"6849","type":"ColumnDataSource"},{"attributes":{},"id":"6822","type":"DataRange1d"},{"attributes":{"bottom_units":"screen","fill_alpha":0.5,"fill_color":"lightgrey","left_units":"screen","level":"overlay","line_alpha":1.0,"line_color":"black","line_dash":[4,4],"line_width":2,"right_units":"screen","syncable":false,"top_units":"screen"},"id":"6841","type":"BoxAnnotation"},{"attributes":{},"id":"7103","type":"UnionRenderers"},{"attributes":{"axis_label":"state","formatter":{"id":"7097"},"major_label_orientation":"vertical","major_label_policy":{"id":"7099"},"major_tick_line_color":null,"minor_tick_line_color":null,"ticker":{"id":"6829"}},"id":"6828","type":"CategoricalAxis"},{"attributes":{"axis":{"id":"6831"},"dimension":1,"ticker":null},"id":"6834","type":"Grid"},{"attributes":{"align":"center","text":"Count of stars by type","text_font_size":"13pt"},"id":"6819","type":"Title"},{"attributes":{"factors":["Food","Bars","Nightlife","Sandwiches","Breakfast &amp; Brunch","Salad","Steakhouses","Vegetarian","Fast Food","Cafes","Diners","Pizza","Buffets","Sushi Bars","Wine Bars","Burgers","Coffee &amp; Tea"]},"id":"6817","type":"FactorRange"},{"attributes":{},"id":"6840","type":"HelpTool"},{"attributes":{"fill_alpha":{"value":0.1},"fill_color":{"value":"lightblue"},"line_alpha":{"value":0.1},"line_color":{"value":"lightblue"},"top":{"field":"stars"},"width":{"value":0.7},"x":{"field":"cat_type"}},"id":"6852","type":"VBar"},{"attributes":{},"id":"6832","type":"BasicTicker"},{"attributes":{"fill_color":{"value":"lightblue"},"line_color":{"value":"lightblue"},"top":{"field":"stars"},"width":{"value":0.7},"x":{"field":"cat_type"}},"id":"6851","type":"VBar"},{"attributes":{},"id":"6829","type":"CategoricalTicker"},{"attributes":{},"id":"6839","type":"ResetTool"},{"attributes":{},"id":"7100","type":"BasicTickFormatter"},{"attributes":{},"id":"6835","type":"PanTool"},{"attributes":{"axis":{"id":"6828"},"ticker":null},"id":"6830","type":"Grid"},{"attributes":{},"id":"6826","type":"LinearScale"},{"attributes":{},"id":"6824","type":"CategoricalScale"},{"attributes":{},"id":"7099","type":"AllLabels"},{"attributes":{},"id":"7102","type":"AllLabels"},{"attributes":{"active_multi":null,"tools":[{"id":"6835"},{"id":"6836"},{"id":"6837"},{"id":"6838"},{"id":"6839"},{"id":"6840"},{"id":"6855"}]},"id":"6842","type":"Toolbar"},{"attributes":{},"id":"6838","type":"SaveTool"},{"attributes":{},"id":"7104","type":"Selection"},{"attributes":{"axis_label":"count","formatter":{"id":"7100"},"major_label_policy":{"id":"7102"},"major_tick_line_color":null,"minor_tick_line_color":null,"ticker":{"id":"6832"}},"id":"6831","type":"LinearAxis"},{"attributes":{"overlay":{"id":"6841"}},"id":"6837","type":"BoxZoomTool"},{"attributes":{"callback":null,"tooltips":[["Average","@stars{1}"]]},"id":"6855","type":"HoverTool"},{"attributes":{"source":{"id":"6849"}},"id":"6854","type":"CDSView"}],"root_ids":["6818"]},"title":"Bokeh Application","version":"2.3.1"}}
        </script>
        <script type="text/javascript">
          (function() {
            var fn = function() {
              Bokeh.safely(function() {
                (function(root) {
                  function embed_document(root) {
                  var docs_json = document.getElementById('7367').textContent;
                  var render_items = [{"docid":"879fb4a5-d468-4ae7-919a-a4fe2cfe0b51","root_ids":["6818"],"roots":{"6818":"43409493-0834-4ab8-8224-45c14214eec9"}}];
                  root.Bokeh.embed.embed_items(docs_json, render_items);
                  }
                  if (root.Bokeh !== undefined) {
                    embed_document(root);
                  } else {
                    var attempts = 0;
                    var timer = setInterval(function(root) {
                      if (root.Bokeh !== undefined) {
                        clearInterval(timer);
                        embed_document(root);
                      } else {
                        attempts++;
                        if (attempts > 100) {
                          clearInterval(timer);
                          console.log("Bokeh: ERROR: Unable to run BokehJS code because BokehJS library is missing");
                        }
                      }
                    }, 10, root)
                  }
                })(window);
              });
            };
            if (document.readyState != "loading") fn();
            else document.addEventListener("DOMContentLoaded", fn);
          })();
        </script>




Text after the plot