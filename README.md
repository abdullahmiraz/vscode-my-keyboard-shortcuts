# vscode-my-keyboard-shortcuts
My custom vscode keyboard shortcuts/keymap/ keybindings
echo "# vscode-my-keyboard-shortcuts" >> README.md
git init  
git add README.md  
git commit -m "first commit"  
git branch -M main  
git remote add origin https://github.com/abdullahmiraz/vscode-my-keyboard-shortcuts.git  
git push -u origin main  
  
| Keybinding              | Command   | When       | Does             | Source |
| --------------- | ------------ | ------------------ | -------------- | -------- |
| `ctrl+c`         | editor.action.clipboardCopyAction | editorTextFocus     | Copies the selected text to the clipboard      | System   |
| `ctrl+x`         | editor.action.clipboardCutAction  | editorTextFocus    | Cuts the selected text to the clipboard        | System   |
| `ctrl+v`         | editor.action.clipboardPasteAction | editorTextFocus                              | Pastes the contents of the clipboard           | System   |
| `ctrl+z`         | undo                          |                                                  | Undoes the previous action                     | System   |
| `ctrl+shift+z`   | redo                          |                                                  | Redoes the previous action                     | System   |
| `ctrl+a`         | editor.action.selectAll       |                                                  | Selects all text in the active editor          | System   |
| `ctrl+f`         | actions.find                  |                                                  | Opens the Find panel                           | System   |
| `ctrl+h`         | editor.action.startFindReplaceAction |                                              | Opens the Replace panel                        | System   |
| `ctrl+space`     | editor.action.triggerSuggest  | editorTextFocus                                 | Triggers code suggestions                      | System   |
| `alt+mouse select` | editor.action.insertCursorAtEndOfEachLineSelected | editorTextFocus && mousePressed            | Inserts a cursor at the end of each selected line | System   |
| `ctrl+shift+q`   | java.debug.runJavaFile        |                                                  | Runs the Java file                              | User     |
| `ctrl+shift+a`   | -extension.currentAREPLSession | !inQuickOpen && !terminalFocus                   | Disables the current AREPL session              | User     |
| `ctrl+shift+a`   | code-runner.run               |                                                  | Runs the code using Code Runner extension       | User     |
| `ctrl+alt+n`     | -code-runner.run              |                                                  | Disables Code Runner extension                  | User     |
| `ctrl+shift+space` | -editor.action.triggerParameterHints | editorHasSignatureHelpProvider && editorTextFocus | Disables trigger for parameter hints         | User     |
| `ctrl+shift+space` | workbench.action.toggleActivityBarVisibility |                                      | Toggles the visibility of the activity bar      | System   |
| `shift+home`     | expandLineSelection           | textInputFocus                                   | Expands the line selection                      | System   |
| `ctrl+l`         | -expandLineSelection          | textInputFocus                                   | Disables line selection expansion                | User     |
| `shift+l`        | cursorHomeSelect              | textInputFocus                                   | Selects from the cursor to the line start        | System   |
| `shift+home`     | -cursorHomeSelect             | textInputFocus                                   | Disables cursor home selection                   | User     |
| `ctrl+tab`       | workbench.action.openNextRecentlyUsedEditor |                                            | Switches to the next recently used editor       | System   |
| `ctrl+\``        | workbench.action.terminal.toggleTerminal |                                        | Toggles the visibility of the terminal           | System   |
| `esc`            | workbench.action.closeQuickOpen |                                          | Closes the Quick Open panel                      | System   |
| `ctrl+k ctrl+s`  | workbench.action.openGlobalKeybindings |                                     | Opens the Keyboard Shortcuts settings           | System   |
| `ctrl+shift+p`   | workbench.action.showCommands |                                                  | Opens the command palette                        | System   |
| `space`          | leaveSnippet                  | editorTextFocus && inSnippetMode                 | Leaves the snippet mode and highlights          | User     |

