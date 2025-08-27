# earthscience-copilot-instructions
A set of curated earth science copilot instructions 

## How to Install Earth Science Copilot Instructions for Automatic Use in Your Repository

GitHub Copilot now supports repository-level custom instructions! By adding a special configuration file, you can ensure that everyone using Copilot in your repository benefits from curated prompts and guidance.

### Steps

1. **Copy or Adapt the Instructions**

   - Review the instruction content you want to provide for Copilot users.
   - The main content should be added to a `.github/`

```bash
cp copilot-instructions.md /PATH/TO/WORKING/REPOSITORY/.github/
cp -r instructions /PATH/TO/WORKING/REPOSITORY/.github/
```
**References:**

- [GitHub Docs: Add repository instructions for Copilot](https://docs.github.com/en/copilot/how-tos/configure-custom-instructions/add-repository-instructions?tool=vscode)
- [copilot.yml reference](https://docs.github.com/en/copilot/how-tos/configure-custom-instructions/copilot-custom-instructions-reference)
