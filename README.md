## Hi, I'm Jayesh

I work on AI products: agentic systems, GenAI copilots, and knowledge
graphs. Most of that work comes down to two questions: what should the
system do, and how do we know it actually did it. I write about both on
Medium and LinkedIn, and I'm starting to build small public examples here.

### What I work on

I'm a product manager, and for the last few years I've worked on AI
in industrial operations, where an answer that is wrong but sounds
confident costs real money and sometimes affects safety. Day to day,
that means:

- ML models built with our data science team, delivered through a SaaS
  product where customers move in stages: first seeing predictions,
  then acting on recommended setpoints, and finally switching to
  control mode, where the system adjusts the process within limits
  operators have agreed to
- Copilots for operators and engineers that answer from documents,
  plant data and a knowledge graph, and say so when they don't know
- Agents that move step by step up an autonomy ladder, with human
  review at the points where it matters
- Evaluation: test sets, LLM-as-judge with its known biases, and the
  gap between how a model scores on a benchmark and how it holds up
  in production

Before this, I worked on hybrid cloud and FinOps SaaS, AIOps, and IoT
analytics for manufacturing. The domains changed, but the job stayed
the same: turning messy systems into something people can trust and
act on.

### What I'm building here

Small, honest projects, not production systems. A few I'm working on
or planning:

- **RAG evaluation harness:** a retrieval pipeline over public
  documents with a test set and LLM-as-judge scoring, plus notes on
  what the scores do and don't tell you. It's the companion to an
  essay on why AI metrics are not the same as evidence.
- **Human-in-the-loop agent:** a small LangGraph agent with approval
  checkpoints and an adjustable autonomy level, to show where a human
  should stay in the loop and why.
- **Farm forecasting:** classical ML on real data from my orchard,
  such as tree health and irrigation needs. It's a reminder that most
  useful ML is still tabular and unglamorous.

Some of the code is written with AI help; the design choices and
conclusions are mine.

### Writing

- [How to Make Your AI Agent Production Ready in an Industrial Setup](https://briefs.aiadvances.org/how-to-make-your-ai-agent-production-ready-in-an-industrial-setup-7e9a65461dcd) - what it actually takes to move an AI agent from a demo to something that holds up in an industrial setting.
- [Everyone's Reading the Wrong Line in Anthropic's Economic Report](https://briefs.aiadvances.org/everyones-reading-the-wrong-line-in-anthropic-s-economic-report-9573488a577a) - a second look at the report, and the line most coverage skipped over.
- [The PM Role Is Getting Harder, Not Smaller](https://medium.com/design-bootcamp/the-pm-role-is-getting-harder-not-smaller-ee8affb4cfda) - why the product manager's job is getting harder as AI changes what a product even means, not easier.
- [Product Management Installed an Operating System in My Brain. I Never Asked for It.](https://medium.com/@jayesh.bachhav/product-management-installed-an-operating-system-in-my-brain-i-never-asked-for-it-7e531a0dd8d2) - how product management habits have started shaping the way I think outside of work too.
- [Your Agent Isn't the Moat. The Verification Stack Is.](https://briefs.aiadvances.org/your-agent-isnt-the-moat-the-verification-stack-is-88c479ddd09a) - why verifying what an agent does matters more than the agent itself.
- [Beyond the Model: The 15 Concepts That Actually Ship AI Products](https://medium.com/@jayesh.bachhav/the-ai-concepts-i-wish-id-learned-sooner-22b1436e8082) - fifteen concepts I kept running into while shipping AI products, written down so I stop relearning them.

### Latest on Medium

<!-- BLOG-POST-LIST:START -->
<!-- BLOG-POST-LIST:END -->

### Outside work

I run a small farm with about two thousand trees. It's the most
patient feedback loop I know.

### Elsewhere

[LinkedIn](https://www.linkedin.com/in/jayesh-bachhav-a969b24a/) · [Medium](https://medium.com/@jayesh.bachhav)
