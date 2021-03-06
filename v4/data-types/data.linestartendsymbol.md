---
layout: sidebar
sidebar: s1
version: "v4"
title: "data.LINESTARTENDSYMBOL"
---
<div class="specPage">
   <div class="datatypeSpec">
      <h3 id="data.LINESTARTENDSYMBOL">data.LINESTARTENDSYMBOL</h3>
      <div class="specs">
         <div class="desc">Symbol that may begin/end a line.</div>
         <div class="facet module">
            <div class="label">Module</div>
            <div class="statement text">MEI</div>
         </div>
         <div class="facet usedBy" id="usedBy">
            <div class="label">Used by</div>
            <div class="statement list">
               <div class="classBox dtBox" title="Attribute Classes">
                  <div class="classHeading"><label class="classLabel">Attribute Classes</label><span class="classDesc">These class-based attributes use data.LINESTARTENDSYMBOL</span></div>
                  <div class="classContent"><span class="ident attclass" data-ident="att.lineRend" data-module="MEI.shared"><a class="classLink" title="Attributes that record the visual rendition of lines." href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.linerend.html">att.lineRend</a>/<span title="Symbol rendered at end of line.">@lendsym</span></span><span class="ident attclass" data-ident="att.lineRend" data-module="MEI.shared"><a class="classLink" title="Attributes that record the visual rendition of lines." href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.linerend.html">att.lineRend</a>/<span title="Symbol rendered at start of line.">@lstartsym</span></span><span class="ident attclass" data-ident="att.arpeg.vis" data-module="MEI.visual"><a class="classLink" title="Visual domain attributes." href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.arpeg.vis.html">att.arpeg.vis</a>/<span title="Symbol rendered at end of the line.">@arrow.shape</span></span><span class="ident attclass" data-ident="att.line.vis" data-module="MEI.visual"><a class="classLink" title="Attributes for describing the visual appearance of a line." href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.line.vis.html">att.line.vis</a>/<span title="Symbol rendered at end of line.">@endsym</span></span><span class="ident attclass" data-ident="att.line.vis" data-module="MEI.visual"><a class="classLink" title="Attributes for describing the visual appearance of a line." href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.line.vis.html">att.line.vis</a>/<span title="Symbol rendered at start of line.">@startsym</span></span></div>
               </div>
            </div>
         </div>
         <div class="facet allowedValues" id="allowedValues">
            <div class="label">Allowed Values</div>
            <div class="statement list">
               <div class="dataValueBox" id="angledown"><span class="dataValue ident">angledown</span><span class="dataValue desc">90 degree turn down (similar to Unicode 231D at end of line, 231C at start).</span></div>
               <div class="dataValueBox" id="angleup"><span class="dataValue ident">angleup</span><span class="dataValue desc">90 degree turn up (similar to Unicode 231F at end of line, 231E at start).</span></div>
               <div class="dataValueBox" id="angleright"><span class="dataValue ident">angleright</span><span class="dataValue desc">90 degree turn right (syntactic sugar for "angledown" for vertical or angled
                     lines).</span></div>
               <div class="dataValueBox" id="angleleft"><span class="dataValue ident">angleleft</span><span class="dataValue desc">90 degree turn left (syntactic sugar for "angleup" for vertical or angled
                     lines).</span></div>
               <div class="dataValueBox" id="arrow"><span class="dataValue ident">arrow</span><span class="dataValue desc">Filled, triangular arrowhead (similar to Unicode U+25C0 or SMuFL U+EB78).</span></div>
               <div class="dataValueBox" id="arrowopen"><span class="dataValue ident">arrowopen</span><span class="dataValue desc">Open triangular arrowhead (similar to Unicode U+02C3 or SMuFL U+EB8A).</span></div>
               <div class="dataValueBox" id="arrowwhite"><span class="dataValue ident">arrowwhite</span><span class="dataValue desc">Unfilled, triangular arrowhead (similar to Unicode U+25C1 or SMuFL U+EB82).</span></div>
               <div class="dataValueBox" id="harpoonleft"><span class="dataValue ident">harpoonleft</span><span class="dataValue desc">Harpoon-shaped arrowhead left of line (similar to arrowhead of Unicode
                     U+21BD).</span></div>
               <div class="dataValueBox" id="harpoonright"><span class="dataValue ident">harpoonright</span><span class="dataValue desc">Harpoon-shaped arrowhead right of line (similar to arrowhead of Unicode
                     U+21BC).</span></div>
               <div class="dataValueBox" id="H"><span class="dataValue ident">H</span><span class="dataValue desc">Hauptstimme (Unicode U+1D1A6 or SMuFL U+E860).</span></div>
               <div class="dataValueBox" id="N"><span class="dataValue ident">N</span><span class="dataValue desc">Nebenstimme (Unicode U+1D1A7 or SMuFL U+E861).</span></div>
               <div class="dataValueBox" id="Th"><span class="dataValue ident">Th</span><span class="dataValue desc">Theme (SMuFL U+E864).</span></div>
               <div class="dataValueBox" id="ThRetro"><span class="dataValue ident">ThRetro</span><span class="dataValue desc">Theme, retrograde (SMuFL U+E865).</span></div>
               <div class="dataValueBox" id="ThRetroInv"><span class="dataValue ident">ThRetroInv</span><span class="dataValue desc">Theme, retrograde inversion (SMuFL U+E866).</span></div>
               <div class="dataValueBox" id="ThInv"><span class="dataValue ident">ThInv</span><span class="dataValue desc">Theme, inverted (SMuFL U+E867).</span></div>
               <div class="dataValueBox" id="T"><span class="dataValue ident">T</span><span class="dataValue desc">Theme (SMuFL U+E868).</span></div>
               <div class="dataValueBox" id="TInv"><span class="dataValue ident">TInv</span><span class="dataValue desc">Theme, inverted (SMuFL U+E869).</span></div>
               <div class="dataValueBox" id="CH"><span class="dataValue ident">CH</span><span class="dataValue desc">Choralemelodie (SMuFL U+E86A).</span></div>
               <div class="dataValueBox" id="RH"><span class="dataValue ident">RH</span><span class="dataValue desc">Hauptrhythmus (SMuFL U+E86B).</span></div>
               <div class="dataValueBox" id="none"><span class="dataValue ident">none</span><span class="dataValue desc">No start/end symbol.</span></div>
            </div>
         </div>
         <div class="facet declaration">
            <div class="label">Declaration</div>
            <div class="statement declaration">
               <div class="code" xml:space="preserve" data-lang="ODD"><code>
                     <div class="indent1 indent"><span data-indentation="1" class="element">&lt;macroSpec <span class="attribute">ident=</span><span class="attributevalue">"data.LINESTARTENDSYMBOL"</span> <span class="attribute">module=</span><span class="attributevalue">"MEI"</span> <span class="attribute">type=</span><span class="attributevalue">"dt"</span>&gt;</span>
                        
                        <div class="indent2 indent"><span data-indentation="2" class="element">&lt;desc&gt;</span>Symbol that may begin/end a line.<span data-indentation="2" class="element">&lt;/desc&gt;</span></div>
                        
                        <div class="indent2 indent"><span data-indentation="2" class="element">&lt;content&gt;</span>
                           
                           <div class="indent3 indent"><span data-indentation="3" class="element">&lt;valList <span class="attribute">type=</span><span class="attributevalue">"closed"</span>&gt;</span>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"angledown"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>90 degree turn down (similar to Unicode 231D at end of line, 231C at start).<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"angleup"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>90 degree turn up (similar to Unicode 231F at end of line, 231E at start).<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"angleright"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>90 degree turn right (syntactic sugar for "angledown" for vertical or angled
                                    lines).<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"angleleft"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>90 degree turn left (syntactic sugar for "angleup" for vertical or angled
                                    lines).<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"arrow"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>Filled, triangular arrowhead (similar to Unicode U+25C0 or SMuFL U+EB78).<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"arrowopen"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>Open triangular arrowhead (similar to Unicode U+02C3 or SMuFL U+EB8A).<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"arrowwhite"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>Unfilled, triangular arrowhead (similar to Unicode U+25C1 or SMuFL U+EB82).<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"harpoonleft"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>Harpoon-shaped arrowhead left of line (similar to arrowhead of Unicode
                                    U+21BD).<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"harpoonright"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>Harpoon-shaped arrowhead right of line (similar to arrowhead of Unicode
                                    U+21BC).<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"H"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>Hauptstimme (Unicode U+1D1A6 or SMuFL U+E860).<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"N"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>Nebenstimme (Unicode U+1D1A7 or SMuFL U+E861).<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"Th"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>Theme (SMuFL U+E864).<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"ThRetro"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>Theme, retrograde (SMuFL U+E865).<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"ThRetroInv"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>Theme, retrograde inversion (SMuFL U+E866).<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"ThInv"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>Theme, inverted (SMuFL U+E867).<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"T"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>Theme (SMuFL U+E868).<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"TInv"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>Theme, inverted (SMuFL U+E869).<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"CH"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>Choralemelodie (SMuFL U+E86A).<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"RH"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>Hauptrhythmus (SMuFL U+E86B).<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"none"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>No start/end symbol.<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              <span data-indentation="3" class="element">&lt;/valList&gt;</span></div>
                           <span data-indentation="2" class="element">&lt;/content&gt;</span></div>
                        <span data-indentation="1" class="element">&lt;/macroSpec&gt;</span></div></code></div>
            </div>
         </div>
      </div><script type="text/javascript">
            
            var tabbedFacets = document.querySelectorAll('.facet ul.tab');
            
            var tabClick = function(e) {
                var style = e.target.getAttribute('data-display');
                var facetId = e.target.parentNode.parentNode.parentNode.parentNode.id;
                setTabs(facetId,style)
            }
            
            for(var facetUl of tabbedFacets) {
                var facetElem = facetUl.parentNode.parentNode;
                var facetId = facetElem.id;
                var storageName = 'meiSpecs_' + facetId + '_display';
                var defaultValue = facetUl.children[0].children[0].getAttribute('data-display');
                
                if(localStorage.getItem(storageName) === null) {
                    setTabs(facetElem.id,defaultValue);
                } else {
                    setTabs(facetElem.id,localStorage.getItem(storageName));
                }
                
                var tabs = facetUl.querySelectorAll('.tab-item a');
                
                for(var tab of tabs) {
                    tab.addEventListener('click',tabClick);
                }
                
            }
            
            function setTabs(facetId,style) {
                
                var storageName = 'meiSpecs_' + facetId + '_display';
                localStorage.setItem(storageName,style);
                
                var facetElem = document.getElementById(facetId);
                
                var oldTab = facetElem.querySelector('.displayTab.active');
                oldTab.classList.remove('active');
                
                var newTab = document.getElementById(facetId + '_' + style + '_tab');
                newTab.classList.add('active');
                
                var oldBox = facetElem.querySelector('.active.facetTabbedContent');
                oldBox.classList.remove('active');
                oldBox.style.display = 'none';
                
                var newBox = document.getElementById(facetId + '_tabbedContent_' + style);
                newBox.classList.add('active');
                newBox.style.display = 'block';
                
            }
        </script></div>
</div>