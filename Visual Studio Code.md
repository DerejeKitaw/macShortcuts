## Visual code shortcut key

command + right arrow to take the arrow to the end of line
comand + Enter ——to go to the next line
command + 2 open two panels in visual studio
command + [ —move the hole one of code to left and right ]

⌘X	Cut line (empty selection)	
⌘C	Copy line (empty selection)	
⇧⌘K	Delete Line	
⌘Enter	Insert Line Below	
⇧⌘Enter	Insert Line Above	
⌥↓	Move Line Down	
⌥↑	Move Line Up	
⇧⌥↓	Copy Line Down	
⇧⌥↑	Copy Line Up	
⌘D	Add Selection To Next Find Match	
⌘K ⌘D	Move Last Selection To Next Find Match	
⌘U	Undo last cursor operation	
⇧⌥I	Insert cursor at end of each line selected	
## ⇧⌘L	Select all occurrences of current selection	
⌘F2	Select all occurrences of current word
⌘I	Select current line	expandLineSelection
⌥⌘↓	Insert Cursor Below	
⌥⌘↑	Insert Cursor Above	
⇧⌘\	Jump to matching bracket	
⌘]	Indent Line	
⌘[	Outdent Line	
Home	Go to Beginning of Line	cursorHome
End	Go to End of Line	
⌘↓	Go to End of File	
⌘↑	Go to Beginning of File	
⌃PageDown	Scroll Line Down	
⌃PageUp	Scroll Line Up	scrollLineUp
⌘PageDown	Scroll Page Down	
⌘PageUp	Scroll Page Up	
⇧⌘[	Fold (collapse) region	
⇧⌘]	Unfold (uncollapse) region	
⌘K ⌘[	Fold (collapse) all subregions	
⌘K ⌘]	Unfold (uncollapse) all subregions	
⌘K ⌘0	Fold (collapse) all regions	
⌘K ⌘J	Unfold (uncollapse) all regions	
⌘K ⌘C	Add Line Comment	
⌘K ⌘U	Remove Line Comment	
⌘/	Toggle Line Comment	
⇧⌥A	Toggle Block Comment	
⌘F	Find	
⌥⌘F	Replace	
⌘G	Find Next	
⇧⌘G	Find Previous	
⌥Enter	Select All Occurences of Find Match	
⌥⌘C	Toggle Find Case Sensitive	
⌥⌘R	Toggle Find Regex	
⌥⌘W	Toggle Find Whole Word	
⌃⇧M	Toggle Use of Tab Key for Setting Focus	
unassigned	Toggle Render Whitespace


Rich Languages Editing

Key	Command	Command id
⌃Space	Trigger Suggest	editor.action.triggerSuggest
⇧⌘Space	Trigger Parameter Hints	editor.action.triggerParameterHints
⇧⌥F	Format Code	editor.action.format
F12	Go to Definition	editor.action.goToDeclaration
⌥F12	Peek Definition	editor.action.previewDeclaration
⌘K F12	Open Definition to the Side	editor.action.openDeclarationToTheSide
⌘.	Quick Fix	editor.action.quickFix
⇧F12	Show References	editor.action.referenceSearch.trigger
F2	Rename Symbol	editor.action.rename
⇧⌘.	Replace with Next Value	editor.action.inPlaceReplace.down
⇧⌘,	Replace with Previous Value	editor.action.inPlaceReplace.up
⌃⇧⌘→	Expand AST Select	editor.action.smartSelect.grow
⌃⇧⌘←	Shrink AST Select	editor.action.smartSelect.shrink
⌘K ⌘X	Trim Trailing Whitespace	editor.action.trimTrailingWhitespace
⌘K M	Change Language Mode	workbench.action.editor.changeLanguageMode
Navigation

Key	Command	Command id
⌘T	Show All Symbols	workbench.action.showAllSymbols
⌃G	Go to Line...	workbench.action.gotoLine
⌘P	Go to File..., Quick Open	workbench.action.quickOpen
⇧⌘O	Go to Symbol...	workbench.action.gotoSymbol
⇧⌘M	Show Problems	workbench.actions.view.problems
F8	Go to Next Error or Warning	editor.action.marker.next
⇧F8	Go to Previous Error or Warning	editor.action.marker.prev
⇧⌘P	Show All Commands	workbench.action.showCommands
⌃⇧Tab	Navigate Editor Group History	workbench.action.openPreviousRecentlyUsedEditorInGroup
⌃-	Go Back	workbench.action.navigateBack
⌃⇧-	Go Forward	workbench.action.navigateForward
Editor/Window Management

Key	Command	Command id
⇧⌘N	New Window	workbench.action.newWindow
⌘W	Close Window	workbench.action.closeWindow
⌘W	Close Editor	workbench.action.closeActiveEditor
⌘K F	Close Folder	workbench.action.closeFolder
unassigned	Cycle Between Editor Groups	workbench.action.navigateEditorGroups
⌘\	Split Editor	workbench.action.splitEditor
⌘1	Focus into Left Editor Group	workbench.action.focusFirstEditorGroup
⌘2	Focus into Side Editor Group	workbench.action.focusSecondEditorGroup
⌘3	Focus into Right Editor Group	workbench.action.focusThirdEditorGroup
⌘K ⌘←	Focus into Editor Group on the Left	workbench.action.focusPreviousGroup
⌘K ⌘→	Focus into Editor Group on the Right	workbench.action.focusNextGroup
⌘K ⇧⌘←	Move Editor Left	workbench.action.moveEditorLeftInGroup
⌘K ⇧⌘→	Move Editor Right	workbench.action.moveEditorRightInGroup
⌘K ←	Move Active Editor Group Left	workbench.action.moveActiveEditorGroupLeft
⌘K →	Move Active Editor Group Right	workbench.action.moveActiveEditorGroupRight
File Management

Key	Command	Command id
⌘N	New File	workbench.action.files.newUntitledFile
unassigned	Open File...	workbench.action.files.openFile
⌘S	Save	workbench.action.files.save
unassigned	Save All	workbench.action.files.saveAll
⇧⌘S	Save As...	workbench.action.files.saveAs
⌘W	Close	workbench.action.closeActiveEditor
⌥⌘T	Close Others	workbench.action.closeOtherEditors
⌘K W	Close Group	workbench.action.closeEditorsInGroup
unassigned	Close Other Groups	workbench.action.closeEditorsInOtherGroups
unassigned	Close Group to Left	workbench.action.closeEditorsToTheLeft
unassigned	Close Group to Right	workbench.action.closeEditorsToTheRight
⌘K ⌘W	Close All	workbench.action.closeAllEditors
⇧⌘T	Reopen Closed Editor	workbench.action.reopenClosedEditor
⌘K Enter	Keep Open	workbench.action.keepEditor
⌃Tab	Open Next	workbench.action.openNextRecentlyUsedEditorInGroup
⌃⇧Tab	Open Previous	workbench.action.openPreviousRecentlyUsedEditorInGroup
⌘K P	Copy Path of Active File	workbench.action.files.copyPathOfActiveFile
⌘K R	Reveal Active File in Windows	workbench.action.files.revealActiveFileInWindows
⌘K O	Show Opened File in New Window	workbench.action.files.showOpenedFileInNewWindow
unassigned	Compare Opened File With	workbench.files.action.compareFileWith
Display

Key	Command	Command id
⌃⌘F	Toggle Full Screen	workbench.action.toggleFullScreen
⌘=	Zoom in	workbench.action.zoomIn
⌘-	Zoom out	workbench.action.zoomOut
unassigned	Reset Zoom	workbench.action.zoomReset
⌘B	Toggle Sidebar Visibility	workbench.action.toggleSidebarVisibility
⇧⌘D	Show Debug	workbench.view.debug
⇧⌘E	Show Explorer / Toggle Focus	workbench.view.explorer
⌃⇧G	Show Git	workbench.view.git
⇧⌘F	Show Search	workbench.view.search
⇧⌘H	Replace in Files	workbench.action.replaceInFiles
⇧⌘X	Show Extensions	workbench.view.extensions
⇧⌘J	Toggle Search Details	workbench.action.search.toggleQueryDetails
⇧⌘C	Open New Command Prompt	workbench.action.terminal.openNativeConsole
⇧⌘U	Show Output	workbench.action.output.toggleOutput
⇧⌘V	Toggle Markdown Preview	markdown.showPreview
⌘K V	Open Preview to the Side	markdown.showPreviewToSide
⌃`	Toggle Integrated Terminal	workbench.action.terminal.toggleTerminal
Preferences

Key	Command	Command id
⌘,	Open User Settings	workbench.action.openGlobalSettings
unassigned	Open Workspace Settings	workbench.action.openWorkspaceSettings
unassigned	Open Keyboard Shortcuts	workbench.action.openGlobalKeybindings
unassigned	Open User Snippets	workbench.action.openSnippets
unassigned	Select Color Theme	workbench.action.selectTheme
unassigned	Configure Display Language	workbench.action.configureLocale
Debug

Key	Command	Command id
F9	Toggle Breakpoint	editor.debug.action.toggleBreakpoint
F5	Continue	workbench.action.debug.continue
F5	Pause	workbench.action.debug.start
F11	Step Into	workbench.action.debug.stepInto
⇧F11	Step Out	workbench.action.debug.stepOut
F10	Step Over	workbench.action.debug.stepOver
⇧F5	Stop	workbench.action.debug.stop
⌘K ⌘I	Show Hover	editor.action.showHover
Tasks

Key	Command	Command id
⇧⌘B	Run Build Task	workbench.action.tasks.build
unassigned	Run Test Task	workbench.action.tasks.test
Extensions

Key	Command	Command id
unassigned	Install Extension	workbench.extensions.action.installExtension
unassigned	Show Installed Extensions	workbench.extensions.action.showInstalledExtensions
unassigned	Show Outdated Extensions	workbench.extensions.action.listOutdatedExtensions
unassigned	Show Recommended Extensions	workbench.extensions.action.showRecommendedExtensions
unassigned	Show Popular Extensions	workbench.extensions.action.showPopularExtensions
unassigned	Update All Extensions	workbench.extensions.action.updateAllExtensions
Customizing Shortcuts

All keyboard shortcuts in VS Code can be customized via theUser/keybindings.json file.

To configure keyboard shortcuts the way you want, go to the menu under File >Preferences > Keyboard Shortcuts. (Code > Preferences > Keyboard Shortcutson Mac)
This will open the Default Keyboard Shortcuts on the left and yourUser/keybindings.json file where you can overwrite the default bindings on the right.
Keyboard Rules

The keyboard shortcuts dispatching is done by analyzing a list of rules that are expressed in JSON. Here are some examples:

// Keybindings that are active when the focus is in the editor
{ "key": "home",            "command": "cursorHome",                  "when": "editorTextFocus" },
{ "key": "shift+home",      "command": "cursorHomeSelect",            "when": "editorTextFocus" },

// Keybindings that are complementary
{ "key": "f5",              "command": "workbench.action.debug.continue", "when": "inDebugMode" },
{ "key": "f5",              "command": "workbench.action.debug.start",    "when": "!inDebugMode" },

// Global keybindings
{ "key": "ctrl+f",          "command": "actions.find" },
{ "key": "alt+left",        "command": "workbench.action.navigateBack" },
{ "key": "alt+right",       "command": "workbench.action.navigateForward" },

// Global keybindings using chords (two separate keypress actions)
{ "key": "ctrl+k enter",    "command": "workbench.action.keepEditor" },
{ "key": "ctrl+k ctrl+w",   "command": "workbench.action.closeAllEditors" },
Each rule consists of:

a key that describes the pressed keys.
a command containing the identifier of the command to execute.
an optional when clause containing a boolean expression that will be evaluated depending on the current context.
Chords (two separate keypress actions) are described by separating the two keypresses with a space. E.g.: ctrl+k ctrl+c.

When a key is pressed:

the rules are evaluated from bottom to top.
the first rule that matches, both the key and in terms of when, is accepted.
no more rules are processed.
if a rule is found and has a command set, the command is executed.
The additional User/keybindings.json rules are appended at runtime to the bottom of the default rules, thus allowing them to overwrite the default rules. TheUser/keybindings.json file is watched by VS Code so editing it while VS Code is running will update the rules at runtime.

Accepted keys

The key is made up of modifiers and the key itself.

The following modifiers are accepted:

Platform	Modifiers
Mac	ctrl+, shift+, alt+, cmd+
Windows	ctrl+, shift+, alt+, win+
Linux	ctrl+, shift+, alt+, meta+