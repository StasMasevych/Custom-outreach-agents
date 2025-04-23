# Customer Outreach Agents

A Python-based autonomous agent system that automates customer outreach and lead nurturing using CrewAI. This project demonstrates how specialized sales agents can collaborate to analyze leads, craft personalized outreach, and drive business growth with minimal manual effort.

## 🚀 Features

- **Agentic Sales Pipeline**: Multiple agents (Sales Representative, Lead Sales Representative) work together to analyze leads and generate outreach campaigns.
- **Automated Lead Profiling**: Agents gather and synthesize information from files, directories, and web sources.
- **Personalized Outreach Generation**: Crafts tailored email drafts and engagement strategies for key decision-makers.
- **Sentiment Analysis Tool**: Ensures communications are positive and engaging.
- **Modular & Extensible**: Add or modify agents and tools for custom sales workflows.
- **Environment Configurable**: API keys and settings via `utils.py` or environment variables.

## 🧩 Main Agents

- **Sales Representative**: Identifies and profiles high-value leads, focusing on company background, key personnel, and business needs.
- **Lead Sales Representative**: Crafts and personalizes outreach campaigns to engage and nurture leads, aiming for conversion.

## 🏗️ How It Works

1. **Setup**: Configure your API keys in `utils.py` or as environment variables.
2. **Run the App**: Execute `main.py` to start the agent workflow.
3. **Agent Collaboration**: Agents analyze leads, generate reports, and create personalized outreach drafts.
4. **Output**: Produces a lead profile report and a set of personalized outreach drafts for your target company.

## 📦 Installation

```bash
git clone <repo-url>
cd customer-outreach-agents
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

## ⚙️ Usage

1. Set up your API keys in `utils.py` or as environment variables.
2. Run the main script:
   ```bash
   python main.py
   ```
3. Edit `main.py` to customize lead details, agent tasks, or workflow.

## 📝 Example

```
$ python main.py
[SalesRepresentative] Profiling lead: Voltage Group...
[LeadSalesRepresentative] Creating personalized outreach campaign...
Output: Lead profile report and outreach drafts printed to console or saved to file.
```

## 🛠️ Customization

- Add new agents or tools in `main.py` or separate files.
- Modify agent logic for your sales process.
- Integrate with additional APIs for more capabilities.

## 📚 Dependencies

- Python 3.8+
- CrewAI (or your agent framework)
- crewai_tools, pydantic, and other packages in `requirements.txt`

## 🤝 Contributing

Pull requests are welcome! For major changes, open an issue first to discuss what you want to change.

---
Feel free to modify or extend the agents for your own customer outreach and sales automation needs!
