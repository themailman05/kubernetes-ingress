# How To Contribute
## Introduction
The NGINX Ingress Controller makes use of the [Hugo](https://gohugo.io/) static site generator.

Documentation is stored within the `docs/`subfolder of the main repository, and is where `hugo` commands should be run.

We use a feature branch workflow: changes should be made from a branch originating from `main`.

Commits should be squashed, and pull requests (PRs) should then target the `main` branch.

Once a PR has been accepted, its changes should be cherry picked onto the release branch.

## Set-up
**Requirements**
* [git](https://git-scm.com/downloads)
* [hugo](https://gohugo.io/installation/)

**Quick Start**
```
git clone git@github.com:nginxinc/kubernetes-ingress.git
cd docs/
hugo server -e production -b "http://127.0.0.1"
```
## Style Guide
NGINX (and F5) has its own style guide, but broadly speaking, you can stick to the [Microsoft Style Guide](https://learn.microsoft.com/en-us/style-guide/welcome/).

We prefer the active voice, and plain language. When possible, be concise and avoid jargon - don't assume the reader knows as much as you.

If an acronym or abbreviation could cause confusion to someone, explicitly define it during its first use, e.g *Security Operations Centor (SOC)*.

