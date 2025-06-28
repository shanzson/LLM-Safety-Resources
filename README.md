# LLM Security 

- [Owasp LLM Top 10](https://genai.owasp.org/llm-top-10/)
- [AI incidence Database](https://github.com/responsible-ai-collaborative/aiid)
- [LLM Attacks practical hands on lab](https://portswigger.net/web-security/llm-attacks)

## OS Command injection Notes
- [Command injection playlist - by Rana Khalil](https://www.youtube.com/watch?v=UBWMLFbjPBc&list=PLuyTk2_mYISK9ywsFZZOT1LuO3Eb7Wq5q)
### Commands
| Purpose of command | Linux | Windows |
|-------------------|-------|---------|
| Name of current user | whoami | whoami |
| Operating system | uname -a | ver |
| Network configuration | ifconfig | ipconfig /all |
| Network connections | netstat -an | netstat -an |
| Running processes | ps -ef | tasklist |
| Output file contents | cat ||
| Delay in giving response | sleep ||
| Blind command injection (10 sec) | ping -c 10 127.0.0.1 ||
| & whoami > /var/www/static/whoami.txt ||




