# CalendarProject

                          List of changes to program:
- Added command parsing in CalendarController
The controller needed to support the multi-calendar and copy features that was implementated in the model layer.
  
- Added three execution modes in CalendarApp
Modified in order to support GUI mode, interactive mode, and headless mode, setting GUI mode as the default while maintaining backwards compatibility.

- Added extra credit features (multiple calendar support, event editing)
These features support easier usability of the the application, and give extra credit.

- Maintained dependency inversion
Our GUI depends on controller abstraction and not concret concrete implementations, allowing for easier testing. Although we didn't need to do that for this assigment.

                          How to run program (jar file):
(Creating jar file)
1) File, project structure, project settings, artifiacts
2) Add a jar from modules
3) Choose desired settings and press "Build to make"
4) Press OK

(Using jar file)
GUI MODE:
1) java -jar calendar-app.jar
2) OR double-clicking JAR file

INTERACTIVE TEXT MODE:
1) java -jar calendar-app.jar --mode interactive

HEADLESS SCRIPT MODE:
1) java -jar calendar-app.jar --mode headless commands.txt

                          Which features work/do not:
                          
Work: All that were outlined in part 3 and previous parts work, including the extra credit features. These features together include: all the features of the basic calendar, all the features of the multi-calendar and timezones, the new GUI interface using Java Swing, schedule view, date navigation, default calendar in system timezone, mutliple calendar support in GUI, event editing in GUI, and event deletion in GUI.

Don't work: We chose not to implement the optional features. (GUI recurring event creation, deletion, etc)

                          Work distribution:

Like the last assigment, we started by first designing how each new functions would work. But since this time the work was more linear, we pair programmed the GUI and then the extra credit features together. Then Raymond did the readme and useme while Samuel did the jar and screenshot.

                          Additional information:
None so far.
