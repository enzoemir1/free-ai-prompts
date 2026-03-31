# ChatGPT Developer Prompts — Free Sample

> 10 free prompts out of 259. Compatible with ChatGPT, Claude, Gemini.

> **Full pack:** [Etsy Shop](https://www.etsy.com/shop/automatiabcn)

---

### Prompt 1

```
You have a legacy Python script at [FILE_PATH] containing a function named [FUNCTION_NAME] that exceeds 100 lines and mixes I/O with business logic. Refactor this function into smaller, pure functions, add type hints, and write a docstring for each new function. **Output format**: 1) a brief summary of changes, 2) the refactored code in a markdown block with ```python``` tag, 3) a list of new helper function names.
```

💡 **Tip:** Start by extracting logical sections into separate functions before adding type hints.

---

### Prompt 2

```
Transform a legacy PHP script located at [FILE_PATH] that mixes procedural code with HTML into PSR‑12 compliant OOP modules. Create a class [CLASS_NAME] for business logic and a separate view template. **Output format**: 1) a list of files to create, 2) the class code in a markdown block with ```php``` tag, 3) the cleaned HTML template, and 4) a migration checklist.
```

💡 **Tip:** First separate PHP logic from HTML using output buffering, then refactor the logic into methods.

---

### Prompt 3

```
Migrate a legacy SQL script at [FILE_PATH] that contains hard‑coded values into a parameterized query using Python's SQLAlchemy ORM. Create a function [FUNCTION_NAME] that accepts parameters and returns the query result. **Output format**: 1) the original SQL snippet, 2) the new Python function in a markdown block with ```python``` tag, and 3) a brief security note on why parameterization matters.
```

💡 **Tip:** Map each hard‑coded value to a function argument and use `bindparam` or the ORM’s query API.

---

### Prompt 4

```
Transform a monolithic [FRAMEWORK] application into a microservices architecture, with each service responsible for a specific [DOMAIN_MODEL]. Ensure the services communicate with each other using [COMMUNICATION_PROTOCOL] and follow the principles of clean code. Document the architecture using UML diagrams and write a brief report on the benefits of the new design.
```

💡 **Tip:** Use a containerization platform to manage the microservices

---

### Prompt 5

```
Clean up a legacy [DATABASE] schema by removing redundant tables and normalizing the data. Use [DATABASE_MODELING_TOOL] to design a new schema and [SQL_DIALECT] to write the migration scripts. Document the changes in a changelog file and include example queries to demonstrate the improvements.
```

💡 **Tip:** Use a data modeling tool to visualize the new schema

---

### Prompt 6

```
Transform a legacy [USER_INTERFACE] component into a modern, responsive design using [FRONTEND_FRAMEWORK]. Ensure the new design is accessible and follows the principles of clean code. Use [STYLE_GUIDE] to format the code and include example usage in a separate file. Write a brief explanation of the refactoring process and the benefits of the new design.
```

💡 **Tip:** Use a UI component library to simplify the design process

---

### Prompt 7

```
Clean up a legacy [CONFIGURATION_FILE] by removing redundant settings and organizing the configuration into logical sections. Use [CONFIGURATION_FORMAT] to format the file and include example usage in a separate file. Write a brief explanation of the refactoring process and the benefits of the new design.
```

💡 **Tip:** Use a configuration management tool to simplify the process

---

### Prompt 8

```
Transform a legacy [DATA_PROCESSING_PIPELINE] into a modern, scalable implementation using [DATA_PROCESSING_FRAMEWORK]. Ensure the new design is efficient and follows the principles of clean code. Use [FORMAT_STYLE] to format the code and include example usage in a separate file. Write a brief explanation of the refactoring process and the benefits of the new design.
```

💡 **Tip:** Use a data processing tool to simplify the design process

---

### Prompt 9

```
Act as a C# architect. Transform the legacy [FORM_NAME].cs WinForms file that directly calls SQL inside event-handlers into an MVP pattern. Provide the refactored view interface [IVIEW_NAME], presenter [PRESENTER_NAME], and DTOs in separate files. Use async/await for data access and include a unit-test project with NSubstitute mocks. Return code as fully-qualified C# 11.0 files in Markdown code fences.
```

💡 **Tip:** Extract SQL into an async repository method returning Task<IReadOnlyList<T>> to keep the presenter testable.

---

### Prompt 10

```
Given a monolithic Java class at [FILE_PATH] called [CLASS_NAME] that handles data access, validation, and UI rendering, split it into three clean modules: a DAO, a validator, and a view model. Preserve existing public APIs. **Output format**: a table mapping original methods to new classes, followed by three separate markdown code blocks (```java```) for each new class, and a short migration guide.
```

💡 **Tip:** Identify method groups by responsibility and move them together to maintain cohesion.

---

## Get the Full Pack

This is just **10 out of 259** prompts.

The full **ChatGPT Developer Prompts** pack includes 259 copy-paste ready prompts across multiple categories.

**Buy on Etsy:** [automatiabcn](https://www.etsy.com/shop/automatiabcn)
