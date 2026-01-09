
# Open Swarm AI Agents

**Improve multi-agent coordination with AI. Built for the way the world works with AI today.**

Open Swarm AI Agents is an open-source framework for building and coordinating multi-agent AI systems. It aims to bring the best of Arzule, CrewAI, AutoGen, Relevance AI, and Lindy into a single, unified platform.

## Key Features

*   **Unified API:** A single, easy-to-use API for creating and managing AI agents, regardless of the underlying model.
*   **Advanced Coordination:** Sophisticated coordination and communication protocols for seamless collaboration between agents.
*   **Extensible and Modular:** Easily extend the framework with new agents, tools, and communication methods.
*   **Built for Production:** Designed for reliability and scalability, with built-in monitoring and logging.
*   **Integrations:** Seamlessly integrates with popular AI models, data sources, and deployment platforms.

## Comparison with Other Systems

| Feature | Open Swarm AI Agents | Arzule | CrewAI | AutoGen | Relevance AI | Lindy |
| --- | --- | --- | --- | --- | --- | --- |
| **Coordination** | Advanced | Basic | Basic | Advanced | Basic | Basic |
| **Extensibility** | High | Medium | Medium | High | Low | Low |
| **Production Ready**| Yes | No | No | Yes | No | No |
| **Integrations** | High | Low | Medium | Medium | Low | Low |

## Getting Started

To get started with Open Swarm AI Agents, you'll need to have Python 3.7 or later installed.

**Installation**

```bash
pip install open-swarm-ai-agents
```

**Example**

```python
from open_swarm_ai_agents import Agent, Task

# Create two agents
agent1 = Agent(name="Researcher")
agent2 = Agent(name="Writer")

# Create a task
task = Task(
    description="Write a blog post about the future of AI",
    agents=[agent1, agent2],
)

# Run the task
task.run()
```

### ✨ Star History

[![Star History Chart](https://api.star-history.com/svg?repos=ishandutta2007/open-swarm-ai-agents&type=date&legend=top-left)](https://www.star-history.com/#ishandutta2007/open-swarm-ai-agents&type=date&legend=top-left)


## Contributing

We welcome contributions from the community! If you'd like to contribute, please read our [contributing guidelines](CONTRIBUTING.md) to get started.
-   **💬 [Discord](https://discord.com/invite/jc4xtF58Ve):** Chat with us on Discord for real-time support and discussions.
-   **🐦 [Twitter](https://twitter.com/ishandutta2007):** Follow us on Twitter for the latest news and updates.
-   **🐦 [Github](https://github.com/ishandutta2007):** Follow me on Github for the latest commits and updates.

## License

Open Swarm AI Agents is licensed under the [MIT License](LICENSE).
