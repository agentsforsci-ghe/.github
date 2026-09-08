# Agents for Scientists

AI coding agents are entering scientific work quickly, and most researchers adopt them without guidance on security, personal data, or good practice. This organization hosts the material for a hands-on workshop on using agentic coding tools for collaboration in scientific work.

All material is published as Open Educational Resources and is free for any group to reuse.

**Sign up (for this and the companion workshop):** <https://forms.gle/Zf5fPsPJqUxEoLgKA>

## The workshop

Website: <https://agentsforsci-ghe.github.io/website/>

### Agentic coding for collaboration and scientific work

**Tuesday, 29 September 2026, 08:30 to 17:00**

[Villa Hatt, ETH Zurich](https://ethz.ch/en/campus/access/region-zurich/villa-hatt.html)

A critical, hands-on introduction to agentic coding tools for research: what they do well, where the risks lie, and the do's and don'ts of daily use, including security concerns and personal data.

The day runs the real work of writing a paper under three conditions: as you do it now without agents, with an agent given minimal input, and with an agent given a proper plan and using GitHub issues. Comparing the three shows what the agent actually does for you, how the process can be documented, and where you stay involved in making decisions.

Participants work with their own data, in their own repository in this organization.

By the end of the workshop, participants will be able to:

- Run an agent inside the Git workflow: give a coding agent a task, write its plan down as GitHub issues before any code is produced, then review what it produced as a pull request and accept or reject the change.
- Judge the difference a plan makes: compare the output of an agent given minimal input against one given a reviewed plan, and say what changed and why.
- Judge the difference documentation makes: compare what an agent does with a plain CSV against the same data published as a data package.
- Declare agent use: point to the record the workflow produced and say what it shows about which parts of the work an agent touched.

### Prerequisite

This is the second of two workshops in the series. [Git for Scientists](https://gitforsci-ghe.github.io/website/) ran on 15 July 2026 and is the foundation this day builds on. Participants should be able to clone a repository, run the pull, stage, commit, push cycle, work with branches and pull requests, and open and close issues. No prior experience with AI coding agents is needed.

## Transparent AI assistance

Because the work runs through Git and GitHub, every action an agent takes and every decision a person makes is recorded as it happens. That record is what makes agent use traceable and declarable.

Research integrity bodies are writing disclosure rules for scientific research now, while journal policies remain vague or missing. The workshop closes by drafting a response from what the group did in the room, built on two concrete mechanisms:

- **Two kinds of commits.** Commits distinguish work done by the human from work done by the agent. The agent writes the commit message in both cases, so the full change is captured while the contribution stays attributed.
- **A `prompts` folder.** The repository documents the prompts used for AI-assisted work, with timestamps and a clear link from each prompt to its commit.

## Reuse

All workshop material in this organization is openly licensed. You are welcome to reuse, adapt, and teach from it.

## Funding and support

**Funding and support:** [Swiss Reproducibility Network (SwissRN)](https://www.swissrn.org/contents/community/nodes/) local node at ETH Zurich & [Data Stewardship Network at ETH Zurich](https://library.ethz.ch/en/researching-and-publishing/data-management-and-policies/research-data-management/data-stewardship.html), funded by the [swissuniversities Open Science Programme](https://www.swissuniversities.ch/en/topics/open-science/open-science-programme) & [Global Health Engineering group at ETH Zurich](https://ghe.ethz.ch/)
