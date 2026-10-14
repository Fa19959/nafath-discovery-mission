Version: NAFATH-V3
Track: <one of: Software | AI | Mobile | Networking | Cybersecurity | Data>

## Overview
The government wants to add an AI chat assistant to its mobile app. The assistant will help citizens find information about government services. It should give clear and correct answers. Six IT fields can help make the assistant safe and useful. Software helps manage updates. AI helps answer questions. Mobile technology makes the service easy to use. Networking connects the app to its services. Cybersecurity protects information. Data management helps keep information safe and organized. All these fields are important for building a reliable government service.
## Software
Semantic versioning uses three numbers: MAJOR, MINOR, and PATCH. MAJOR changes may break compatibility with older versions. MINOR changes add new features without breaking compatibility. PATCH changes fix bugs without adding new features. For the government assistant, this system helps the team track updates and understand their impact.

Source: https://semver.org/
## AI
Retrieval-Augmented Generation (RAG) helps an AI assistant find information from trusted documents before answering questions. For example, the assistant can use official government websites to answer questions about services and required documents. This can help make answers more accurate. The information must be updated and reliable. The assistant should also say when it cannot find a clear answer.

Source: https://cloud.google.com/use-cases/retrieval-augmented-generation
## Mobile
App Transport Security (ATS) is a security feature in iOS. It helps protect data sent between the app and the server. ATS requires secure HTTPS connections by default. If the app uses a plain HTTP connection, iOS may block it. The development team should use HTTPS for all API connections to help protect citizens’ information.

Source: https://developer.apple.com/documentation/security/preventing-insecure-network-connections
## Networking
IPv4 and IPv6 are two types of internet addresses. IPv4 uses 32-bit addresses, while IPv6 uses 128-bit addresses. IPv6 provides many more addresses for connected devices. The government app should work with different networks and devices. The development team should test both IPv4 and IPv6 connections to help citizens use the service reliably.

Source: https://www.cloudflare.com/learning/network-layer/what-is-ipv6/
## Cybersecurity
Prompt injection is a security risk for AI systems. Direct prompt injection happens when a user gives the AI harmful instructions. Indirect prompt injection can be hidden in a webpage or document. To reduce this risk, the assistant should treat external content as untrusted. The team should also limit the AI’s permissions and test it regularly.

Source: https://genai.owasp.org/llmrisk/llm01-prompt-injection/
## Data
Anonymization and pseudonymization help protect personal information. Anonymization removes personal details so a person cannot reasonably be identified. Pseudonymization replaces personal details with codes, but the person may still be identified using extra information. The government assistant should collect only the data it needs and protect chat records. This helps respect citizens’ privacy.

Source: https://www.edpb.europa.eu/
## Misconception in My Track
A common misconception is that RAG always gives correct answers. RAG helps the AI find information from trusted documents, but it does not guarantee that every answer is correct. The AI may misunderstand the information or use old data. The team should use updated sources, test the assistant, and check its answers regularly. This can help make the service more reliable for citizens.
## Open Question
How can we make sure the AI assistant gives correct and safe answers to citizens?
