# proarchive-template
A template repository meeting the Smarsh Professional Archive Best Practices: https://smarsh.atlassian.net/wiki/spaces/P1/pages/854065209/GitHub+Kanban+Standards

This template repo utilizes our `Professional Archive GitHub Re-Usable Workflows`. Please read about thier workflows and how to name branches properly here:
https://github.com/Smarsh/proarch-github-reusable-workflows

Delete this header when setting up your repository + fill out the sections below.

---

Build status tags or badges go at the top.

[![Git Secrets Scan](https://github.com/Smarsh/proarchive-template/actions/workflows/git-secrets-scan.yml/badge.svg)](https://github.com/Smarsh/proarchive-template/actions/workflows/git-secrets-scan.yml)  
👆 `edit the path in this badge to match your new repo`

# App name
Brief application description

## Requirements
- list language and build tool requirements (Java, .net, docker, etc.)

## Service dependencies
- list services this project depends on (zookeeper, db, Retrieval Service, etc.)

## Applications
Describe each individual application contained in the repo and its entry point or start script. Many repos will contain one application but some contain multiple.

## Artifacts
Describe each artifact produced by the project and where it lives. Example:

### Docker image
The <projectname> docker image lives in Artifactory (provide URL).

## Building the application
Describe how to build the application locally

## Running the application
Describe how to run code locally, including starting any prerequisites or service dependencies. Also include any IDE or debugging setup necessary

## Scripts and other tooling
Projects often have scripts, makefiles, or other tooling to speed local development. Describe them here.

## Additional Resources
Link to other documentation or resources a developer might want. Examples:

- changelog file
- Jira board
- Confluence space or home page for project
