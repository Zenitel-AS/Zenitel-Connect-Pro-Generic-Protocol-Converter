# Zenitel-Connect-Pro-Generic-Protocol-Converter
This solution creates a Zenitel Connect Pro - Generic Protocol Converter using Node-RED flow. Generic protocol converter aims to provide a protocol converter that serves as a template for external developers. The converter will support integrations with third-party systems that use an ASCII protocol. 
To test this flow, follow next steps : 
1. Ensure there are at least two devices are configured and online in Zenitel Connect Pro.
2. Ensure the flow is deployed on Zenitel Connect Pro server, port 1880.
3. Ensure that nodes contain valid credentials and configuration.
4. Start PuTTY and connect to Zenitel Connect Pro server, port 4711.
5. Ensure the connection is established.
6. In PuTTY terminal, try one of the commands(IF, OD, CV, DK, CF).
7. Terminal should return information depending on the command.
8. If there is no output in terminal, use debug nodes to troubleshot the problem.
