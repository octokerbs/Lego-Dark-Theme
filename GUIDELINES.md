## Theme Color Guidelines

This document outlines the semantic meaning of each color in the theme, ensuring consistency and clarity in code representation. Colors are assigned based on the role of tokens in the code, helping developers quickly identify and understand different elements.

---

### **White (#FEF6D0)**

**Purpose:** Represents state-changing objects.  
**Scope:**

- Variables

**Rationale:** White is used for variables to highlight their mutable nature, making it clear when a value is subject to change.

---

### **Grey (#CAC8CB)**

**Purpose:** Neutral color for structural elements.  
**Scope:**

- Operators
- Brackets
- Punctuation

**Rationale:** Grey is used for syntax elements that provide structure to the code but do not carry semantic meaning themselves.

---

### **Black (#1E1E1E)**

**Purpose:** Base color for the editor.  
**Scope:**

- Editor background

**Rationale:** Black serves as the foundation of the theme, providing contrast and ensuring readability for all other colors.

---

### **Red (#FF5242)**

**Purpose:** Highlights language-specific keywords.  
**Scope:**

- Language keywords (e.g., control flow keywords like `if`, `else`, `for`, `while`)

**Rationale:** Red draws attention to keywords that define the logic and flow of the program, making them stand out.

---

### **Blue (#89b4fa)**

**Purpose:** Represents callable entities.  
**Scope:**

- Functions
- Methods
- Subroutines

**Rationale:** Blue is used for functions and methods to signify their role as actionable or callable components in the code.

---

### **Green (#C3E88D)**

**Purpose:** Segregates external and non-core elements.  
**Scope:**

- Comments
- Strings
- External modules

**Rationale:** Green adds vibrancy and helps distinguish external modules and non-executable elements (like comments and strings) from the core logic of the code.

---

### **Yellow (#F9CB5E)**

**Purpose:** Represents data structures and types.  
**Scope:**

- Types
- Classes
- Structs

**Rationale:** Yellow is used for types and classes to signify their role as foundational building blocks in the code.

---

### **Orange (#F78C6C)**

**Purpose:** Highlights literal values and constants.  
**Scope:**

- Constant variables
- Language defaults (e.g., numbers, booleans, `nil`, `null`)
- Function/Method parameters (if passed by value)

**Rationale:** Orange is used for values that are fixed or immutable, such as literals and constants. If a language passes arguments by reference, they should be white (as they are treated as variables).

---

### Notes:

- **Function/Method Parameters:** If a language passes arguments by reference, they should be white instead of orange, as they are treated as variables rather than fixed values.
- **External Modules:** Green is intentionally used for external modules to visually separate them from internal components, reinforcing their "external" nature.
