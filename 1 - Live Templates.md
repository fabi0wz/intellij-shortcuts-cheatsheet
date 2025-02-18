# IntelliJ IDEA Live Templates Cheatsheet

## Java Templates

| Shortcut | Description | Expands To |
|----------|-------------|------------|
| `psvm` | Main method | `public static void main(String[] args)` |
| `main` | Main method | `public static void main(String[] args)` |
| `prsf` | Private static final | `private static final` |
| `psf` | Public static final | `public static final` |
| `sout` | Print to console | `System.out.println()` |
| `souf` | Print formatted | `System.out.printf()` |
| `soutm` | Print method name | `System.out.println("method name")` |
| `soutv` | Print variable | `System.out.println("variable = " + variable)` |
| `fori` | For loop | `for (int i = 0; i < ; i++)` |
| `iter` | Enhanced for | `for (element : collection)` |
| `itar` | Array iteration | `for (int i = 0; i < arr.length; i++)` |
| `try` | Try-catch block | Try-catch structure |
| `thr` | Throw exception | `throw new` |
| `test` | Test method | Creates test method structure |

## Custom Template Creation

1. Navigate to: Settings → Editor → Live Templates
2. Click + to add new template
3. Define:
   - Abbreviation
   - Description
   - Template text
   - Applicable contexts
   - Variables (if needed)