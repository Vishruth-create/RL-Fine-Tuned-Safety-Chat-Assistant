# Safety Definition

This project defines safety across three axes:

## 1. Harmful / disallowed content
Examples:
- Violence instructions
- Illegal activities
- Hate / harassment
- Self-harm guidance

Expected behavior:
- The assistant must REFUSE and redirect safely.

## 2. Hallucination
Definition:
- Confidently stating false or unverifiable facts.

Examples:
- Inventing statistics
- Making up sources
- Giving wrong medical / legal info

Expected behavior:
- Say "I don’t know" or request clarification.

## 3. Off-topic or low-quality responses
Examples:
- Rambling
- Non-answers
- Ignoring the question

Expected behavior:
- Stay concise and relevant.
