<div align="center">
  <h1>MLTO: Machine Learning Testing Ontology</h1>
  <p><b>A domain ontology for systematizing testing processes and failures in Machine Learning systems.</b></p>
</div>

<hr>

<h3>📖 About MLTO</h3>
<p>
  The <b>MLTO (Machine Learning Testing Ontology)</b> was developed as part of a PhD research project at the <b>University of São Paulo (IME-USP)</b>. 
  It provides a semantically rich vocabulary to describe testing procedures, execution environments, and specific failure modes throughout the ML model lifecycle.
</p>

<h3>🛠️ Technical Specifications</h3>
<ul>
  <li><b>Language:</b> Turtle (Terse RDF Triple Language).</li>
  <li><b>Foundation:</b> Built upon the <b>gUFO</b> (Unified Foundational Ontology) framework for maximum taxonomic rigor.</li>
  <li><b>Namespace:</b> <code>http://mlto.usp.br</code></li>
  <li><b>Compatible Tools:</b> Protégé, RDFLib, Apache Jena, and other Semantic Web stacks.</li>
</ul>

<h3>🔍 Modeled Concepts & Taxonomies</h3>
<p>MLTO covers a wide range of error taxonomies and infrastructural components, including:</p>
<table>
  <tr>
    <th>Category</th>
    <th>Sample Modeled Concepts</th>
  </tr>
  <tr>
    <td><b>Model Errors</b></td>
    <td>Wrong Model Initialisation, Wrong Weights Initialisation, Wrong Network Architecture.</td>
  </tr>
  <tr>
    <td><b>Data Management</b></td>
    <td>Wrong Tensor Shape, Wrongly Implemented Data Batching, Wrong Type of Input Data.</td>
  </tr>
  <tr>
    <td><b>Infrastructure & GPU</b></td>
    <td>Wrong Reference to GPU Device, Wrong Tensor Transfer to GPU.</td>
  </tr>
  <tr>
    <td><b>Testing Lifecycle</b></td>
    <td>Test Execution, Retest, Hardware Implementation, and Operational Graphs.</td>
  </tr>
</table>

<h3>🚀 Getting Started</h3>
<ol>
  <li><b>Visualization:</b> Import the <code>MLTO.ttl</code> file into <b>Protégé</b> to explore the class hierarchy and properties.</li>
  <li><b>Development:</b> Use libraries like <b>Apache Jena (Java)</b> or <b>RDFLib (Python)</b> to perform SPARQL queries over the testing knowledge base.</li>
  <li><b>Reasoning:</b> Apply the ontology to automatically classify failures detected in ML CI/CD pipelines.</li>
</ol>

<hr>

<div align="center">
  <p>This ontology is a core resource for <b>Explainable AI (XAI)</b> and <b>Software Engineering for AI</b>.</p>
  <p>Developed at <b>LIAMF - USP (Logics, Artificial Intelligence and Formal Methods Lab)</b>.</p>
</div>
