# Adobe Commerce Support Knowledge Base
This repository contains the markdown source of articles, published in [Support Knowledge Base for Adobe Commerce](https://support.magento.com/hc/en-us).

## Goals

Our goal is to provide the Adobe Commerce Community with comprehensive and quality documentation on resolving Magento issues, Magento best practices, and sharing answers to questions our Support team typically gets. We believe that to accomplish this goal, we need experts from the community to share their knowledge with us and each other. We are thankful to all of our contributors for improving Support Knowledge Base documentation.

## Contributing

We welcome all kinds of contributions, from minor typo corrections to complete troubleshooting articles. Your contributions are highlighted in the Adobe Commerce Bitergia leaderboards. See [contribution points](docs/contribution-points.md) for details.

### General Contribution Flow

- Fork this Repository.
- Make edits on the forked Repository.
- Submit a Pull Request (PR) to this Repository.
- Tests are run:
    - Adobe CLA - making sure the Adobe Open Source Contributor License Agreement is signed.
    - Markdown Linting test - making sure markdown syntax is correct.
    - File structure validation test - making sure the commit is done according to the [required file structure](.github/CONTRIBUTING,md#file_structure).
    - Metadata validation test - making sure all the necessary metadata are included in the right format. See [Metadata validation guide](https://github.com/magento-commerce/knowledge-base/blob/main/docs/guides/metadata-validation-guide.md) on how to fix common validation errors.     
- Pull Request (PR) approvals flow:
    - Knowledge Base (KB) writers reviews the PR within several days' time frame and adds label.
    - KB writer can approve/deny/request changes.
    - If approved, KB writer adds labels corresponding to the level of input provided in PR and internal subject matter expert (SME) reviews the PR.
    - SME can approve/deny/request changes.
- Once all corrections are done (if any requested) and both the KB writer and SME approve the PR, The KB writer imports content to the internal repo and merges it internally.
- The **magento/knowledge-base** repository synchronizes with the internal one in 20 minutes.
- Once the repositories are synced, your PR gets closed and you get reward points.
- **For more details on contribution flow, Please refer to the [Contributor's Guide](.github/CONTRIBUTING.md) of Knowledge Base.**
- **For templates, style guide, labels and formatting guidelines, Please refer to this [Documentation](docs/index.md).**

## Licensing

This project is licensed under the OSL 3.0 License. See [LICENSE](LICENSE.txt) for more information.
