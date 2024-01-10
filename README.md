# hegeljs

Welcome to [HegelJS](https://www.npmjs.com/package/@hegel-ai/hegeljs)! The official TypeScript and JavaScript client for Hegel AI's developer platform.

[Hegel AI](https://hegel-ai.com) enables developers to build, monitor, and improve their LLM applications. It tracks every
request, provides and editor for prompts, and automatically generates improvements based on real-time feedback and evaluations. You can sign up [here](https://app.hegel-ai.com).

![image](img/platform.png)

## Adding HegelJS to an existing Node.js app

Just install the package with `npm i @hegel-ai/hegeljs` and make the following change to your OpenAI client initialization:

![image](img/commit.png)

Before starting your app, you'll need to have your `HEGELAI_API_KEY` set. You can do this by running `export HEGELAI_API_KEY=<YOUR_API_KEY>`. You'll need your `OPENAI_API_KEY` set as well, which you can set similarly.

If you need a Hegel AI API key, you can sign up [here](https://app.hegel-ai.com).
