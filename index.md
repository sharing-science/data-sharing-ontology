---
layout: default
title: "Academic Incentive Ontology: A Model of Blockchain-Based Data Sharing"
---


<h1 class="page-title" style="text-transform:uppercase;" id="header">Academic Incentive Ontology: A Model of Blockchain-Based Data Sharing</h1>
<h3 style="color:dimgrey;">Kacy Adams<sup>1</sup>, Oshani Seneviratne<sup>1</sup>, Deborah L. McGuinness<sup>1</sup></h3>
<h3><a href="https://www.rpi.edu/"><sup>1</sup>Rensselaer Polytechnic Institute</a></h3>

<!-- <table>
  <tbody>
    <tr>
      <td><a href="#abstract">Abstract</a></td>
    </tr>
  </tbody>
</table> -->

<hr>
<article class="mb-5" id="abstract">
<content>
  
  
<h2>Abstract</h2>
  <p>In fields such as medical research, data collection is slow and rigorous, meaning conclusive findings take years to produce. Due to the closed nature of biomedical research, this leads to the reproduction of similar datasets, while leaving datasets with multiple implications abeyant. Further, there is a lack of complete and useful open datasets in many different fields, which leave researchers with no choice but to collect data on their own. There is a rising need for a secure data sharing ecosystem which recommends, incentivizes, and rewards collaborative efforts between researchers and research groups. Permissionless, public blockchains provide the necessary framework for trustless and fair data sharing. We design an ontology to capture the events associated with blockchain-based data sharing and a corresponding incentive scheme, which includes a reputation-based peer review system and an index to provide recommendations and ratings of possible collaborators. We present a use case indicating the ontology’s plausibility in the biomedical research community and evaluate our ontology with a set of competency questions geared towards participating researchers and other academic stakeholders. Through the use of the ontology, a blockchain ecosystem can be built that will incentivize, encourage, and reward data sharing.</p>
 </content>
 
 <hr/>
 <article class="mb-5" id="resources">
<content>
<h2>List of Resources </h2>
<ul>
 <table style="width:100%">
    <tr>
    <th>Resources</th>
    <th>Links</th> 
  </tr>
   <tr>
    <td>Protocol Guidance on Usage of Ontology</td>
    <td><a href="protocol">Protocol</a> </td> 
  </tr>
  <tr>
    <td>Ontology</td>
    <td><a href="ontology">Explanation Ontology</a> </td> 
  </tr>
  <tr>
    <td>Explanation Types</td>
    <td><a href="modeling#explanationtypes">Modeling</a> </td> 
  </tr>
    <!--<tr>
    <td> </td>
    <td> (b) <a href="./application.html">Faceted Browser</a> </td> 
  </tr>-->
    <tr>
    <td>Clincal Example</td>
    <td><a href="clinicalexample">Example of a Contrastive Explanation</a> </td> 
  </tr>
   <tr>
    <td>Competency Questions </td>
    <td><a href="competencyquestions#sparql">SPARQL Queries</a> </td> 
  </tr>
   <tr>
    <td>Tools Used </td>
    <td><a href="index#toolsused">References to tools used</a> </td> 
  </tr>
</table>
  
 </ul>
 </content>
 
 <hr/>
 
 <article class="mb-5" id="toolsused">
<content>
  
  
<h2>Tools Used during Development</h2>
  <ul>
  <li>Ontology Editor: <a href="https://protege.stanford.edu/products.php#desktop-protege">Protege 5.5.0</a></li>
  <li>Ontology documentation tool, <a href="https://github.com/dgarijo/Widoco">Widoco</a></li>
  </ul>
  </content>
  <!--<iframe src="https://tetherless-world.github.io/explanation-ontology/WidocoDocumentation/index-en.html" style="width:100%;"/>-->
 
  <article class="mb-5" id="publications">
<content>
  <h2>Publications</h2>
  <ul>
  </ul>
  </content>
<!-- 
<div class="posts">
  {% for post in paginator.posts %}
  <div class="post">
    <h1 class="post-title">
      <a href="{{ post.url }}">
        {{ post.title }}
      </a>
    </h1>

    <span class="post-date">{{ post.date | date_to_string }}</span>

    {{ post.content }}
  </div>
  {% endfor %}
</div>

<div class="pagination">
  {% if paginator.next_page %}
    <a class="pagination-item older" href="{{ site.baseurl }}page{{paginator.next_page}}">Older</a>
  {% else %}
    <span class="pagination-item older">Older</span>
  {% endif %}
  {% if paginator.previous_page %}
    {% if paginator.page == 2 %}
      <a class="pagination-item newer" href="{{ site.baseurl }}">Newer</a>
    {% else %}
      <a class="pagination-item newer" href="{{ site.baseurl }}page{{paginator.previous_page}}">Newer</a>
    {% endif %}
  {% else %}
    <span class="pagination-item newer">Newer</span>
  {% endif %}
</div> -->
    
   ---
layout: default
title: Explanation Ontology
---

<article class="mb-5" id="ontology">
<content>
  
  
<h2 id="ontologyabout">Academic Incentive Ontology</h2>
  <p>The Academic Incentive Ontology (AIO) intends to provide a semantic model to power a blockchain application to handle, confirm, and incentivize research data sharing. The ontology is built upon basic blockchain components such as addresses and transaction hashes and uses simple logic such that it could be easily handled by smart contracts</p>
  
  <caption>Insert full conceptual overview</caption>  
  
  <h3 id="ontologylinks">Ontology Links</h3>
  <ul>
  <li>Widoco Link</a></li>
  <li>RDF Link</li>
  </ul>
  
  <article class="mb-5" id="ontologymetadata">
  <content>
    <h3>Ontology Metadata</h3>
    <p>Metadata that would be useful to navigate our <a href="#resources">resources</a>, i.e., ontology, modeling snippets and SPARQL queries. The content below can also be viewed by inspecting our explanation ontology in an ontology editor, like, <a href="https://protege.stanford.edu/products.php#desktop-protege">Protege 5.5.0</a>.
  <h4 id="ontologiesreused">Ontologies Reused</h4>
  <ul>
  <li><a href="https://raw.githubusercontent.com/MaastrichtU-IDS/semanticscience/master/ontology/sio.owl">SemanticScience Integrated Ontology (SIO)</a></li>
  <li><a href="https://www.w3.org/TR/prov-o/">The Provenance Ontology (PROV-O)</a></li>
  </ul>
    
  <h4> Ontology Prefixes </h4>
  <table style="width:100%">
    <tr>
    <th>Prefix</th>
    <th>Links</th> 
  </tr>
  <tr>
    <td>rdf</td>
    <td><a href="http://www.w3.org/1999/02/22-rdf-syntax-ns">Resource Description Framework</a></td> 
  </tr>
  <tr>
    <td>rdfs</td>
    <td><a href="http://www.w3.org/2000/01/rdf-schema"> RDF Schema</a> </td> 
  </tr>
  <tr>
    <td>owl</td>
    <td><a href="http://www.w3.org/2002/07/owl#">Web Ontology Language </a> </td> 
  </tr>
    <tr>
    <td> xsd</td>
    <td> <a href="http://www.w3.org/2001/XMLSchema#"></a> XML Schema Definition</td> 
  </tr>
   <tr>
    <td>skos</td>
    <td> <a href="http://www.w3.org/2004/02/skos/core#"></a>  Simple Knowledge Organization System</td> 
  </tr>
    <tr>
    <td>aio</td>
    <td> <a> Academic Incentive Ontology</a> </td> 
  </tr>   
    <tr>
    <td>sio</td>
    <td> <a href="http://semanticscience.org/resource/">SemanticScience Integrated Ontology</a> </td> 
  </tr>
  <tr>
    <td>ep</td>
    <td> <a href="https://www.w3.org/TR/prov-o/">Provenance Ontology</a> </td> 
  </tr>

    
</table>
