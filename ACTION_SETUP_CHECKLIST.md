# Action Setup Checklist

Complete the list of tasks to update this `GitHub Action Template` with the requirements for your new GitHub Action.

- [x] Checkout repository
- [ ] Update [.gitignore](.gitignore)
- [ ] Update [action.yml](action.yml)
  - [ ] Update `name`, `description` and `author` fields
  - [ ] Update `branding` fields 
    - see [GitHub Actions Branding Cheat Sheet](https://haya14busa.github.io/github-action-brandings/)
  - [ ] Create `inputs` and `outputs` fields if applicable to the project
  - [ ] Update `runs` section with action functionality
- [ ] Update [README.md](README.md) file
  - [ ] Update action title and description
  - [ ] Update `Usage` section
  - [ ] Update or delete `Inputs` and `Outputs` section
  - [ ] Update or delete `License` section, or leave as is
  - [ ] Update or delete `Contributions` section, or leave as is
- [ ] Update or delete [CONTRIBUTING.md](CONTRIBUTING.md) file
  - [ ] Update or delete existing sections
  - [ ] Add additional sections if needed
- [ ] Update or delete [LICENSE](LICENSE) file, or leave as is
  - [ ] Update to a different license or delete the file if preferred. Defaults to `MIT`.
  - [ ] Add name or organization name to the copyright, ex. `Copyright (c) 2023 MyCompany`.
- [ ] Update or delete [pull-request.yml](.github/workflows/pull-request.yml)
- [ ] Update or delete [dependabot.yml](.github/dependabot.yml), or leave as is
- [ ] Update or delete [publish.yml](.github/workflows/publish.yml), or leave as is
  - Set `publish_latest_tag` to `false` to exclude a `latest` tag when publishing
  - See [Actions Tagger](https://github.com/marketplace/actions/actions-tagger)
- [ ] Delete this checklist file `ACTION_SETUP_CHECKLIST.md` once everything is complete