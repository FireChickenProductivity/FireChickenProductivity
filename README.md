I am a computer science student working on projects to make it easier for people with disabilities to operate a computer.

# Summary of Significant Talon Voice Projects
## Summary of Talon: The Tool My Projects Are Built On
[Talon Voice](https://talonvoice.com/) is an extremely customizable voice command and dictation software that also offers support for working with eye tracker and key macros. I frequently work on talon voice customization projects for personal use and to help others. The software is largely used by people with disabilities, but is used by some nondisabled technical workers to boost their productivity or lower their risk for repetitive strain injury. Talon is a popular choice for voice programming. (In case it was not obvious, no, I did not develop Talon Voice. I just write customization for it)

## My Contributions to Others' Projects
I made a minor contribution to [sight-free-talon](https://github.com/C-Loftus/sight-free-talon). According to the project readme, it makes it easier to "Use Talon while not needing to look at your computer. Especially helpful for those with vision impairment, blindness, eye strain, or those who prefer alternative computer interaction."

I regularly contribute to [the talon voice community repository](https://github.com/talonhub/community).

## Mouse Control
[Mouse Control Chicken](https://github.com/FireChickenProductivity/MouseControlChicken): Offers several mouse grid systems. This works better for me than other systems for controlling the computer mouse through voice and offers considerable customization options. This system was also an experiment at using what I learned studying object oriented design to make a system that would be easier to extend and maintain.

[Viper](https://github.com/FireChickenProductivity/Viper): Originally started as a project to control the computer mouse through hissing. It can now be used to trigger custom sets of actions through hissing. I find this useful for saving vocal endurance.

## Basic Action Records
[Basic Action Recorder](https://github.com/FireChickenProductivity/BAR): Allows recording basic actions (things like mouse clicking, key presses, and typing text). This has applications to proctoring including making it easier for proctors to follow what a student using voice commands is doing. It can also be used to support other projects by making it possible to register functions to get called when a basic action is performed with an object containing the name of the basic action and a list of arguments it received. The project can generate a history of commands including the command names and basic actions performed. 

[Basic Action Record Analysis](https://github.com/FireChickenProductivity/BasicActionRecordAnalyzer): I made a prototype but currently not very documented program for generating the body of the source code for new voice commands based on one of those histories (The body defines the actions a voice command will perform. Every other aspect defines when a command is available and what you say to use it). The goal is to generate commands that can improve productivity by condensing frequent command sequences into individual commands as well as to identify voice commands frequently used where the user says a lot to do little. I find it surprisingly useful, but it generates excessive recommendations and quite a few useless recommendations.

[Artificial History Generator](https://github.com/FireChickenProductivity/ArtificialTalonCommandHistoryGenerator): I made a program for generating an artificial talon voice command history that could have been used to generate an input text file (with some limitations). This can be combined with the basic action record analysis program to generate voice commands that may be useful for generating certain kinds of text.

## Miscellaneous
[Correction Chicken](https://github.com/FireChickenProductivity/CorrectionChicken): Simple dictation error correction system.

[Clipboard Manager](https://github.com/FireChickenProductivity/Talon-Voice-multidimensional-clipboard): Simple, but one of the most useful things I made.

[Terminal Chicken](https://github.com/FireChickenProductivity/TerminalChicken): Allows writing terminal commands in VSCode and having them sent to the terminal. This allows using tools like cursorless for editing terminal commands.

[Google Sheets Commands](https://github.com/FireChickenProductivity/GoogleSheetsTalonCommands): This was created in a hurry to make it practical for me to do a few assignments, but some people find it useful.

[Key Rebinding](https://github.com/FireChickenProductivity/TalonKeyRebindings): This makes it easier to do some talon key rebinding work and was developed to help support the use case of a specific talon user.

## Personal Setup
[Dictation Setup](https://github.com/FireChickenProductivity/TalonVoiceDictationSetup): This is my personal setup for dictating prose. It is intended to be used with the community talon repository.

[Programming](https://github.com/FireChickenProductivity/PersonalTalonVoiceCodingSetup): This is my personal setup for programming. It is also intended to be used with the community talon repository. This is really not intended to be useful for anyone other than myself, but you might want to borrow some of my custom commands for doing talon voice customization if you have to do a lot of that yourself.

[Community Fork](https://github.com/FireChickenProductivity/knausj_talon/tree/personal-setup): This is my personal fork of the community talon repository. 

## Projects That Let Me Not Need Extended Time Exam Accommodation
[Math Commands](https://github.com/FireChickenProductivity/Talon-Voice-EquatIO-Commands): I personally find my math command setup better for speed than any of the alternatives. Your mileage may vary. They work with EquatIO, which is a math software used already by some academic institutions to accommodate various disabilities.

[Diagram Drawing Commands](https://github.com/FireChickenProductivity/TalonVoiceDiagramDrawing): They are currently primarily intended for personal use, but I am gradually making it easier for others to work with. I find that useful mostly for simple computer science diagrams and helping me solve some math problems.

[Desmos Calculator Commands](https://github.com/FireChickenProductivity/TalonVoiceDesmosCommands): These commands are for working with desmos online calculators. Many colleges and universities allow students with certain disabilities to use desmos calculators during exams.

[Exam Mode](https://github.com/FireChickenProductivity/Talon-Voice-Exam-Mode): This blocks many of the talon community repository commands and actions when a specific talon voice tag is active. This let me work with many of of the community commands about having to worry about triggering voice commands that would not be allowed on exams.
