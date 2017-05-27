# KAVI
Keyboard Accelerated Visual Interface

## What is KAVI
KAVI is a set of design principles around grahical user interfaces which are intended to provide the user with a VI like experience within a graphical setting of modern UI's.

## KAVI Design Principles
1.  All user interaction must be possible by using only the keyboard.
1.  All input from the user should flow as if typing a letter.  Hands should not be required to completely leave the home row position.
    1.  Special commands, navigation or other types of input must be able to be executed by using key sequences that are as close to possible to that which would constitute normal typing.
    1.  For example, keybinds which use 3 or 4 key combinations or keys far out of reach from the typing flow such as function keys should not be used.
1.  Navigation to visual UI elements should be direct.
    1.  This differes from current UI paradigms which use tab stops which must be sequenced through to the destination.
1.  The interface should provide direct access to actions.
    1.  This differs from current UI paradigms which are often hierarchy based.  For example the user may need to navigate a series of UI interactions such as cascading menus, tabs, pages etc.
1.  The UI should assist the user executing tasks by tracking tasks the user often performs in order to provide a fast method of input to select and repeat such tasks.
1.  The number of keystrokes required for all actions such as navigation and command execution should be short.
    
## KAVI Influences
These are some of the sources for ideas and concepts influencing KAVI.  With KAVI, we want to take a more holistic view of modern UI and see how the UI paradigm can be restructured with our design principles in mind.
1.  VI text editor
2.  Ace Jump
3.  Sublime command pallete 

## KAVI Implementation Rules
These are currently in-progress definitions that are being refined and added as these concepts are futher explored.
### Lists
1.  Lists must be scrollable by keyboard
1.  Items within the list must be selectable by keyboard
1.  Navigation to items in the list for selection or action must be direct.
    1.  A user should not have to sequence down one by one in a list.  If I see an item in the list I want to select, I should be able to do so directly.
1.  Lists must be filterable or searchable
1.  Lists of actions should be executable without additional buttons or controls
1.  Single action lists should execute immediately on selection without additonal input

## KAVI Implementations
1.  Eclipse Commander - A replacement for the Eclipse Quick Access feature built using the design principles of KAVI.  This is currently an Alpha of some of the first attempts at building UI controls with a KAVI paradigm.  Based on some of the experience here KAVI will be further revised and defined.
