<h1 align="center">Legal Document Analyzer</h1>

<p align="center">
  <a href="https://huggingface.co/spaces/soureesh1211/legal-document-analyzer">
    <img src="https://img.shields.io/badge/🤗-Open%20in%20Spaces-blue.svg" alt="Open in Spaces">
  </a>
</p>

<p align="center">An AI-powered legal document analysis tool that leverages a team of specialized AI agents to review, analyze, and provide recommendations for legal documents.</p>

<h2> Overview</h2>

<p>The Legal Document Analyzer is a Streamlit web application that uses Agno's agent framework to create a team of specialized legal AI agents. The application allows users to upload PDF legal documents, which are then processed, embedded, and stored in a vector database (Qdrant). The AI agents then analyze these documents to provide detailed insights, key points, and recommendations.</p>

<h2> Features</h2>

<ul>
  <li><strong>Document Processing</strong>: Upload and process PDF legal documents</li>
  <li><strong>AI Agent Team</strong>: Utilizes a team of specialized legal AI agents:
    <ul>
      <li>Legal Researcher: Finds and cites relevant legal cases and precedents</li>
      <li>Contract Analyst: Reviews contracts and identifies key terms and issues</li>
      <li>Legal Strategist: Develops comprehensive legal strategies and recommendations</li>
      <li>Legal Team Lead: Coordinates analysis between team members</li>
    </ul>
  </li>
  <li><strong>Analysis Types</strong>:
    <ul>
      <li>📑 Contract Review</li>
      <li>🔍 Legal Research</li>
      <li>⚠️ Risk Assessment</li>
      <li>✅ Compliance Check</li>
      <li>💭 Custom Query</li>
    </ul>
  </li>
  <li><strong>Comprehensive Results</strong>: Get detailed analysis, key points, and actionable recommendations</li>
</ul>

<h2> Technologies Used</h2>

<ul>
  <li><a href="https://streamlit.io/">Streamlit</a>: Web application framework</li>
  <li><a href="https://github.com/agno-ai/agno">Agno</a>: Agent framework for creating AI agent teams</li>
  <li><a href="https://openai.com/">OpenAI</a>: GPT-4o for agent intelligence</li>
  <li><a href="https://qdrant.tech/">Qdrant</a>: Vector database for document storage and retrieval</li>
  <li><a href="https://pypi.org/project/duckduckgo-search/">DuckDuckGo Search</a>: Web search capabilities</li>
</ul>

<h2> Live Demo</h2>

<p>Try the application live on Hugging Face Spaces:<br>
<a href="https://huggingface.co/spaces/soureesh1211/legal-document-analyzer">Legal Document Analyzer</a></p>

<h2> Installation</h2>

<ol>
  <li>Clone the repository:
    <pre><code>git clone https://github.com/yourusername/legal-document-analyzer.git
cd legal-document-analyzer</code></pre>
  </li>
  <li>Install the required dependencies:
    <pre><code>pip install -r requirements.txt</code></pre>
  </li>
  <li>Run the application:
    <pre><code>streamlit run app.py</code></pre>
  </li>
</ol>

<h2> Requirements</h2>

<p>The following packages are required:</p>
<pre><code>agno
streamlit==1.40.2
qdrant-client==1.12.1
openai
pypdf
duckduckgo-search</code></pre>

<h2>🔑 API Setup</h2>

<p>To use this application, you'll need to provide:</p>
<ol>
  <li>OpenAI API Key</li>
  <li>Qdrant API Key</li>
  <li>Qdrant URL</li>
</ol>
<p>These can be entered directly in the application's sidebar.</p>

<h2> How It Works</h2>

<ol>
  <li><strong>Document Upload</strong>: Upload your legal PDF document</li>
  <li><strong>Document Processing</strong>: The document is processed, chunked, and stored in Qdrant</li>
  <li><strong>Agent Team Initialization</strong>: A team of specialized legal AI agents is created</li>
  <li><strong>Analysis Selection</strong>: Choose the type of analysis you need</li>
  <li><strong>Results</strong>: Receive detailed analysis, key points, and recommendations</li>
</ol>


<ul>
  <li>Built using <a href="https://github.com/agno-ai/agno">Agno</a> for agent orchestration</li>
  <li>Powered by OpenAI's GPT-4o model</li>
  <li>Vector embeddings and search provided by Qdrant</li>
</ul>
