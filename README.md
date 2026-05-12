# Gandalf | Lakera-writeups
The Gandalf challenge by Lakera is a prompt injection challenge where your goal is to devise creative prompts to convince or trick Gandalf into revealing its secret password, simulating real-world scenarios where attackers attempt to circumvent AI safeguards.

Link to the live challenge (gandalf.lakera.ai)
## Challenge Architecture
The architecture uses a User Input Guard (checks prompts for direct or indirect password extraction attempts), a System Prompt (gives the model a secret password and directive not to reveal it), and an Output Guard

## Level Breakdown 
Each level includes:
- The level's defense description (e.g. "I double-check my response doesn't contain the password")
- The prompt(s) you used
- Gandalf's response (redact or partially hide the password if you prefer)
- Why it worked , the conceptual explanation 
