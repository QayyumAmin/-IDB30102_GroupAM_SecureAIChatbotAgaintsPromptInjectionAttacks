# Expected Outcomes

No final performance numbers are claimed at proposal stage. The expected direction of the results is:

1. The secured chatbot should allow fewer prompt-injection attempts to pass through than the baseline chatbot.
2. Legitimate prompts should continue to be accepted in most cases, with a low false-positive rate.
3. The security layer should add only a limited amount of response-time overhead for normal chatbot use.
4. Detected malicious prompts should be blocked, recorded in the security log and followed by a warning message.
5. Testing should also reveal limitations and edge cases that can be used to refine the detector in a later increment.
