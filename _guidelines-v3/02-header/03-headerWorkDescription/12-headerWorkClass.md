---
sectionid: headerWorkClass
title: Classification
---


<h3 id="headerWorkClass">
   <span class="headingNumber">2.3.12</span>
   <span class="head">Classification</span>
</h3>
The next component of the core 
<a class="link_odd_elementSpec" href="/v3/elements/workDesc">workDesc</a> element is the 
<a class="link_odd_elementSpec" href="/v3/elements/classification">classification</a> element. This element is used to classify a musical text
according to one or more of the following methods:


<span class="list">
   
   <span class="item">by reference to a recognized international classification scheme such as the Dewey
      Decimal Classification, the Universal Decimal Classification, the Colon Classification,
      the Library of Congress Classification, or any other system widely used in library
      and
      documentation work
   </span>
   
   <span class="item">by providing a set of keywords, as provided, for example, by British Library or
      Library of Congress Cataloguing in Publication data.
   </span>
   
</span>
The following elements are provided for this purpose:



<span class="specList">
   
   <span class="specDesc"></span>
   
   <span class="specDesc"></span>
   
</span>


The 
<a class="link_odd_elementSpec" href="/v3/elements/termList">termList</a> element categorizes an individual text by supplying a
set of terms which may describe its topic or subject matter, its physical or intellectual
form, date, etc. Each term is indicated by a 
<a class="link_odd_elementSpec" href="/v3/elements/term">term</a> element. In some
schemes, the order of items in the list is significant, for example, from major topic
to
minor; in others, the list has an organized substructure of its own. No recommendations
are
made here as to which method is to be preferred. Wherever possible, such terms should
be
taken from a recognized source.

The classCode element offers the possibility of capturing a bibliographic citation
and/or a
URI at which the classification scheme or information about it may be found.


{% include _plainExample.html example="./v3/examples/header/header-sample070.xml" valid="true" %}


{% include _plainExample.html example="./v3/examples/header/header-sample071.xml" valid="true" %}


{% include _plainExample.html example="./v3/examples/header/header-sample072.xml" valid="true" %}

The **@classcode** attribute may be used on each term element to make reference, by
means of an identifier, to the classification scheme from which it is drawn.


{% include _plainExample.html example="./v3/examples/header/header-sample073.xml" valid="true" %}

Alternatively, **@classcode** may be used on 
<a class="link_odd_elementSpec" href="/v3/elements/termList">termList</a> when all
the contained terms come from the same source.


{% include _plainExample.html example="./v3/examples/header/header-sample074.xml" valid="true" %}
