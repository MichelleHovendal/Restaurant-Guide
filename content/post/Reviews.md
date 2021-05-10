---
title: "Reviews"
date: 2021-04-18T08:33:03+02:00
draft: True
weight: 3
---
Ellen tryller ...

<script type="text/javascript" src="https://cdn.pydata.org/bokeh/release/bokeh-1.4.0.min.js"></script>
        <script type="text/javascript">
            Bokeh.set_log_level("info");
        </script>
        <div class="bk-root" id="24d03565-cfeb-4edf-a98d-f44e26927db7" data-root-id="1002"></div>
        <script type="application/json" id="1185">
          {"e7f263f9-49de-4e9c-bd2b-43dad2b3ba72":{"roots":{"references":[{"attributes":{},"id":"1025","type":"SaveTool"},{"attributes":{"fill_color":{"value":"lightblue"},"line_color":{"value":"lightblue"},"top":{"field":"top"},"width":{"value":0.3},"x":{"field":"x"}},"id":"1036","type":"VBar"},{"attributes":{"formatter":{"id":"1042","type":"CategoricalTickFormatter"},"major_tick_line_color":{"value":null},"ticker":{"id":"1014","type":"CategoricalTicker"}},"id":"1013","type":"CategoricalAxis"},{"attributes":{"source":{"id":"1035","type":"ColumnDataSource"}},"id":"1039","type":"CDSView"},{"attributes":{"callback":null,"data":{"top":[800,200],"x":["Real review","Fake review"]},"selected":{"id":"1048","type":"Selection"},"selection_policy":{"id":"1047","type":"UnionRenderers"}},"id":"1035","type":"ColumnDataSource"},{"attributes":{"callback":null,"start":0},"id":"1007","type":"DataRange1d"},{"attributes":{},"id":"1018","type":"BasicTicker"},{"attributes":{},"id":"1047","type":"UnionRenderers"},{"attributes":{"formatter":{"id":"1044","type":"BasicTickFormatter"},"major_tick_line_color":{"value":null},"minor_tick_line_color":{"value":null},"ticker":{"id":"1018","type":"BasicTicker"}},"id":"1017","type":"LinearAxis"},{"attributes":{},"id":"1009","type":"CategoricalScale"},{"attributes":{"callback":null,"factors":["Real review","Fake review"]},"id":"1005","type":"FactorRange"},{"attributes":{"dimension":1,"ticker":{"id":"1018","type":"BasicTicker"}},"id":"1021","type":"Grid"},{"attributes":{},"id":"1014","type":"CategoricalTicker"},{"attributes":{"bottom_units":"screen","fill_alpha":{"value":0.5},"fill_color":{"value":"lightgrey"},"left_units":"screen","level":"overlay","line_alpha":{"value":1.0},"line_color":{"value":"black"},"line_dash":[4,4],"line_width":{"value":2},"render_mode":"css","right_units":"screen","top_units":"screen"},"id":"1046","type":"BoxAnnotation"},{"attributes":{"grid_line_color":null,"ticker":{"id":"1014","type":"CategoricalTicker"}},"id":"1016","type":"Grid"},{"attributes":{"align":"center","text":"Anomaly detection","text_font_size":{"value":"13pt"}},"id":"1003","type":"Title"},{"attributes":{},"id":"1022","type":"PanTool"},{"attributes":{},"id":"1026","type":"ResetTool"},{"attributes":{},"id":"1042","type":"CategoricalTickFormatter"},{"attributes":{},"id":"1027","type":"HelpTool"},{"attributes":{"fill_alpha":{"value":0.1},"fill_color":{"value":"#1f77b4"},"line_alpha":{"value":0.1},"line_color":{"value":"#1f77b4"},"top":{"field":"top"},"width":{"value":0.3},"x":{"field":"x"}},"id":"1037","type":"VBar"},{"attributes":{"data_source":{"id":"1035","type":"ColumnDataSource"},"glyph":{"id":"1036","type":"VBar"},"hover_glyph":null,"muted_glyph":null,"nonselection_glyph":{"id":"1037","type":"VBar"},"selection_glyph":null,"view":{"id":"1039","type":"CDSView"}},"id":"1038","type":"GlyphRenderer"},{"attributes":{},"id":"1048","type":"Selection"},{"attributes":{},"id":"1023","type":"WheelZoomTool"},{"attributes":{"active_drag":"auto","active_inspect":"auto","active_multi":null,"active_scroll":"auto","active_tap":"auto","tools":[{"id":"1022","type":"PanTool"},{"id":"1023","type":"WheelZoomTool"},{"id":"1024","type":"BoxZoomTool"},{"id":"1025","type":"SaveTool"},{"id":"1026","type":"ResetTool"},{"id":"1027","type":"HelpTool"}]},"id":"1028","type":"Toolbar"},{"attributes":{},"id":"1011","type":"LinearScale"},{"attributes":{},"id":"1044","type":"BasicTickFormatter"},{"attributes":{"overlay":{"id":"1046","type":"BoxAnnotation"}},"id":"1024","type":"BoxZoomTool"},{"attributes":{"below":[{"id":"1013","type":"CategoricalAxis"}],"center":[{"id":"1016","type":"Grid"},{"id":"1021","type":"Grid"}],"left":[{"id":"1017","type":"LinearAxis"}],"plot_height":300,"renderers":[{"id":"1038","type":"GlyphRenderer"}],"title":{"id":"1003","type":"Title"},"toolbar":{"id":"1028","type":"Toolbar"},"toolbar_location":null,"x_range":{"id":"1005","type":"FactorRange"},"x_scale":{"id":"1009","type":"CategoricalScale"},"y_range":{"id":"1007","type":"DataRange1d"},"y_scale":{"id":"1011","type":"LinearScale"}},"id":"1002","subtype":"Figure","type":"Plot"}],"root_ids":["1002"]},"title":"Bokeh Application","version":"1.4.0"}}
        </script>
        <script type="text/javascript">
          (function() {
            var fn = function() {
              Bokeh.safely(function() {
                (function(root) {
                  function embed_document(root) {
                    
                  var docs_json = document.getElementById('1185').textContent;
                  var render_items = [{"docid":"e7f263f9-49de-4e9c-bd2b-43dad2b3ba72","roots":{"1002":"24d03565-cfeb-4edf-a98d-f44e26927db7"}}];
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