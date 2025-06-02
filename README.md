<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Agentic AI Developer Roadmap</title>
  <style>
    body {
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen,
        Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
      line-height: 1.6;
      margin: 0 auto;
      max-width: 900px;
      padding: 20px;
      color: #222;
      background: #fafafa;
    }
    h1, h2, h3 {
      color: #2c3e50;
    }
    h1 {
      border-bottom: 3px solid #2980b9;
      padding-bottom: 0.3em;
    }
    table {
      border-collapse: collapse;
      width: 100%;
      margin: 1em 0 2em 0;
    }
    th, td {
      text-align: left;
      padding: 0.75em;
      border-bottom: 1px solid #ddd;
    }
    th {
      background-color: #2980b9;
      color: white;
    }
    ul {
      margin-top: 0;
      padding-left: 1.2em;
    }
    section {
      margin-bottom: 3em;
      background: white;
      border-radius: 6px;
      box-shadow: 0 2px 5px rgb(0 0 0 / 0.05);
      padding: 1.5em;
    }
    code {
      background-color: #eaeaea;
      padding: 0.2em 0.4em;
      border-radius: 3px;
      font-family: Consolas, monospace;
    }
    pre {
      background-color: #eaeaea;
      padding: 1em;
      border-radius: 5px;
      overflow-x: auto;
    }
    a {
      color: #2980b9;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
    footer {
      font-size: 0.9em;
      color: #666;
      text-align: center;
      margin-top: 3em;
      padding-top: 1em;
      border-top: 1px solid #ddd;
    }
  </style>
</head>
<body>

  <h1>Agentic AI Developer Roadmap</h1>

  <p>
    Welcome to the <strong>Agentic AI Developer Roadmap</strong> — a comprehensive 21-week journey designed to take you from the fundamentals of generative AI all the way to building advanced agentic AI systems.
  </p>
  <p>
    This roadmap is perfect for developers, researchers, and AI enthusiasts eager to master the skills needed to design, build, and deploy intelligent AI agents.
  </p>

  <section>
    <h2>Roadmap Overview</h2>
    <table>
      <thead>
        <tr>
          <th>Weeks</th>
          <th>Topics</th>
        </tr>
      </thead>
      <tbody>
        <tr><td>1–2</td><td>Introduction to Generative AI</td></tr>
        <tr><td>3</td><td>Build Your First Agent – No Code</td></tr>
        <tr><td>4–5</td><td>Basic Coding for AI</td></tr>
        <tr><td>6–7</td><td>LLM Essentials</td></tr>
        <tr><td>8</td><td>Prompt Engineering Essentials</td></tr>
        <tr><td>9–10</td><td>Introduction to LangChain</td></tr>
        <tr><td>11–12</td><td>RAG Systems Essentials</td></tr>
        <tr><td>13</td><td>Introduction to AI Agents</td></tr>
        <tr><td>14–15</td><td>Agentic AI Design Patterns</td></tr>
        <tr><td>16–17</td><td>Build an AI Agent from Scratch in Python</td></tr>
        <tr><td>18–19</td><td>Build Agentic AI Systems with LangChain, CrewAI, LangGraph, AutoGen</td></tr>
        <tr><td>20–21</td><td>Build Advanced Agentic RAG Systems</td></tr>
      </tbody>
    </table>
  </section>

  <section>
    <h2>Weekly Modules &amp; Key Focus Areas</h2>

    <article>
      <h3>🧬 Week 1–2: Introduction to Generative AI</h3>
      <ul>
        <li>Understand core <strong>Generative AI</strong> concepts and how they differ from traditional AI</li>
        <li>Learn about foundational GenAI models:
          <ul>
            <li><code>GANs</code> (Generative Adversarial Networks)</li>
            <li><code>VAEs</code> (Variational Autoencoders)</li>
            <li><code>Gaussian Mixture Models</code></li>
          </ul>
        </li>
        <li>Explore modern GenAI techniques:
          <ul>
            <li><code>Diffusion Models</code> (used in image generation like Stable Diffusion)</li>
            <li><code>Transformer-based Models</code> (e.g., GPT, BERT, T5)</li>
          </ul>
        </li>
        <li>Examine <strong>real-world applications</strong> of Generative AI in healthcare, finance, marketing, and entertainment</li>
      </ul>
    </article>

    <article>
      <h3>🛠️ Week 3: Build Your First Agent – No Code</h3>
      <ul>
        <li>Use <strong>No-Code platforms</strong> like Flowise, LangChain Hub, Pinecone Playground</li>
        <li>Customize and deploy AI agents without writing code</li>
        <li>Build simple utility agents and multi-tool agents</li>
        <li>Chain tools, memory, and LLMs using visual workflows</li>
      </ul>
    </article>

    <article>
      <h3>💻 Week 4–5: Basic Coding for AI</h3>
      <ul>
        <li>Master core <code>Python</code> programming: loops, conditionals, functions, classes</li>
        <li>Work with <code>Pandas</code> for data processing</li>
        <li>Learn basic <code>SQL</code> to query/manage databases</li>
        <li>Practice using APIs to connect with external services and LLMs</li>
        <li>Build simple AI-powered apps using <code>Flask</code> or <code>FastAPI</code></li>
      </ul>
    </article>

    <article>
      <h3>🧩 Week 6–7: LLM Essentials</h3>
      <ul>
        <li>Introduction to <strong>Large Language Models (LLMs)</strong> and their applications</li>
        <li>Types of LLMs and their general architecture</li>
        <li>Understand <em>self-attention</em>, tokenization, pretraining, and fine-tuning</li>
        <li>Explore LLMs like GPT-4o, OpenAI o1 preview, Gemini, Claude, Llama 3.1</li>
      </ul>
    </article>

    <article>
      <h3>✍️ Week 8: Prompt Engineering Essentials</h3>
      <ul>
        <li>Core principles of prompt engineering</li>
        <li>Writing effective prompts for summarization, Q&amp;A, creative writing, coding</li>
        <li>Advanced techniques including zero-shot, few-shot, chain-of-thought, role prompting</li>
      </ul>
    </article>

    <article>
      <h3>🛠️ Week 9–10: Introduction to LangChain</h3>
      <ul>
        <li>Core LangChain components: LLMs, Chains, Parsers, Model I/O</li>
        <li>Use LangChain Expression Language (LCEL) to create pipelines</li>
        <li>Build prompt templates and output parsers</li>
        <li>Build simple conversational LLM applications</li>
        <li>Create advanced AI systems with chaining and external data integration</li>
      </ul>
    </article>

    <article>
      <h3>📚 Week 11–12: RAG Systems Essentials</h3>
      <ul>
        <li>Document loading and processing techniques</li>
        <li>Document chunking strategies</li>
        <li>Work with vector databases (ChromaDB, FAISS, Pinecone)</li>
        <li>CRUD operations in vector databases</li>
        <li>Retrieval strategies: semantic and hybrid search</li>
        <li>Build end-to-end Retrieval-Augmented Generation (RAG) systems</li>
      </ul>
    </article>

    <article>
      <h3>🤖 Week 13: Introduction to AI Agents</h3>
      <ul>
        <li>What are AI Agents? Definitions and components</li>
        <li>Agent architecture, action loops, memory and planning</li>
        <li>Types: reactive, deliberative, hybrid agents</li>
        <li>Common use cases: chatbots, autonomous systems, assistants</li>
      </ul>
    </article>

    <article>
      <h3>📐 Week 14–15: Agentic AI Design Patterns</h3>
      <ul>
        <li>Design patterns for AI agents</li>
        <li>Memory and state management</li>
        <li>Tool use &amp; APIs integration</li>
        <li>Planning and reasoning methods</li>
        <li>Multi-agent collaboration</li>
      </ul>
    </article>

    <article>
      <h3>🐍 Week 16–17: Build an AI Agent from Scratch in Python</h3>
      <ul>
        <li>Python frameworks &amp; packages for AI agents</li>
        <li>Agent class structure and implementation</li>
        <li>Integrate LLMs, APIs, and toolkits</li>
        <li>Implement memory, prompt chaining, and tool use</li>
        <li>Test and deploy your agent</li>
      </ul>
    </article>

    <article>
      <h3>🚀 Week 18–19: Build Agentic AI Systems with LangChain, CrewAI, LangGraph, AutoGen</h3>
      <ul>
        <li>Advanced LangChain usage</li>
        <li>Using CrewAI for task orchestration</li>
        <li>Visualizing agent workflows with LangGraph</li>
        <li>Multi-agent collaboration with AutoGen</li>
        <li>Integration best practices</li>
      </ul>
    </article>

    <article>
      <h3>⚙️ Week 20–21: Build Advanced Agentic RAG Systems</h3>
      <ul>
        <li>Combine retrieval with agentic AI</li>
        <li>Advanced RAG design patterns</li>
        <li>Knowledge management and multi-modal data integration</li>
        <li>Deploying scalable agentic AI systems</li>
        <li>Security, ethical AI, and monitoring</li>
      </ul>
    </article>
  </section>

  <section>
    <h2>Getting Started</h2>
    <p>
      To start your journey, explore the <a href="https://github.com/hwchase17/agentic" target="_blank" rel="noopener noreferrer">official agentic AI GitHub repo</a> and check out <a href="https://www.hwchase17.com/agentic/" target="_blank" rel="noopener noreferrer">the creator’s website</a> for tutorials and sample projects.
    </p>
  </section>

  <footer>
    &copy; 2025 Agentic AI Developer Roadmap. Created by ChatGPT.
  </footer>

</body>
</html>
