---
layout: page
title: Publications
permalink: /publications/
---

  <header class="post-header">
    <h2 class="post-title">Publications</h2>
  </header> 
<p>Our groups published 3 papers at <a href="https://aaai.org/Conferences/AAAI-18/wp-content/uploads/2017/12/AAAI-18-Accepted-Paper-List.Web_.pdf">AAAI</a> and 9 at <a href="https://icml.cc/">ICML</a>!</p>
<p>See the individual group publication pages below for additional publications:</p>

{% for link in site.data.publications %}

<table class="table table-striped table-hover">
{% for link in link.links %}
    <tr>
        <td> 
           <a href="{{link.url}}">{{link.name}}</a> 
        </td>
        <td> {{ link.description }}  </td>
    </tr>
{% endfor %}
</table>
{% endfor %}

<style>
#pubTable_filter{
    display:none;
}
</style>

<table id="pubTable" class="table table-hover"></table>



