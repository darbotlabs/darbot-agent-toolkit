# Darbot Agent Toolkit

[![Build Status](https://github.com/darbotlabs/darbot-agent-toolkit/actions/workflows/ci.yml/badge.svg)](https://github.com/darbotlabs/darbot-agent-toolkit/actions/workflows/ci.yml)
[![codecov](https://codecov.io/gh/darbotlabs/darbot-agent-toolkit/branch/main/graph/badge.svg)](https://codecov.io/gh/darbotlabs/darbot-agent-toolkit)

Darbot Agent Toolkit is a comprehensive framework for building intelligent agents and conversational AI applications. Whether you are new or a seasoned developer, Darbot Agent Toolkit provides the tools and libraries you need to create, build, debug, test, and deploy sophisticated agent-based solutions.

<img width="2405" alt="Darbot Agent Toolkit" src="https://github.com/user-attachments/assets/84fa9339-cc14-43fc-bef2-22fc8513e57c" />


Darbot Agent Toolkit provides support for the end-to-end development journey, including:

- Support for all major platform extensibility surfaces, including conversational AI agents, chatbots, and intelligent assistants.
- Seamless integration with modern AI frameworks and SDKs for building self-hosted agents.
- Seamless integration with conversational AI libraries to build intelligent chatbots with ease.
- Integrations with the tools, languages, and frameworks you know and love.
- Scaffolds for getting started fast with common agent scenarios and conversational AI patterns.
- Rapid iteration with full stack debugging, hot reload, and secure tunneling.
- Simplified authentication and authorization.
- Integrated support for hosting, data storage, and serverless functions.
- CI/CD actions for GitHub and Azure DevOps to deliver agents with confidence.

## Get Started

Pick your preferred tool to get started:

- For JavaScript and TypeScript developers, install [Darbot Agent Toolkit for Visual Studio Code](https://github.com/darbotlabs/darbot-agent-toolkit).
- For .NET developers, install [Darbot Agent Toolkit for Visual Studio](https://github.com/darbotlabs/darbot-agent-toolkit).
- For command line users, install [Darbot Agent Toolkit CLI](https://github.com/darbotlabs/darbot-agent-toolkit): `npm install -g @darbot/agent-toolkit-cli`

Visit [Darbot Agent Toolkit documentation](https://github.com/darbotlabs/darbot-agent-toolkit) to get started with building agents and applications.

## Roadmap

Darbot Agent Toolkit for Visual Studio, Visual Studio Code, and Command Line Interface (CLI) will be updated regularly with new features and bug fixes to continuously improve the end-to-end agent development experience. Visit our [Changelog](https://github.com/darbotlabs/darbot-agent-toolkit/blob/main/CHANGELOG.md) to see what's available for you now and see [product roadmap](https://github.com/darbotlabs/darbot-agent-toolkit/blob/main/ROADMAP.md) to find out what's coming.

## Support Policy

Darbot Agent Toolkit products will follow [Modern Lifecycle Policy](https://docs.microsoft.com/lifecycle/policies/modern) and extended support as described in our [lifecycle and support document](https://github.com/darbotlabs/darbot-agent-toolkit/blob/main/SUPPORT.md).

## Feedback

- Ask a question on [Stack Overflow](https://stackoverflow.com/questions/tagged/darbot-agent-toolkit)
- [Request a new feature](https://github.com/darbotlabs/darbot-agent-toolkit/issues/new?assignees=&labels=&template=feature_request.md&title=)
- [File an issue](https://github.com/darbotlabs/darbot-agent-toolkit/issues/new?assignees=&labels=&template=bug_report.md&title=)
- Send an email to support@darbotlabs.com to chat with the product team
- Report security issues and bugs to security@darbotlabs.com

## Repository

This repository contains the following packages:
| Package | Description |
| ----------- | ----------- |
| **Darbot Agent Toolkit for Visual Studio Code** [packages/vscode-extension](https://github.com/darbotlabs/darbot-agent-toolkit/tree/main/packages/vscode-extension) | Agent Toolkit for Visual Studio Code enables you to scaffold, run, debug, and deploy custom agent applications directly from Visual Studio Code. It provides all the features of the Agent Toolkit CLI tool integrated into the IDE, as well as easy access to more samples, docs and tools. |
| **Darbot Agent Toolkit CLI** [packages/cli](https://github.com/darbotlabs/darbot-agent-toolkit/tree/main/packages/cli) | Whether you prefer keyboard-centric developer operations, or you are automating your CI/CD pipeline, the Agent Toolkit CLI tool offers the same features as the IDE extensions. |
| **SDK** [packages/sdk](https://github.com/darbotlabs/darbot-agent-toolkit/tree/main/packages/sdk) | The main code library encapsulating simple authentication for both client and server-side code tailored for agent developers. |
| **API** [packages/api](https://github.com/darbotlabs/darbot-agent-toolkit/tree/main/packages/api) | The API package is a collection of contracts supported by the IDE Extensions and CLI. It enables developers to write plugins to extend the toolkit with new capabilities. |
| **Core** [packages/fx-core](https://github.com/darbotlabs/darbot-agent-toolkit/tree/main/packages/fx-core) | The Core package centralizes implementation of capabilities shared by the IDE Extensions and the CLI. |
| **Azure Functions Support** [packages/function-extension](https://github.com/darbotlabs/darbot-agent-toolkit/tree/main/packages/function-extension) | Agent Toolkit helps developers include server-side code in their agent applications backed by [Azure Functions](https://docs.microsoft.com/azure/azure-functions/). This plugin adds support to simplify the integration of an authentication-aware Azure Function into your agent app. |
| **Spec Parser** [packages/spec-parser](https://github.com/darbotlabs/darbot-agent-toolkit/tree/main/packages/spec-parser) | Agent Toolkit automates the process of generating API-based extensions and Adaptive Cards by parsing the OpenAPI description document. |

## Contributions

This project welcomes contributions and suggestions. Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit [Contributor License Agreement](https://cla.opensource.microsoft.com).

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

- Download our latest releases [here](https://github.com/darbotlabs/darbot-agent-toolkit/releases)
- Check out our [contribution](https://github.com/darbotlabs/darbot-agent-toolkit/blob/main/CONTRIBUTING.md) page for more information

## Telemetry

Darbot Agent Toolkit collects usage data and sends it to Darbotlabs to help improve our products and services. Read our [Privacy Statement](https://github.com/darbotlabs/darbot-agent-toolkit/blob/main/PRIVACY.md) and [Data Collection Notice](https://github.com/darbotlabs/darbot-agent-toolkit/blob/main/DATA_COLLECTION.md) to learn more. Learn more in our [FAQ](https://github.com/darbotlabs/darbot-agent-toolkit/blob/main/FAQ.md).

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Darbotlabs
trademarks or logos is subject to and must follow Darbotlabs's Trademark & Brand Guidelines.
Use of Darbotlabs trademarks or logos in modified versions of this project must not cause confusion or imply Darbotlabs sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.

## Code of Conduct

This project has adopted the [Contributor Covenant Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/).
For more information see the [Code of Conduct FAQ](https://www.contributor-covenant.org/faq/) or
contact [conduct@darbotlabs.com](mailto:conduct@darbotlabs.com) with any additional questions or comments.
