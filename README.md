# Github-Actions vs Jenkins

Advantages of GitHub Actions over Jenkins

Hosting: Jenkins is self-hosted, meaning it requires its own server to run, while GitHub Actions is hosted by GitHub and runs directly in your GitHub repository.

User interface: Jenkins has a complex and sophisticated user interface, while GitHub Actions has a more streamlined and user-friendly interface that is better suited for simple to moderate automation tasks.

Cost: Jenkins can be expensive to run and maintain, especially for organizations with large and complex automation needs. GitHub Actions, on the other hand, is free for open-source projects and has a tiered pricing model for private repositories, making it more accessible to smaller organizations and individual developers.

Advantages of Jenkins over GitHub Actions

Integration: Jenkins can integrate with a wide range of tools and services, but GitHub Actions is tightly integrated with the GitHub platform, making it easier to automate tasks related to your GitHub workflow.
In conclusion, Jenkins is better suited for complex and large-scale automation tasks, while GitHub Actions is a more cost-effective and user-friendly solution for simple to moderate automation needs.ns

# Github-action self-hosted runner

Need of using self-hosted runner
1. It is mainly used when we are using private projects, code is not open to everyone.
2. when we need huge computation
3. Security approach (eg: banking application)

How to set-up self-hosted runner?
1. launch instance
2. configure inbound and outbound traffic rules (http and https)
3. Github->settings->action->runner->add a new runner->choose runner image->choose architecture->then it display certain steps that need to be run in the terminal
4. update action file , runs-on:self-hosted
