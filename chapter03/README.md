Chapter 3 of "Learning GitHub Actions: Automation and Integration of CI/CD with GitHub" dives into the details of what constitutes an individual action within the GitHub Actions platform. Here's a summary of the key points covered in this chapter:

1. Distinction Between Actions and Workflows:
    - Actions are akin to plug-ins or modules used by workflows, which are more like scripts or pipelines that utilize these modules.
    - Actions are executed when steps in a workflow call them.

2. Structure of an Action:
    - Actions can range from simple shell scripts to complex implementations involving extensive code, test cases, and CI/CD workflows.
    - Each action is defined by a set of code and a metadata file named `action.yml` or `action.yaml`, which specifies its inputs, outputs, and execution environment.

3. Interfacing with Actions:
    - Steps within workflows call actions, which can be predefined GitHub Actions or custom implementations.
    - Actions are often defined by their version in workflows, e.g., `uses: actions/foo@v3`.

4. Using Actions:
    - Actions can be used directly within workflows by specifying the action and its version.
    - Best practices include using version tags to ensure stability and predictability.

5. Public Actions and the Actions Marketplace:
    - The Actions Marketplace is a repository where creators can publish their actions for public use.
    - Users can search for existing actions in the Marketplace to find functionality that meets their needs.
    - GitHub provides a set of default actions that can be found in the `github.com/actions` repository.

6. Conclusion:
    - The code for an action resides in a standard GitHub repository.
    - The GitHub Actions Marketplace facilitates sharing and discovering public actions, simplifying the process of integrating external functionality into workflows.