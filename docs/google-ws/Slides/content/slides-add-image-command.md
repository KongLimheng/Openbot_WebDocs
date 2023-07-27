<!--TITLE: Slides Add Image Command -->
<!-- SUBTITLE: a command in the Google Workspace Commands\Slides\Content group. -->
# Slides Add Image Command


## What does this command do?
This command adds an Image to a slide.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Slides Instance Name|Enter the unique instance that was specified in the **Create Session** command.|MySlidesInstance|Failure to enter the correct instance or failure to first call the **Create Session** command will cause an error.|
|Slide Options|Indicate the input option for target slide.|||
|Slide Id|Enter the Id of the slide where the image will be added.|_A1 \|\| vSlideId||
|Slide Location|Indicate the position of the slide where the image will be added.|||
|Slide Index|Enter the index of the slide where the image will be added.|2 \|\| vSlideIndex||
|Translate X|Enter the X coordinate translation element.|30.0 \|\| vTranslateX||
|Translate Y|Enter the Y coordinate translation element.|30.0 \|\| vTranslateY||
|Image Url|Enter the Image Url you want to set.|"https://openbots.ai/media/File:Image_created_with_a_mobile_phone.png" \|\| vImageUrl||
|Output ObjectId Variable (Optional)|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: SlidesAddImageCommand
Parent Namespace: OpenBots.Commands.GoogleWorkspace.Slides.Content
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
