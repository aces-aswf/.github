<!-- SPDX-License-Identifier: Apache-2.0 -->
<!-- Copyright Contributors to the ACES Project. -->

# Contributing to ACES

ACES relies on active community participation in order to succeed. We welcome contributions from developers, manufacturers, and end users alike. 

You can contribute to the ACES ecosystem in several ways:
* **Feedback & Issues:** Log bugs or submit feature requests in our issue trackers.
* **Community:** Join discussions on our Slack and forum to help support other users. You can also attend TSC meetings, which are open to all.
* **Technical Artifacts:** Contribute mathematical color transforms, utilities, or code.
* **Documentation:** Create, edit, or clarify user-facing guides and documentation.


## Legal Requirements

ACES is a project hosted by the Academy Software Foundation (ASWF) and follows the open source software best practice policies of the ASWF TAC with guidance from the Linux Foundation.

### License

ACES is licensed under the [Apache 2.0](./LICENSE) license. New contributions should abide by that license. 

### Policy on AI Tools

The thoughtful use of AI coding assistants is permitted on this project, provided that contributions remain transparent and human-driven. To help us maintain quality and trust, please keep the following guidelines in mind when using these tools:

- _Disclosure_: Clearly state if AI tools were used to generate or refine your code contribution. Also identify which models were used. At a minimum, you could include an `Assisted-by: TOOL/MODEL` line (e.g. `Assisted-by: Claude-3.5-Sonnet`) in both your commit messages and PR description.
- _Human Ownership & Accountability:_ Just as with any non-AI-assisted commit, you (the human contributor) are responsible for the code you submit. You must be able to understand, explain, defend, and modify your changes during code review.
- _Human Interaction:_ Interactions with maintainers and the community should come from you (the human contributor). Do not delegate communications about your work (e.g. PR review conversations or issue discussions) to automated agents.

> [!NOTE]
> _This policy is a work in progress and may be updated as AI capabilities and community norms develop._

### Contributor License Agreements

To maintain the legal integrity of the project's codebase, we require all contributors to complete a **Contributor License Agreement (CLA)**.

ACES uses [EasyCLA](https://lfx.linuxfoundation.org/tools/easycla) for managing CLAs, which automatically checks to ensure CLAs are signed by a contributor before a commit can be merged.

* If you are an individual writing the code on your own time and you're SURE you are the sole owner of any intellectual property you contribute, you can [sign the CLA as an individual contributor](https://docs.linuxfoundation.org/lfx/easycla/contributors/individual-contributor).

* If you are writing the code as part of your job, or if there is any possibility that your employers might think they own any intellectual property you create, then you should use the [Corporate Contributor Licence Agreement](https://docs.linuxfoundation.org/lfx/easycla/contributors/corporate-contributor).

The ACES CLA's are the standard forms used by Linux Foundation projects and [recommended by the ASWF TAC](https://github.com/AcademySoftwareFoundation/tac/blob/main/process/contributing.md#contributor-license-agreement-cla).

### Commit Sign-Off

Every commit must be signed off. That is, every commit log message must include a “`Signed-off-by`” line (generated, for example, with “`git commit --signoff`” or "`git commit -s`"), indicating that the committer wrote the code and has the right to release it under the [license](LICENSE).

Here is an example Signed-off-by line, which indicates that the submitter accepts the DCO:

`Signed-off-by: John Doe <john.doe@example.com>`

If John Doe has signed an individual CLA, or his corporation's CLA Manager has included his GitHub account in a corporate CLA approved list, his pull request can be merged. Otherwise the EasyCLA system will provide instructions on signing a CLA, or request inclusion in an existing corporate CLA approved list.

See the [ASWF TAC CONTRIBUTING.md](https://github.com/AcademySoftwareFoundation/tac/blob/main/process/contributing.md#contribution-sign-off) file for more information on this requirement.

### Copyright Notices

All new source files should begin with a copyright and license stating:

    // SPDX-License-Identifier: Apache-2.0
    // Copyright Contributors to the ACES Project.