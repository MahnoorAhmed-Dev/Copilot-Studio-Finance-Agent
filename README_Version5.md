# Copilot Studio Policy Agent

A Microsoft Copilot Studio agent that connects to a SharePoint site containing JBS policy documents, enabling users to query policies directly from their Teams channel. The agent leverages integrated SharePoint and Excel actions to retrieve, check in, and provide details about policy files.

---

## Overview

Copilot Studio Policy Agent allows users to:

- Ask questions about JBS policy documents directly in Teams
- Retrieve document details and properties from SharePoint
- Check in files using SharePoint actions
- Query Excel data associated with policy documentation

The agent is deployed to a Teams channel and uses SharePoint and Excel as knowledge sources for fast, authoritative answers.

---

## Features

**For Users**
- Query any JBS policy document in natural language
- Retrieve document properties from SharePoint
- Get rows and data from associated Excel policy sheets
- Check in files to SharePoint directly

**For Admins**
- Configure agent connection to SharePoint policy document library
- Set up Excel data integrations
- Deploy and manage the agent in Copilot Studio and Teams

---

## Tech Stack

- **Copilot Studio**: For agent provisioning and workflow orchestration
- **SharePoint Online**: Stores all JBS policy documents
- **Microsoft Excel (Online)**: Hosts policy-related datasets
- **Microsoft Teams**: End-user deployment and interaction

---

## Installation

Clone the repository:

```
git clone https://github.com/MahnoorAhmed-Dev/Copilot-Studio-Policy-Agent.git
cd Copilot-Studio-Policy-Agent
```

Set up your Copilot Studio environment and provision a new agent using this repository’s code/configuration.

---

## Configuration

**SharePoint Setup**
- Ensure your SharePoint site contains the necessary policy documents
- Grant the agent access to the document library
- Configure SharePoint actions: Check In File, Get Properties

**Excel Setup**
- Store policy data in a dedicated Excel file on SharePoint
- Grant agent access to this Excel file
- Configure the Get Rows action for Excel integration

**Licensing**
- Copilot Studio License: Required for agent provisioning ([details](https://learn.microsoft.com/en-us/microsoft-copilot-studio/licensing))
- SharePoint License: Required for document access ([details](https://learn.microsoft.com/en-us/sharepoint/sharepoint-licensing-overview))

---

## Usage

**For Users**
- Access the Teams channel where the agent is deployed
- Ask policy-related questions or request document actions

**For Admins**
- Monitor agent performance in Copilot Studio
- Update SharePoint/Excel integrations as policies evolve

---

## Contributing

1. Fork the project
2. Create your feature branch (`git checkout -b feature/NewFeature`)
3. Commit your changes (`git commit -m 'Add NewFeature'`)
4. Push to the branch (`git push origin feature/NewFeature`)
5. Open a Pull Request

---

## License

This project requires valid Copilot Studio and SharePoint licenses for use. See their respective documentation for terms and conditions.

---

## Support

For support, open an issue in this repository or contact [Mahnoor Ahmed-Dev](https://github.com/MahnoorAhmed-Dev).

---

## Roadmap

- Enhanced natural language understanding for policy queries
- Integration with additional knowledge sources
- Advanced analytics and reporting for admins
- Multi-language support

---

## Acknowledgments

- Microsoft Copilot Studio team
- SharePoint development community
- Microsoft Teams and Excel teams
