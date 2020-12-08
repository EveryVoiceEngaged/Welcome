# Welcome!

Thank you for visiting Every Voice Engaged.  We are in the process of getting our project more accessable for public visability and contributions.  

Check out [CGA_tech_stack-containerized.pdf](https://github.com/EveryVoiceEngaged/Welcome/blob/master/CGA_tech_stack-containerized.pdf) for a pictorial view of our tech stack.

At this time our code repository remains private.  If you're interested in helping out, reach out to gary@everyvoiceengaged.org and let's start a conversation.  Once you're on board, we'll add you to our private repo and together we will have an opportunity to improve civic engagement.

## Development Environment Requirements - Option A - local build and test
You will need to install each of these items to build and run the software locally on your own system.  Links to download instructions are included.

0. If you are on a Mac, consider installing [homebrew](https://brew.sh/)
1. Install OpenJDK Version 8, aka 1.8 [Instructions for Mac](https://stackoverflow.com/questions/24342886/how-to-install-java-8-on-mac) 
2. Install Maven [Instructions for Mac](https://stackoverflow.com/questions/54601898/how-to-install-and-configure-maven-on-macos)
3. Use [IntelliJ IDE](https://www.jetbrains.com/idea/download/) for a better developing experience, [Eclipse](https://www.eclipse.org/downloads/) works too!
4. Install [PostgreSQL](https://www.postgresql.org/download/) 9.6
5. Create a database named "cga_dev" (`createdb cga_dev`)
6. If you're planning to make style sheet changes, you'll need to install the [Compass.app](https://github.com/KKBOX/compassapp/releases) to complile the SCSS code.

## Development Environment Requirements - Option B - devops build, test, deploy
If you're working on a branch linked to our development or staging pipeline, commits and pull requests trigger builds, tests, and deployment to the linked container.  Note that CSS changes will still require local compliation of the SCSS code.
