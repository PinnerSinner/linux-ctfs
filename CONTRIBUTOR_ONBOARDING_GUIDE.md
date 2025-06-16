# Developer Onboarding Guide for Linux CTF Project

This guide provides a comprehensive list of questions that developers can use with AI assistants (Claude Code, GitHub Copilot Chat, etc.) to quickly familiarize themselves with this Linux Command Line CTF challenge project.

## Project Overview & Architecture

- **What is the main purpose of this Linux CTF project and who is the target audience?**
- **How is the project structured? What are the main directories and their purposes?**
- **What cloud providers are supported for deploying this CTF environment?**
- **What is the relationship between the main README.md and the provider-specific READMEs in aws/ and azure/ directories?**

## Technical Stack & Dependencies

- **What technologies and tools are used in this project (e.g., Terraform, cloud services)?**
- **What are the system requirements for running this CTF environment?**
- **Are there any specific Linux distributions or versions required?**
- **What network ports and services are utilized by the CTF challenges?**

## Setup & Deployment

- **Walk me through the setup process for deploying this CTF on AWS**
- **What are the differences between the AWS and Azure deployment processes?**
- **What does the ctf_setup.sh script do? Can you explain its main functions?**
- **What Terraform resources are created by main.tf in each cloud provider?**
- **How is user authentication handled for the CTF VM?**

## Challenge Structure

- **How many challenges are there in total and what skills do they test?**
- **What is the flag format used throughout the challenges?**
- **How does the verify command work for flag submission?**
- **Which challenges depend on running services and can't survive a VM reboot?**
- **What is the expected completion time for all challenges?**

## Code Analysis

- **Show me the structure of the ctf_setup.sh script and explain the key sections**
- **How are the CTF challenges deployed and configured on the target VM?**
- **What security measures are implemented to prevent cheating or unauthorized access?**
- **How are the flags generated and hidden throughout the system?**

## Development & Contribution

- **What are the contribution guidelines for this project?**
- **How should new challenges be added to the system?**
- **What testing procedures should be followed before submitting changes?**
- **Are there any coding standards or conventions specific to this project?**

## Troubleshooting & Maintenance

- **What are common issues users might face during setup and how to resolve them?**
- **How can I debug issues with the Terraform deployment?**
- **What logs should I check if challenges aren't working properly?**
- **How do I clean up resources after completing the CTF?**

## Integration & Extension

31. **How could this CTF be integrated into a learning management system?**
32. **What would be required to add support for a new cloud provider (e.g., GCP)?**
33. **How could the verification system be enhanced to provide hints or partial credit?**
34. **Could this project be containerized using Docker? What would be the benefits?**

## Security & Best Practices

- **What security considerations were taken into account when designing these challenges?**
- **How does the project ensure that CTF participants can't access other users' data?**
- **What are the cost implications of running this CTF environment?**
- **Are there any rate limiting or resource constraints implemented?**

## Learning Path

- **What prerequisite knowledge should users have before attempting these challenges?**
- **How do these challenges align with the Phase 1 Guide mentioned in the README?**
- **What resources would you recommend for users who get stuck on specific challenges?**
- **How could an instructor use this CTF in a classroom setting?**

## Tips for Using This Guide

- Start with questions 1-4 to get a high-level understanding
- Use questions 9-13 when you need to deploy the environment
- Reference questions 14-18 to understand the challenge mechanics
- Dive into questions 19-22 for code-level understanding
- Consult questions 27-30 when troubleshooting issues

Remember: The goal is to understand the project well enough to contribute effectively or adapt it for your own use cases. Don't hesitate to explore the code and documentation beyond these questions!
