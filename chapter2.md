# Chapter 2: Credential Hygiene: Protecting the Keys to the Kingdom

## The Vulnerability of Automation

In a sovereign AI workforce, your API keys and Personal Access Tokens (PATs) are more than just passwords; they are the delegated authority of your entire business. If a GitHub PAT or a Stripe Secret Key is compromised, the attacker doesn't just see your data—they inherit your ability to act. For the Aussie Architect, credential hygiene is the first line of defense against global exploitation.

### The Sovereign Credential Protocol
1.  **Scope Minimization:** Never use 'Full Access' tokens. We teach the principle of 'Least Privilege,' where each agent (e.g., the Hostinger MCP) only has the specific permissions required to perform its task.
2.  **Ephemeral Secrets:** We implement automated rotation for all high-risk keys. Using the Aussie Node's secure environment, we ensure that secrets are never hard-coded and are only injected at the moment of execution.
3.  **Regional Monitoring:** We monitor the logs of our MCP servers for any 'out-of-jurisdiction' calls. If a tool call originating from outside our Australian IP range is detected, the Taskmaster automatically triggers a 'Sovereign Lock' on all credentials.

## Fortifying the Pipeline

In this chapter, we walk through the setup of a secure 'Vault' on your Aussie Node. You will learn how to use environment variables and encrypted secret managers to ensure that your workforce remains autonomous while your credentials remain invisible. We are moving from 'security by obscurity' to 'security by architecture.'
