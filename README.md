# isra36agent
AI Agent that automatically rechecks AI generated SQL in isolated test environment

You can import `isra36_n8nAgent.json` file into your n8n. 
It is an embedded chat for the isra36 website, but you can pin input data and run it on your own n8n instance.

***Make sure to fill in your credentials:***

- OpenAI key or OpenRouter key

- Local PostgreSQL database for test execution

You can view your created tables by connecting to your preferred PostgreSQL GUI. We recommend using DBeaver. Alternatively, you can activate the “Deactivated DB Visualization” nodes below. You’ll need to connect them to the latest successful Set node and adjust the output yourself. However, the easiest method is to connect a GUI.

It is built for PostgreSQL, but can be adapted to any programming language, and the logic can be extended to any programming framework.

## What's Next

1. Make sure that the AI **truly understands** your complex query. A strategy from Dale Carnegie: don't ask if someone understood you or not; rather, ask them to retell it in their own words. Then, approve or correct according to their narration. Only after this validation, pass the idea to the model for code generation. Separate code geneartion and understanding the problem.
2. Extend support to other programming languages.
3. Extend support to programming frameworks.
4. Extend support to entire products. 
