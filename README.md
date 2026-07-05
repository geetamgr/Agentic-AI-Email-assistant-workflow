# Agentic-AI--Email-assistant-workflow
This agentic workflow can carry out various tasks related to email management, including sending emails, searching for emails from a specific sender, and deleting emails. You’ll give it natural language instructions - like “check unread emails from my boss” or “delete the Happy Hour email” - and see how it selects the right tools.
<img width="1284" height="694" alt="image" src="https://github.com/user-attachments/assets/51bccff7-af85-4008-9427-219f2bc78381" />
You will be able to connect an LLM to tools with AISuite, give natural language instructions, and observe how the agent selects, executes, and validates multi-step tasks such as searching, sending, and deleting emails.

<br>
Final Takeaways
In this ungraded lab, you explored how an LLM email agent interacts with a simulated email service using tool calls.
Tool calling allows LLMs to go beyond text generation—enabling them to call functions (tools) and complete multi-step tasks.
The set of available tools determines what the agent can and cannot do (e.g., without delete_email, it cannot remove messages).
Clear docstrings and consistent behavior help the LLM select the right tool for each step.
AISuite manages the interaction layer: exposing Python functions as tools, accepting parameters, making API requests, and returning results.
Observing the full workflow—from prompt → tool calls → outputs → final response—is key to understanding and improving how agents reason and act.
