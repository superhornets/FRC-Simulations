Feel free to make improvements to the simulations or submit new simulations of other FRC mechanisms by creating issues or pull requests on the [GitHub page](https://github.com/superhornets/FRC-Simulations).

If you would like to share your solution to a challenge, please post it on the [ChiefDelphi thread](https://github.com/superhornets/FRC-Simulations). Thanks!

### Pull Request Guidelines

You may submit pull requests even if they don't meet these guidelines however they may not be merged into the master branch until they do.
These guidelines are meant to help teach good practices, not to discourage anyone from contributing. If you have questions, please ask. If you're not sure how to use GitHub yet, the [ChiefDelphi thread](https://www.chiefdelphi.com/t/labview-simulated-control-panel-challenge-more-challenges-welcome/386232) is a good place to ask.

1. All LabVIEW code should have the "Separate compiled code from source file" option turned on. For more information please read the "Recommended LabVIEW Setting Change" section at https://bitbucket.org/JonathanLindsey/lv-merge-and-diff-wrapper/src/master/README.md.
1. Generally, as much code as possible should be kept in the Sensors and Actuators VIs. This hides the complexity of the simulation from everyone simply trying to solve the challenge.
1. All Simulation Support code should go into a "Simulation Support" folder. Folders inside the Simulation Support folder are perfectly fine. Again, this hides the complexity of the simulation from everyone simply trying to solve the challenge.
1. Any Build Specifications should build to a `Builds` folder. The .gitignore file tells git to not track anything in any Builds folder.
1. All challenges should be functional without any kind of joystick or gamepad.


### Thank You!
