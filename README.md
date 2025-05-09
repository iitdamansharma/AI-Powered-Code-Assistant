# FILE STRUCTURE

- **agent.py**: contains all agents.

- **agent_store.py**: contains code for the agent selection process.

- **commands.sh**: basic shell commands to setup the environment to run our application.

- **Requirements.txt**: contains all dependencies needed to be installed.
  
- **custom_generate.py**: contains code for a custom generate function required at many places in our codebase.
  
- **filter.py**: contains code for the tasks of context filtering.

- **complexity_evaluator.py**: contains code for evaluating the complexity of a query and determining the class in which this query belongs.

- **database.py**: initializes rag client using PATHWAY.

- **rag_server.py**: initializes a pathway vectorserver.

- **rag_client.py**: client for pathway vector server.

- **hr_database.txt**: databse for HR manager.

- **llm_ui.py**: streamlitt front of our UI application.

- **memory.py**: contains code for short and core memory.

- **prompts.py**: contains all prompt templates required.

- **query_decomposer.py**: contains code for breaking complex multi-hop queries to simple single-hop sub-queries.

- **sandbox.py**: contains code for code guardrailing using sandboxing.

- **variables.py**: fill your API keys here.

- **wrapper.py**: combines all of our codebase into a single pipeline.

- **cache**: cache for loading huggingface models.
