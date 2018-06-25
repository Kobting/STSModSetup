# MTSSetup
A base structure for the creation of mods for Slay the Spire based off of the wiki from <a href="https://github.com/daviscook477/BaseMod/wiki/Getting-Started-(For-Modders)">BaseMod</a>

This would be the base directory where all your mods would go.
To make a new mod just copy the structure of the ExampleMod and put it in the same area that
ExampleMod is at. Right next to the libs folder.

### Steps
1. Download this repository as a zip. Do not clone or fork.
2. Follow the instructions at lib/help.txt
3. If using **Eclipse** *File -> Import -> Maven -> Existing Maven Projects -> Browse and select ExampleMod folder or your own mod that follows the structure of the ExampleMod*. You may need to right-click your project *Maven -> Update Project -> Select your current project -> Click OK*.
4. If using **IntelliJ** *File -> Project from Existing Sources -> Select ExampleMod folder or your own mod that follows the structure of the ExampleMod Select Maven -> Press next until your project is built*. Click on the Maven Projects tab on the right of the editor and click the refresh icon to load your dependencies from the pom.xml into your project. (If no Maven projects tab on the right *View -> Tool Windows -> Maven Projects*)
5. You should now be ready to start modding. After you've written your mod you can build it by typing "mvn package" in the Terminal in IntelliJ or If using Eclipse open a command prompt and navigate to the location of the pom.xml.
---
### Helpful Resources
https://github.com/daviscook477/BaseMod/wiki

https://github.com/kiooeht/ModTheSpire/wiki
