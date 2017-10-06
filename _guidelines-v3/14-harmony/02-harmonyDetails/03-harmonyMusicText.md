---
sectionid: harmonyMusicText
title: Indications of Harmony in the Music Text
---


<h3 id="harmonyMusicText">
   <span class="headingNumber">14.2.3</span>
   <span class="head">Indications of Harmony in the Music Text</span>
</h3>
With regard to indications of harmony, MEI attempts to strike a balance between very
precise (interpreted) and very loose (uninterpreted) markup needs. Therefore, various
kinds
of harmonic labels are accommodated by the 
<a class="link_odd_elementSpec" href="/v3/elements/harm">harm</a> element. While some
are more 
<span class="q">structured</span> than others, in the final analyis they all function as
*labels*. Therefore, MEI provides only a single element for the capture of
harmonic indications of all kinds:



<span class="specList">
   
   <span class="specDesc"></span>
   
</span>


The 
<a class="link_odd_elementSpec" href="/v3/elements/harm">harm</a> element can be used to capture chord labels that consist
entirely of text:


{% include _plainExample.html example="./v3/examples/harmony/harmony-sample249.xml" valid="false" %}

or labels that are chord tablature grids:


<figure class="figure">
   <img src="../../../../guidelines/3.0.0/Images/modules/harmony/A7_5th.gif" class="img-responsive"></img>
   <figcaption class="figure-caption">Figure 39. Chord grid without label</figcaption>
</figure>

{% include _plainExample.html example="./v3/examples/harmony/harmony-sample250.xml" valid="true" %}

or labels that mix these styles:


<figure class="figure">
   <img src="../../../../guidelines/3.0.0/Images/modules/harmony/A7_1st.gif" class="img-responsive"></img>
   <figcaption class="figure-caption">Figure 40. Chord grid with label</figcaption>
</figure>

{% include _plainExample.html example="./v3/examples/harmony/harmony-sample251.xml" valid="true" %}


The 
<a class="link_odd_elementSpec" href="/v3/elements/harm">harm</a> element must define a point of attachment using one of the
following attributes: **@startid**, **@tstamp**, **@tstamp.ges** or
**@tstamp.real**. The most commonly-used of these are **@startid** and
**@tstamp**.

The **@dur** attribute encodes the logical and visual duration of the harmony. Please
note that the **@dur** attribute here is not a true duration, but rather a time stamp
for the end point of the harmony.

Precise placement of the harmonic label can be controlled through the use of attributes
in
the 
<a class="link_odd" href="/v3/attribute-classes/att.harm.vis">att.harm.vis</a> attribute class.


