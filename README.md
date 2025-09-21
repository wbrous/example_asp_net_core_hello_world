# example_asp_net_core_hello_world

A simple .NET console application that prints "Hello World!".

## Running Locally

```sh
$ dotnet run
Hello World!
```

## GitHub Actions Workflow

This repository includes a workflow that can be manually triggered to build the application:

1. Go to the **Actions** tab in GitHub
2. Select **Build on Workflow Dispatch** workflow
3. Click **Run workflow**
4. Provide the required inputs:
   - **Release Title**: A descriptive title for your release
   - **Release Tag**: A tag identifier (e.g., v1.0.0)
5. Click **Run workflow** to start the build

The workflow will:
- Build the application using .NET 8.0
- Create a published version of the app
- Upload the build artifacts with your release tag in the name
