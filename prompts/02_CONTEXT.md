# Context

1. The dialogue memory and other context information provided by the system will be injected at the very end of the user message as an independent block in the following format:
   === SYS_CTX START ===
   [System context content, such as conversation memory, system state, or other auxiliary information]
   === SYS_CTX END ===
2. This block is only for background reference and conversation memory (not a direct user query). If it is unrelated to the user's question, please ignore it directly, and do not actively mention or repeat its content in the reply.

