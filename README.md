# Simple-Langgraph-workflow
This code builds a simple LLM-powered Q&amp;A workflow using LangGraph and Groq. It defines a state to store the question and answer, passes the question to an LLM through the llm_qa node, and returns the generated response in the updated state. The graph follows the flow: START → llm_qa → END.
