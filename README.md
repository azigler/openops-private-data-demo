# OpenOps Private Data Demo

> Build AI bots on your private data with an open source stack powered by Mattermost ⚡️

![header image by recraft.io](https://github.com/azigler/azigler/assets/7295363/5066cbb9-5576-4c50-942d-a3b1db1abb6f)

[![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)

## Table of Contents
- [OpenOps Private Data Demo](#openops-private-data-demo)
  - [Table of Contents](#table-of-contents)
  - [Background](#background)
  - [Install](#install)
  - [Usage](#usage)
  - [Related Efforts](#related-efforts)
  - [Maintainers](#maintainers)
  - [Contributing](#contributing)
  - [License](#license)

## Background

**"How to Build a Custom Collaboration Stack with Open Source Software"**

*Technical workshop demo created by [Andrew Zigler](https://www.linkedin.com/in/andrewzigler/), Developer Advocate @ [Mattermost](https://mattermost.com/)* 🍎

> In today's rapidly evolving AI landscape, organizations are increasingly seeking innovative ways to leverage their internal data to improve productivity and reduce errors. In this workshop, we’ll delve into the realm of building internal AI bots using an entirely open source stack. We'll set up a local Mattermost instance with a local Large Language Model (LLM) and train it on communication happening in those channels, allowing your team to harness the power of AI within your organization's private communication channels. You’ll discover best practices for creating bots that seamlessly cater to the needs of multiple users to foster collaboration. We'll also shed light on critical safety and security concerns to ensure the responsible and secure use of AI with internal data. As the process of building an internal AI bot with open source tools and training it on data within a channel is demonstrated, you'll gain invaluable insights that will empower you to become a catalyst for AI-driven innovation within your own organization.

To learn about the technology behind this demo, visit the [Mattermost OpenOps repository](https://openops.mattermost.com).

## Install

***Rather watch a video?** 📽️ Check out our YouTube tutorial video for getting started with OpenOps: https://www.youtube.com/watch?v=20KSKBzZmik*

***Rather read a blog post?** 📝 Check out our Mattermost blog post for getting started with OpenOps: https://mattermost.com/blog/open-source-ai-framework/*

1. Clone the OpenOps repository (**not this project**): `git clone https://github.com/mattermost/openops && cd openops`
2. Start docker services and configure plugin
    - **If using OpenAI:**
      - Run `env backend=openai ./init.sh`
      - Run `./configure_openai.sh sk-<your openai key>` to add your API credentials *or* use the Mattermost system console to configure the plugin
3. Access Mattermost and log in with the credentials provided in the terminal.

When you log in, you will start out in a direct message with your AI Assistant bot.

## Usage

To learn more about this project, you can view the [accompanying slides](https://docs.google.com/presentation/d/171BlzkccVSvXcxHG_NwvdYtPUB0YOQwleFJj2lySFu0/edit?usp=sharing) on Google Slides. There are AI use cases with screenshots and example, and the The "Proof of concept: OpenOps" section has screenshots of setting up the OpenOps environment, step by step.

## Related Efforts

- [OpenOps repository](https://forum.mattermost.com/c/openops-ai/40) 
- [OpenOps forum](https://forum.mattermost.com/c/openops-ai/40) 
- [OpenOps "AI Exchange" channel on the Mattermost Community server](https://community.mattermost.com/core/channels/ai-exchange) (for Mattermost community interested in AI)
- [OpenOps Discord Server](https://discord.gg/kAC8WakMAx) (for AI community interested in Mattermost) 
- [Mattermost Troubleshooting Discussion on Mattermost Forum](https://forum.mattermost.com/c/trouble-shoot/16)
- [Mattermost "Peer-to-peer Help" channel on Mattermost Community server](https://community.mattermost.com/core/channels/peer-to-peer-help)

## Maintainers

[@azigler](https://github.com/azigler/)

## Contributing

Thank you for your interest in contributing to our open source project! ❤️ To get started, please read the [contributor guidelines](./CONTRIBUTING.md) for this repository.

## License

This repository is licensed under [Apache-2](./LICENSE).
