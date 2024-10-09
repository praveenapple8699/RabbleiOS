# RabbleiOS

-> I was able to clone the telegram iOS Source code and setup the project and open it in xcode and run it successfully in simulator.

-> I was able to Identify the code where Login part of telegram happens(AuthorizationUI) and after the login the control goes to TelegramRootController which is being used in AuthorizedContext class.

-> The project structure itself was too complex and I did not understand the structure or architecture of the app and I was not able to add our custom invite code screen after the telegram login step successfully.

-> I have implemented the Invite Code Screen fully in Swift programmatically without using nibs or storyboards.

-> I have tried to get myself faimiliarized with the telegram ios source code, but the project structure was too complex for me to modify and add additional code, I didnt know where to add the code to push the InviteCodeVC after the telgram login happened. I was not able to understand its architecture/structure of the project.

-> I have created a new project and implemented the UI and the mock API to check the success invite code and a basic client side validation before making the api call.

-> Regarding the Web3Auth SDK integration, I have gone through their website and documentaion, I created an free account and tried to run their sample project, but their own SDK was giving errors, the SDK's are not editable or debuggable and coudn't find a solution for this.

-> I have tried web3auth's own example projects also they also have the same issue, not able to run the project to check the sample output.

-> I am attaching a 2nd project with web3auth sdk added for you reference to see what are the issues that I am facing.
