## .NET Core CI/CD on the AWS Cloud—Quick Start

For architectural details, step-by-step instructions, and customization options, see the [deployment guide](https://fwd.aws/yewap).

To post feedback, submit feature ideas, or report bugs, use the **Issues** section of this GitHub repo. 

To submit code for this Quick Start, see the [AWS Quick Start Contributor's Kit](https://aws-quickstart.github.io/).

## Updates after fork
- Update dotnet runtime to 5.0

### Note: 
Using the following environment for CodeBuild does work to build .NET 5 applications:

Managed image
Operating system: Ubuntu
Runtime: Standard
Image: aws/codebuild/standard:5.0
Imager version: Always use the latest image for this runtime version
Environment type: Linux