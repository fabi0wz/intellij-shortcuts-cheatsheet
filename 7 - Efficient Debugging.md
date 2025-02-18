# Debugging - Cheat Sheet  
## Breakpoint Control  
| **Action**                    | **Shortcuts**           | **Description** |
|------------------------------|------------------------|-----------------|
| **Add/Remove Breakpoint**    | `Ctrl + F8`            | Adds or removes a breakpoint on current line |
| **Enable/Disable Breakpoint**| `Ctrl + Shift + F8`    | Enables or disables a breakpoint without removing it |
| **Conditional Breakpoints**  | Right-click breakpoint | Sets conditions for when the breakpoint should pause |
| **Dependent Breakpoints**    | Configure "Disable until breakpoint is hit" | Sets a breakpoint that only activates when another is hit |
| **Log Message Breakpoints**  | Edit breakpoint and check "Log message" | Logs messages to console without interrupting execution |
---
## Execution Control During Debug  
| **Action**              | **Shortcuts**         | **Description** |
|------------------------|---------------------|-----------------|
| **Start Debug**        | `Shift + F9`        | Starts program execution in debug mode |
| **Stop Execution**     | `Ctrl + F2`         | Stops program execution |
| **Continue Execution** | `F9`                | Resumes execution until next breakpoint |
| **Step Over**          | `F8`                | Executes current line without stepping into methods |
| **Step Into**          | `F7`                | Steps into the method called on current line |
| **Step Out**           | `Shift + F8`        | Continues until exiting current method |
| **Run to Cursor**      | `Alt + F9`          | Continues execution to cursor position |
---
## Variable and Expression Analysis  
| **Action**                  | **Shortcuts**              | **Description** |
|----------------------------|---------------------------|-----------------|
| **Evaluate Expressions**    | `Alt + F8`                | Test expression values during debug |
| **Add Variable to Watch**   | `Ctrl + Shift + F8`       | Tracks specific variable values during execution |
| **Modify Variable Value**   | Double-click variable     | Allows changing values during execution |
| **View Object References**  | `Alt + Click` on variable | Expands object details in debugger panel |
---