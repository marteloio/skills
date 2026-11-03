# Marteloio

Work on your family's tree from a conversation with Claude: who is in it, one person's record, a search of your workspace, and, after you approve each change, a person added or corrected.

## Use it

Ask Claude who is in your tree, about one person in it, or to search your workspace by name. Claude can add a person or correct a record. It shows a preview of every change and makes it only after you approve.

Sign in with your Marteloio account when you connect the Marteloio connector.

## Install

In Claude, add the Marteloio plugin from the directory. In another agent, install the skills with:

```bash
npx skills add marteloio/skills
```

and add the Marteloio connector, `https://mcp.martelo.io/mcp`, in that agent's connector or MCP settings.

## Data

The plugin sends the questions you ask and the changes you approve to your Marteloio account through https://mcp.martelo.io, and nowhere else. The plugin stores nothing itself.
