# KBase SDK Actions
GitHub Actions CI workflows for apps built with the [KBase SDK](https://kbase.github.io/kb_sdk_docs/index.html) 

## Usage

1. Ensure you have a [KBase developer token](https://kbase.github.io/kb_sdk_docs/tutorial/3_initialize.html#set-up-your-developer-credentials) saved as `KBASE_TEST_TOKEN` in your repo or org's [GitHub Secrets](https://help.github.com/en/actions/configuring-and-managing-workflows/creating-and-storing-encrypted-secrets) settings.
1. Copy the [action.yaml](./action.yaml) file to your project's `.github/workflows/` directory. Create this directory if needed.
1. You're done! Any future commits and pull requests to your repo's `master` branch will trigger the SDK tests to run.

To review your projet's SDK test status and results, see your repo's Actions tab.

