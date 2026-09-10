# 05_Data_or_Sample_Input

This folder contains the proposed labelled test prompts for evaluating the Secure AI Chatbot Against Prompt Injection Attacks.

## Files
- `prompt_injection_test_cases.csv` - combined test set (30 benign + 30 malicious prompts).
- `benign_prompts.csv` - legitimate prompts that should be allowed.
- `malicious_prompts.csv` - synthetic prompt-injection attempts that should be blocked, logged and followed by a warning.

## Scope
The samples only cover prompt injection delivered through the chatbot user-input layer. Training-data poisoning, model backdoors, infrastructure attacks and RAG-specific indirect injection are outside the current prototype scope.

## Labels
- `safe` -> expected action: `allow_to_chatbot`
- `malicious` -> expected action: `block_log_warn`

The test prompts are synthetic and are intended for controlled testing of the group's own prototype. They do not contain real credentials or personal data.
