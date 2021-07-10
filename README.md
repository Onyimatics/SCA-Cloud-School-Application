# SCA-Cloud-School-Application
This is She Code Africa Cloud School Technical Assessment.

## Jenkins pipeline syntax

### Source(Git)

This instructs Jenkins to obtain your Pipeline from a Source Control Management, in this case <code>Git</code>.

 - Define the source of your project.
 - Specify the URL or path of the git repository. This uses the same syntax as your git clone command.
 - Specify the branch if you'd like to track a specific branch in a repository. If left blank, all branches will be examined for changes and built.
 - Define the Credential Id used to check out sources.
 
### Build Step

At this stage, the code builds and compiles. You can add a shell script that contains the script needed for the build.


### Deploy

This stage will only execute if the previous stages executed successfully. You can also add a shell script that contains the script to execute the deployment.
