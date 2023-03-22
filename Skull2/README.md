# Shellcode Loader
Shellcode injection is an ancient technique used to inject shellcode into a process via the CreateRemoteThread WinAPI (don't use this). This technique is often used to evade static analysis, as the injected code is not stored on disk and is executed directly in memory.

## for skids such as myself
- This is a POC and should only be used for educational purposes 
- This is not a full fledged shellcode loader, many features are missing
- Build the solution yourself and note that you are building a malicious binary


## reference
- https://www.ired.team/offensive-security/code-injection-process-injection/process-injection