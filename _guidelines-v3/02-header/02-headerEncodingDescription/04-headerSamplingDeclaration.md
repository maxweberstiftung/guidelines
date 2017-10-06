---
sectionid: headerSamplingDeclaration
title: Sampling Declaration
---


<h3 id="headerSamplingDeclaration">
   <span class="headingNumber">2.2.4</span>
   <span class="head">Sampling Declaration</span>
</h3>
The samplingDecl element holds a prose description of the rationale and methods used
in
selecting texts, or parts of text, for inclusion in the resource.



<span class="specList">
   
   <span class="specDesc"></span>
   
</span>


The 
<a class="link_odd_elementSpec" href="/v3/elements/samplingDecl">samplingDecl</a> element should include information about such
matters as:


<span class="list">
   
   <span class="item">the size of individual samples</span>
   
   <span class="item">the method or methods by which they were selected</span>
   
   <span class="item">the underlying population being sampled</span>
   
   <span class="item">the object of the sampling procedure used</span>
   
</span>
but is not restricted to these.


{% include _plainExample.html example="./v3/examples/header/header-sample051.xml" valid="true" %}

It may also include a simple description of any parts of the source text included
or
excluded:


{% include _plainExample.html example="./v3/examples/header/header-sample052.xml" valid="true" %}


{% include _plainExample.html example="./v3/examples/header/header-sample053.xml" valid="true" %}

A sampling declaration which applies to more than one text or division of a text need
not
be repeated in the header of each such text. Instead, the **@decls** attribute of each
text (or subdivision of the text) to which the sampling declaration applies may be
used to
supply a cross-reference to it, as further described in section 
<span class="ptr"></span>.
