# Soft Drink Agent

A Salesforce-based AI agent application powered by Einstein AI, built to handle soft drink orders and provide intelligent customer support through Salesforce bots and Agentforce.

## Overview

This project demonstrates an advanced Salesforce implementation featuring:

- **AI-Powered Bot**: A sophisticated Soft Drink Agent bot built with Salesforce Agentforce
- **Case Management**: Intelligent case handling and updates with AI capabilities
- **Order Management**: Complete soft drink order lifecycle management
- **Flex Chat**: Customer service flex templates for seamless chat interactions
- **Account Intelligence**: Prompt-based account summary generation using AI
- **Data Cloud Integration**: Advanced data handling with Salesforce Data Cloud

## Features

### Core Components

- **Soft Drink Agent Bot**: Automated customer service bot for order processing and support
- **Case Copilot**: AI-assisted case management system
- **Order Management**: Track and manage soft drink orders efficiently
- **Account Summaries**: Automated account analysis and insights
- **Flex Templates**: Custom Lightning Web Components for Flex chat UI
- **Workflows & Flows**: Automated business processes for task creation, returns, and order updates

### Technology Stack

- **Salesforce Metadata**: Custom objects, fields, and layouts
- **Apex**: Backend business logic for controllers and handlers
- **Lightning Web Components (LWC)**: Modern UI components
- **Salesforce Flows**: Process automation
- **Einstein AI**: Intelligent prompts and automations

## Project Structure

```
force-app/main/default/
├── classes/              # Apex controllers and handlers
├── lwc/                  # Lightning Web Components
├── flows/                # Salesforce Flows
├── bots/                 # Agentforce bot definitions
├── layouts/              # Custom page layouts
├── flexipages/           # Flex chat page configurations
├── objects/              # Custom object definitions
├── tabs/                 # Custom tabs
├── profiles/             # Permission profiles
└── aiAuthoringBundles/   # AI prompt bundles
```

## Getting Started

### Prerequisites

- Salesforce CLI installed
- Salesforce Developer Org or Sandbox
- Node.js 14+ for development tools

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/Soft-Drink-Agent.git
cd Soft-Drink-Agent
```

2. Install dependencies:
```bash
npm install
```

3. Authorize your Salesforce org:
```bash
sfdx auth:web:login -a my-org
```

4. Deploy to your org:
```bash
sfdx force:source:deploy -p force-app -u my-org
```

## Development

### Running Tests

```bash
npm run test:unit        # Run unit tests
npm run test:unit:watch  # Run tests in watch mode
npm run test:unit:coverage # Generate coverage report
```

### Code Quality

```bash
npm run lint             # Run ESLint
npm run prettier         # Format code
npm run prettier:verify  # Verify code formatting
```

## Key Components

### Apex Classes

- **SoftDrinkOrderController**: Manages order operations
- **SoftDrinkOrderStatus**: Tracks order status
- **CaseCopilot**: AI-powered case management
- **AccountSummaryPrompt**: Generates intelligent account summaries
- **UserInfoHandler**: Handles user information
- **ZipCodeName**: Location-based utilities

### Flows

- **Soft_Drink_Flow**: Main order management flow
- **Create_a_Task_Flow**: Automated task creation
- **Initiate_Return**: Returns processing flow

### Custom Objects

- **Soft Drink** (`Soft_Drink__c`): Product catalog
- **Soft Drink Order** (`Soft_Drink_Order__c`): Order records

## Contributing

Contributions are welcome! Please ensure code follows the formatting standards:

```bash
npm run prettier
npm run lint
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact & Support

For questions or support, please reach out through GitHub issues.

---

Built with Salesforce and Agentforce for intelligent automation and customer engagement.
