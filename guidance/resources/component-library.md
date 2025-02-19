---
title: Sample library for Customer Service 
description: Read about the library of sample components in GitHub that can help customers and partners to create and deploy solutions in a fast and easy way.
ms.date: 03/15/2024
ms.topic: conceptual
author: edupont04
ms.author: viange
---

# Sample library for Dynamics 365 Customer Service

***Applies to: Dynamics 365 Customer Service***

This collection of sample code, components (solutions), and documents has been created to help Customer Service projects with various tasks like: customization, configuration, and operation of the platform. The goal of the library is to offer reusable and easy-to-follow resources for Customer Service developers and users.  

Some of the components are hosted in the GitHub repo [https://github.com/microsoft/Dynamics-365-FastTrack-Implementation-Assets/](https://github.com/microsoft/Dynamics-365-FastTrack-Implementation-Assets/tree/master/Customer%20Service/ComponentLibrary). You can contribute to this project by reporting issues, suggesting features, or submitting pull requests.

> [!IMPORTANT]
> Sample codes, components (solutions), and documents created by the community aren't supported by Microsoft. If you have questions or issues with community tools, contact the publisher of them.

## Areas

The following sections outline the content of the collection. Each section includes links to the corresponding articles and samples.

### Unified routing

- Channel-based presence

    A core feature of this scenario is the flexibility of channel presence management for agents. Depending on the volume and urgency of different types of customer inquiries, agents can adjust the flow of incoming channel requests to suit their preferences and availability. For instance, an agent can pause the incoming calls channel if they want to focus on chats or cases, or the other way around. This way, agents can optimize their productivity and customer satisfaction.

    This sample approach is to use a channel-centric solution by setting up a separate Advanced Queue for each relevant channel. This allows for the use of the native Assignment MethodAssignment Ruleset functionality and reduces latency between Agent Channel selection and assignments. Learn more at [Overview of unified routing](/dynamics365/customer-service/overview-unified-routing).  

    Learn more at [Channel-based presence](cs-channel-based-presence.md).

- Set up agent capacity for custom entities

    In Dynamics 365 Customer Service, you can configure capacity-based routing for entities to supplement the case (incident) entity. Learn more at [Set up agent capacity for custom entities](cs-route-release-capacity-in-ur.md), where we provide two approaches one no-code and one low-code to perform the before mentioned actions.

### Omnichannel

- Custom record identification

    To identify a customer in the contact center, you might have to apply custom search criteria, based on the information that the customer provides. This approach will help you quickly and efficiently find the customer's profile and access their records. In OOB, you can search by name, phone number, and email address. However, you might want to search by account number or other relevant data. This article explains how to customize the search criteria.

    Learn more at [Custom Record Identification](cs-omnichannel-custom-record-identification-rule.md).

- Sample context parsing in JavaScript

    Context variables play a crucial role in optimizing customer service workflows and enhancing agent productivity. They provide essential context for effective communication and decision-making.  
    If you're working with web resources, you can access context variables from custom JavaScript code. This allows you to enhance the user experience by dynamically adjusting behavior based on the context.  

    Learn more at [JavaScript Sample Context parsing](cs-omnichannel-sample-context-parsing.md).

- LiveChat Widget customization samples

    This is a collection of Ready-to-use JavaScript code examples for customizing the Omnichannel LiveChat Widget.  

    Learn more at [LiveChat Widget customization samples](cs-omnichannel-live-chat-widget-samples.md).

- AgentScript and macro samples

    Agent scripts are essential tools for minimizing human errors during customer interactions. They provide structured guidance to agents, ensuring consistent and efficient resolution processes. These scripts come in two main forms: text-based guidance and macros. Macros simplify repetitive tasks, allowing agents to handle complex actions with a single click. By incorporating these elements, teams can optimize workflows and improve overall operational efficiency.  

    Learn more at [AgentScript and Macro samples](cs-agent-script-macro-sample.md).

### AI

- AI case deflection

    Emails have unstructured content. Routing rules based on subject/body text aren't effective.

    Human intervention is required for proper categorization. The case would need to be re-assigned to the right owner. The customer might want to implement a custom AI model before engaging Unified Routing.

    This content describes a proposal approach by using ARC rules, and AI Builder.  

    Learn more at [Route or deflect cases using AI Builder](cs-ai-case-deflection.md).

- Summarize Dynamics 365 Knowledge Base articles with ChatGPT

    The current integration of Copilot Studio with Knowledge Base articles only offers article links without providing a summary that can be used in chat conversations.

    By integrating ChatGPT with Copilot Studio, the gap is bridged. This way, knowledge articles are summarized directly within the chat conversation.  

    Learn more at [Summarize Dynamics 365 Knowledge Base with ChatGPT for efficient customer support](ai-summarize-knowledge-base-articles.md).

### Microsoft Copilot Studio

[!INCLUDE[pva-rebrand](../includes/pva-rebrand.md)]

- DTMF aggregation by Bot Framework Skills

    This sample serves to explain how to use Bot Framework Composer skill to add DTMF aggregation to Copilot Studio classic for voice support. For DTMF aggregation on chatbots, Bot Framework Skills are required to develop semi-pro-code solutions with the Bot Framework Composer and the Bot Framework Telephony Package.

    Learn more at [Using Bot Framework Composer skill to add DTMF aggregation to Copilot Studio classic for voice support](copilot-studio-bot-framework-composer-skill.md).

- Multilingual voice bot in Microsoft Copilot Studio

    This sample solution contains a Copilot Studio bot that was implemented based on the guidance at [Set up a multilingual bot in Microsoft Copilot Studio](/dynamics365/customer-service/set-up-multilingual-pva-bot).

    Learn more at [Set up a multilingual bot in Copilot Studio for contact center](copilot-studio-multilanguage-bot.md).

- Play audio file in Copilot Studio voice bot

    This sample shows how to play audio files saved in secure data storage. With Bot Framework Composer and Azure Blob Storage, we can secure a custom audio clip and play it in a custom copilot.  

    Learn more at [Play secure audio file from Copilot Studio](copilot-studio-play-audio-file.md).

## Related resources

- [Dynamics365 Customer Service](/dynamics365/customer-service/)
- [Unified Routing](/dynamics365/customer-service/administer/overview-unified-routing)
- [Omnichannel for Customer Service](/dynamics365/customer-service/implement/introduction-omnichannel)
- [Microsoft Copilot Studio](/microsoft-copilot-studio/)
