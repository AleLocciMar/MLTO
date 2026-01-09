<div align="center">
  <h1>MLTO: Machine Learning Testing Ontology</h1>
  <p><b>Uma ontologia de domínio para a sistematização de testes e falhas em sistemas de Machine Learning.</b></p>
</div>

<hr>

<h3>📖 Sobre a MLTO</h3>
<p>
  A <b>MLTO (Machine Learning Testing Ontology)</b> foi desenvolvida como parte de uma investigação de doutoramento no <b>IME-USP</b>. 
  O objetivo é fornecer um vocabulário semanticamente rico para descrever o processo de teste, execução e as falhas específicas que ocorrem no ciclo de vida de modelos de ML.
</p>

<h3>🛠️ Especificações Técnicas</h3>
<ul>
  <li><b>Linguagem:</b> Turtle (Terse RDF Triple Language).</li>
  <li><b>Framework Base:</b> Baseada em <b>gUFO</b> (Unified Foundational Ontology), garantindo rigor taxonômico.</li>
  <li><b>Namespace:</b> <code>http://mlto.usp.br</code>.</li>
  <li><b>Ferramentas Compatíveis:</b> Protégé, RDFLib, Apache Jena.</li>
</ul>

<h3>🔍 Conceitos Modelados</h3>
<p>A ontologia cobre uma vasta gama de taxonomias de erros e infraestrutura, incluindo:</p>
<table>
  <tr>
    <th>Categoria</th>
    <th>Exemplos de Conceitos Modelados</th>
  </tr>
  <tr>
    <td><b>Erros de Modelo</b></td>
    <td>Wrong Model Initialisation, Wrong Weights Initialisation, Wrong Network Architecture.</td>
  </tr>
  <tr>
    <td><b>Gestão de Dados</b></td>
    <td>Wrong Tensor Shape, Wrongly Implemented Data Batching, Wrong Type of Input Data.</td>
  </tr>
  <tr>
    <td><b>Infraestrutura/GPU</b></td>
    <td>Wrong Reference to GPU Device, Wrong Tensor Transfer to GPU.</td>
  </tr>
  <tr>
    <td><b>Execução de Testes</b></td>
    <td>Test Execution, Retest, Hardware Implementation.</td>
  </tr>
</table>

<h3>🚀 Como Utilizar</h3>
<ol>
  <li><b>Visualização:</b> Importe o ficheiro <code>MLTO.ttl</code> no <b>Protégé</b> para explorar a hierarquia de classes e propriedades.</li>
  <li><b>Programação:</b> Utilize bibliotecas como <b>Jena (Java)</b> ou <b>RDFLib (Python)</b> para realizar consultas SPARQL sobre os conceitos de teste.</li>
  <li><b>Raciocínio Semântico:</b> Utilize a ontologia para classificar falhas detetadas automaticamente em pipelines de CI/CD para ML.</li>
</ol>

<hr>

<div align="center">
  <p>Esta ontologia é um recurso fundamental para a <b>IA Explicável (XAI)</b> e <b>Engenharia de Software para IA</b>.</p>
  <p>Desenvolvido no laboratório <b>LIAMF - USP</b>.</p>
</div>
