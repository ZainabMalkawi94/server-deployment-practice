# server-deployment-practice


## Node.js 
Node js is an open-source, server-side JavaScript runtime environment.

## Action in github 
In the context of a GitHub repository, an "action" refers to a specific task or workflow that can be automated within the repository. GitHub Actions allows developers to create custom workflows, which are sequences of actions, to automate various processes such as building, testing, deploying, and releasing software. Actions can be triggered by events, such as a commit or pull request, and can perform a wide range of tasks to streamline the development and deployment workflow.

## CI/CD 
CICD, short for Continuous Integration and Continuous Deployment, is a software engineering practice that involves automating the process of integrating code changes, running tests, and deploying applications to production. It aims to ensure that software is built, tested, and deployed consistently and efficiently, enabling faster development cycles and reducing the risk of introducing bugs or issues into the production environment. CICD pipelines typically involve source code management, automated testing, and automated deployment steps.

## Middleware
 In server-side development, middleware is often implemented as a function that sits between the incoming request and the outgoing response. It intercepts the request, performs specific tasks or modifications, and then passes the request to the next middleware or sends the response back to the client. Middleware functions can perform operations such as logging, authentication, data validation, error handling, and more, allowing for modular and customizable processing of requests and responses in server applications.

 ----------------------------------------------------------------------------
## How to create action in github: 

To create a GitHub Action, you can follow these steps:

1. Navigate to your GitHub repository in which you want to create the Action.
2. Go to the "Actions" tab at the top of the repository.
3. Click on the "New workflow" button, or if it's your first time, you might see a template to choose from (Node.js).
4. You'll be directed to the workflow file editor, where you can define the workflow using YAML syntax.
5. Provide a name for your workflow file, such as main.yml.
6. Define the event that triggers the workflow. This could be a push to the repository, a pull request, or a scheduled event, among others.
7. Specify the jobs and steps that make up your workflow. Jobs represent the work that needs to be done, and steps define the individual tasks within each job.
8. Configure the desired actions to be performed within each step. You can use pre-built actions from the GitHub Marketplace or create your own custom actions.
9. Customize and configure each action with relevant inputs, outputs, and settings as needed.
10. Save the workflow file.
11. GitHub will automatically validate the syntax of your workflow file and enable the workflow.
12. The workflow will now run based on the triggers you defined, and you can view the execution logs and status in the "Actions" tab.
By following these steps, you can create a GitHub Action and automate various tasks within your repository.

-----------------------------------------------------------------------