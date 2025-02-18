# IntelliJ Postfix Completions Cheat Sheet - Java

## Variable Declaration & Assignment
| Completion | Description | Example |
|------------|-------------|----------|
| `.var` | Create a variable with inferred type | `"hello".var` → `String name = "hello"` |
| `.val` | Create a final variable | `calculateValue().val` → `final int value = calculateValue()` |
| `.field` | Create a field from expression | `"default".field` → `private String field = "default"` |
---
## Control Flow
| Completion | Description | Example |
|------------|-------------|----------|
| `.if` | Create if statement | `count.if` → `if (count) {}` |
| `.else` | Create negative if statement | `count.else` → `if (!count) {}` |
| `.while` | Create while loop | `iterator.while` → `while (iterator) {}` |
| `.for` | Create for loop | `list.for` → `for (Item item : list) {}` |
| `.fori` | Create indexed for loop | `list.fori` → `for (int i = 0; i < list.length; i++) {}` |
| `.try` | Surround with try-catch | `riskyCall().try` → `try { riskyCall(); } catch (Exception e) {}` |
---
## Checks & Assertions
| Completion | Description | Example |
|------------|-------------|----------|
| `.null` | Check for null | `obj.null` → `if (obj == null) {}` |
| `.notnull` | Check for not null | `obj.notnull` → `if (obj != null) {}` |
| `.nn` | Assert not null | `obj.nn` → `assert obj != null` |
| `.assert` | Create assertion | `count.assert` → `assert count` |
---
## Collections & Arrays
| Completion | Description | Example |
|------------|-------------|----------|
| `.toar` | Convert to array | `list.toar` → `list.toArray(new Type[0])` |
| `.stream` | Create stream | `list.stream` → `list.stream()` |
| `.format` | String format | `"User %s".format` → `String.format("User %s", param)` |
---
## Output & Logging
| Completion | Description | Example |
|------------|-------------|----------|
| `.sout` | System.out.println() | `"message".sout` → `System.out.println("message")` |
| `.soutv` | Print variable | `count.soutv` → `System.out.println("count = " + count)` |
| `.return` | Return value | `value.return` → `return value` |
---
## Boolean Operations
| Completion | Description | Example |
|------------|-------------|----------|
| `.not` | Negate expression | `condition.not` → `!condition` |
| `.if` | Check boolean condition | `isValid.if` → `if (isValid) {}` |
| `.while` | While boolean condition | `isRunning.while` → `while (isRunning) {}` |
---
## Optional Handling
| Completion | Description | Example |
|------------|-------------|----------|
| `.opt` | Wrap with Optional | `value.opt` → `Optional.ofNullable(value)` |
| `.par` | Wrap with parentheses | `expr.par` → `(expr)` |
---