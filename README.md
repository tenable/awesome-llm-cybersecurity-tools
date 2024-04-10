# Awesome Large Language Model Tools for Cybersecurity Research

## Reverse Engineering

<!-- should we have a "### Developed by Tenable" subsection here? -->

- [G-3PO: A Protocol Droid for Ghidra](https://github.com/tenable/ghidra_tools/tree/main/g3po): An AI assistant developed by Olivia Lucca Fraser at Tenable for analysing and annotating decompiled code in Ghidra, which queries OpenAI and/or Anthropic's language models. See [this writeup on the Tenable tech blog](https://medium.com/tenable-techblog/g-3po-a-protocol-droid-for-ghidra-4b46fa72f1ff) for details.
- [ai for Pwndbg](https://github.com/tenable/pwndbg/blob/dev/pwndbg/commands/ai.py): Your trusty AI debugging sidekick, developed by Olivia Lucca Fraser at Tenable as a Pwndbg command.
- [ai for GEF](https://github.com/tenable/gef-extras): Same as above, but implemented as a GEF command. Developed by Olivia Lucca Fraser at Tenable.

<!-- Not by Tenable -->

- [Gepetto](https://github.com/JusticeRage/Gepetto): An IDA Pro plugin that queries GPT models for explanatory comments and meaningful variable names (like G-3PO for IDA Pro). Developed by Ivan Kwiatkowski.
- [GPT-WPRE](https://github.com/moyix/gpt-wpre): Whole-program Reverse Engineering with GPT-3. This is a little toy prototype of a tool that attempts to summarize a whole binary using GPT-3 (specifically the text-davinci-003 model), based on decompiled code provided by Ghidra. Developed by Brendan Dolan-Gavitt.
- [IATelligence](https://github.com/fr0gger/IATelligence): IATelligence is a Python script that extracts the Import Address Table (IAT) from a PE file and uses OpenAI's GPT-3 model to provide details about each Windows API imported by the file. The script also searches for related MITRE ATT&CK techniques and explains how the API could potentially be used by attackers. Developed by Thomas Roccia.
- [VulChatGPT](https://github.com/ke0z/vulchatgpt): An IDA Pro plugin which helps in finding vulnerabilities in binaries.

## Network Analysis

- [Burp Extension for GPT](https://github.com/tenable/Burp-extension-for-GPT): A BurpSuite plugin, developed by Tenable, that uses GPT to analyse HTTP requests and responses. Developed by Yossi Nisani at Tenable.

## Cloud Security

- [EscalateGPT](https://github.com/Tenable/EscalateGPT): Uses GPT to discover privilege escalation vulnerabilities in misconfigured Identity Access and Management (IAM) policies for AWS. Developed by Yossi Nisani at Tenable.

## Assistants

- [PentestGPT](https://github.com/GreyDGL/PentestGPT) - A helpful pentest assistant, helps pentesters to leverage the power of LLM and gain insigtful AI outputs.
- [ChatWithBinary](https://github.com/retr0reg/ChatWithBinary) - A helpful assistant the allows diagnosing binary files.

## Thread detection

- [Galah](https://github.com/0x4D31/galah) - An open source tool which creates a honeypot based on LLM.


## Proofs of Concept

### Hacking LLMs

- [Indirect Prompt Injections](https://github.com/greshake/llm-security): Proof of concept code for indirect prompt injection attacks, by Kai Greshake.

### LLM-Driven Malware

- [LLMorphism](https://github.com/SPTHvx/SPTH/tree/master/viruses/files/LLMorphism): A self-replicating agent that uses GPT-3.5 as a metamorphic engine, by Second Part to Hell.
- [Darwin-GPT](https://github.com/muellerberndt/darwin-gpt): A minimal self-replicating agent based on GPT-3.5/4, by Bernhard Mueller.
