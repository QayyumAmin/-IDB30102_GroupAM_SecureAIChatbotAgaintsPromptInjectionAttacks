# Member 4 - Proposed Evaluation Plan (README snippet)

## Proposed evaluation plan

**Baseline:** Run the labelled prompt set on the chatbot without the proposed prompt-injection security layer.

**Test environment:** Run the same prompt set on the secured prototype containing prompt preprocessing, prompt-injection detection, allow/block decision, security logging and warning functions.

**Dataset / sample input:** A balanced synthetic test set containing 30 benign prompts and 30 prompt-injection prompts. The malicious samples cover direct instruction override, system-prompt extraction, role manipulation, instruction hijacking and simple obfuscation.

**Metrics:** Prompt Injection Detection Rate, Attack Success Rate (ASR), False Positive Rate (FPR), Benign Prompt Acceptance Rate, response-time/latency overhead and security-log completion.

**Evaluation goal:** Determine whether the security layer reduces malicious prompts reaching the chatbot while maintaining normal use and acceptable response time for legitimate prompts.
