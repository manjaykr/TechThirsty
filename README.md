# JavaScript Coding Standards
## Spacing
`
Use spaces liberally throughout your code. “When in doubt, space it out.”

These rules encourage liberal spacing for improved developer readability. The minification process creates a file that is optimized for browsers to read and process.

* Indentation with tabs.
* No whitespace at the end of line or on blank lines.
* Lines should usually be no longer than 80 characters, and should not exceed 100 (counting tabs as 4 spaces). This is a “soft” rule, but     long lines generally indicate unreadable or disorganized code.
* if/else/for/while/try blocks should always use braces, and always go on multiple lines.
* Unary special-character operators (e.g., ++, --) must not have space next to their operand.
* Any , and ; must not have preceding space.
* Any ; used as a statement terminator must be at the end of the line.
* Any : after a property name in an object definition must not have preceding space.
* The ? and : in a ternary conditional must have space on both sides.
* No filler spaces in empty constructs (e.g., {}, [], fn()).
* There should be a new line at the end of each file.
* Any ! negation operator should have a following space.
* All function bodies are indented by one tab, even if the entire file is wrapped in a closure.
* Spaces may align code within documentation blocks or within a line, but only tabs should be used at the start of a line.
`
