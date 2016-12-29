# life_simulator

In this coursework you are required to implement an application, the “Artificial Life Simulator”, to
manage, run and visualise simulations of artificial life forms on 2D maps. The horizontal and vertical
dimensions of the 2D map should be user-defined parameters. A life form should be able to move, sense
the environment (sight, smell, etc.), find and eat food to increase its energy/stamina level. By using
inheritance several different types of life forms should be developed. Life forms may prefer some type of
food over others (e.g., carnivores vs herbivores). Some life forms may have a complex behaviour and
organise themselves in social groups or communicate with others to hunt. When the life form performs an
action (moving, sensing) its energy/stamina level is decreased. The environment can contain life forms,
food entities containing some amount of calories or poison. Complex food entities may be able to provide
a continuous source of food (e.g.. grass, plant, fruit trees, etc.). The environment contains obstacles (such
as rocks, trees, etc.). Some objects in the environment may be changed by the life forms (such nests, dens,
etc.) and used for protection. Life forms and other entities should be shown on the map by means of icons
or images.
Each student may determine the richness and complexity of the simulation and use creativity, however
remember that richness impacts positively on the final mark.
Graphical User Interface: A Graphical User Interface (GUI) based on JavaFX must be provided. You
can use the Java console (stdin/stdout) only for displaying debugging information. The GUI has menus
with menu items and a toolbar with buttons to control the simulation (e.g., start, pause, reset, etc.).
IMPORTANT: GUI based on GUI builder tools will not be accepted: the GUI must be hand-coded by
using the JavaFX API directly.
Configurations File: The application allows the user to save and load simulation configurations from
files. A configuration is defined as the set of parameters required to set up and start a simulation. The
application should also remember the last configuration file used when the application is restarted and
should automatically load the last configuration when started.
Application Menu: The application should be organized in 5 menus as shown in Figure 1. A different
structure of the menu items is acceptable as long as they provide an equivalent set of features.
You can make design choices about what the menu items are, as long as you describe these choices in the
design section of the report.
Inheritance: the code should make use of either an abstract class or an interface. Generics must be used
throughout the code.
Animation: You can use any method, as long as you use JavaFX, to achieve the animation.
CS2JA16 Java - Major Coursework #1 Prof Richard Mitchell
University of Reading - Department of Computer Science 3
File
1. New configuration (reset configuration, no file is created)
2. Open configuration file (using your own file format, e.g. CSV)
3. Save (using your own file format)
4. Save as (allows to change the file name)
5. Exit
View
1. Display configuration
2. Edit configuration
3. Display info about life forms (e.g., list of <ID, name, position, energy>)
4. Display info about map (size, obstacles, food)
Edit
1. Modify current life form parameters
2. Remove current life form
3. Add a new life form
Simulation
1. Run
2. Stop
3. Pause/restart
4. Reset
5. Display map at each iteration: ON/OFF (toggle between ON and OFF)
Help
1. Display info about application
2. Display info about author
Figure 1: Application Menu
INSTRUCTIONS
1. Initial Demonstration: You are required to demonstrate a console version of your program in the
allotted slot on Wednesday of Week 6 of the Autumn term and to get a demo mark sheet signed
by an assistant during your practical session in the Week 2 of the Spring Term. Missing the
demonstration will impact your final mark negatively. If you have an officially approved
extenuating circumstance then contact Richard Mitchell by e-mail (r.j.mitchell@reading.ac.uk) to
set up an alternative demonstration timeslot.
2. Final Demonstration: You are required to demonstrate the final application and to get a demo
mark sheet signed by an assistant during your practical session in the Week 2 of the Spring
Term. Missing the demonstration will impact your final mark negatively. If you have an officially
approved extenuating circumstance then contact Richard Mitchell by e-mail
(r.j.mitchell@reading.ac.uk) to set up an alternative demonstration timeslot.
3. Electronic submission:
a. You are required to submit an electronic report in docx / pdf format on Blackboard by
the specified deadline. The report (max 10 pages of A4, 12 pt font) should include:
i. A brief abstract. A short introduction.
ii. A description of the OOP design of your application (list/explanation of classes,
UML diagrams, data design etc.) with a critical analysis of the design you were
provided throughout the weekly practical sessions. (Remember to use appropriate
software engineering methods)
iii. A short informal presentation of the final application (including screenshots of GUI
and user manual),
iv. Tests, discussion and short conclusions with your personal reflection on this
project.
b. You are required to submit an electronic copy of your code (runnable jar archive
including source code) in Blackboard by deadline specified in the header. This file should
include a top-level folder named “javadoc” containing the Javadoc documentation as a
website.
