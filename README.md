# Advanced AI Agents

An open source collection of sovereign, autonomous, and multi-agent systems designed for various industries and tasks. This repository features both single-agent applications and complex multi-agent teams.

## 📁 Repository Structure

The project is organized into two main categories:

### 1. [multi_agent_apps](./multi_agent_apps)

A collection of collaborative agent systems where multiple agents work together to achieve complex goals.

- **[agent_teams](./multi_agent_apps/agent_teams)**: Specialized teams like the `ai_seo_audit_team` for comprehensive SEO Analysis.
- **[ai_news_and_podcast_agents](./multi_agent_apps/ai_news_and_podcast_agents)**: Automated content creation pipelines for news and media.
- **[ai_Self-Evolving_agent](./multi_agent_apps/ai_Self-Evolving_agent)**: Research into agents that can improve their own logic.
- **[multi_agent_researcher](./multi_agent_researcher)**: Deep research orchestration using multiple LLM perspectives.

### 2. [single_agent_apps](./single_agent_apps)

Focused, sovereign agents designed to perform specific tasks with high efficiency.

- **[windows_use_autonomous_agent](./single_agent_apps/windows_use_autonomous_agent)**: An agent capable of interacting directly with the Windows OS.
- **[ai_consultant_agent](./single_agent_apps/ai_consultant_agent)**: Professional advisory agent for business insights.
- **[ai_investment_agent](./single_agent_apps/ai_investment_agent)**: Financial analysis and portfolio management assistant.
- **[ai_deep_research_agent](./single_agent_apps/ai_deep_research_agent)**: Focused deep-dive research tools.

## 🚀 Getting Started

Most agents are built using Python. To get started:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/politewolf/ai-agents.git
   cd ai-agents
   ```

2. **Set up a Virtual Environment:**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies:**
   Navigate to a specific agent's folder and install its requirements:
   ```bash
   cd multi_agent_apps/agent_teams/ai_seo_audit_team
   pip install -r requirements.txt
   ```

## 📜 License

This project is licensed under the MIT License.
