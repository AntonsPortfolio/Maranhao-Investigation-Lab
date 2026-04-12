# Maranhao Investigation Lab 
--> IR Report <--

### **Scenario:** 

A gaming enthusiast in a known organization has downloaded what they believed to be a free mod launcher for a popular survival game. The file which downloaded contained a ZIP archive with an installer that looked like a standard game setup package.

Eager to try it, the gamer downloaded the file and executed the installer. Unbeknownst to him, the program silently dropped hidden files into a directory. One of these files was configured to persist through registry keys, ensuring it would relaunch every time the system started.

Within a short time, unusual activity triggered alerts on the Security Operations Center's (SOC) in GOAT Company's monitoring dashboard. The gamer's machine was observed making outbound requests to a malicious domain and a suspicious external IP address. Endpoint logs also showed evidence of process injection, suggesting credential theft. The Security Operations Center (SOC) quickly isolated the machine and saved a full disk image for your analysis.

### **Methodology**
