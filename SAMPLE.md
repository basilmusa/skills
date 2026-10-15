
This should be configurable to "X" number of questions instead of 12 using a skill.

```
I want you to ask me questions, identify  gaps and future proofing questions. Keep it for the important
stuff. Dont ask trivial questions. You only have 12 questions to ask so focus on the important ones. For
each question give me your recommendation. Before asking the next question wait for my confirmation
please to agree on a decision.
```

Another variant:

```
I want you to ask me questions, identify  gaps and future proofing questions. Keep it for the important
stuff. Dont ask trivial questions. Dont ask questions that you are confident of the way forward with
them and that are already settled. You only have 4 questions to ask so focus on the important ones. For
each question give me your recommendation. Before asking the next question wait for my confirmation
please to agree on a decision.
```

Revise a change prompt:
```
Can you please revise the openspec change <<change_name>>, try to identify any design flaws, unclear descriptions, lack of clarity in explanation, low quality specs, etc. And explain
  them to me before starting modification of these files.
```

Git commit message:

```
Please give me a medium sized git commit message explaining the changes that were done in this openspec change, use the git message format and conventions.
```

Sample prompt to create all artifacts before apply, notice how we explicitly instruct it to follow rules in AGENTS.md:

```
/opsx:ff page-content-rpc

Create change 5 as defined in TREE-COMPONENT.md
Follow its "How to read this document" rules and AGENTS.md
```
