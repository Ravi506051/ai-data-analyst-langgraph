# Multi-Agent Data Analyst

A CSV analysis assistant built around a multi-agent workflow. The application explores a dataset, plans useful analysis, generates and executes Python code, and presents charts with natural-language insights through a Streamlit interface.

## Agent workflow
1. **Data exploration** — inspect columns, types, missing values and summary statistics.
2. **Analysis planning** — select relevant questions and visualizations.
3. **Code generation and execution** — create analysis code and run it in the configured execution environment.
4. **Review and explanation** — interpret generated outputs and communicate findings.

## Technology
Python · LangGraph · Streamlit · Pandas · Plotly · LLM Integration

## Getting started
```bash
git clone https://github.com/Ravi506051/ai-data-analyst-langgraph.git
cd ai-data-analyst-langgraph
python -m venv .venv
# Windows: .venv\\Scripts\\activate
pip install -r requirements.txt
```
Configure the provider credentials required by the project using environment variables or the documented secrets mechanism. Start the app using the Streamlit command specified in the repository.

## Safety and reliability
Executing generated code is a security-sensitive operation. Keep execution isolated, restrict filesystem and network access, enforce resource limits and validate uploaded files. Do not run generated code with unrestricted access to user data or credentials.

## Evaluation
Test with CSV files containing missing values, mixed data types, large row counts and ambiguous column names. Check that charts and written conclusions match the actual computed results.

## Future improvements
Add deterministic analysis tools, execution timeouts, audit logs, typed agent state and regression tests for generated analyses.

## Maintainer
**Ravi Kumar Rao** · [GitHub](https://github.com/Ravi506051)
