# To-Do-List-

# *Problem Statement

* Students need a simple way to create, store, and manage notes or tasks.
* Existing apps are often complex or require internet access.
* A lightweight, offline, beginner-friendly solution is required.

---

# *Objectives*

* To allow users to create, view, edit, delete, and search notes.
* To store notes permanently using a simple JSON file system.
* To provide an easy menu-driven console interface.
* To apply basic Python programming concepts in a real project.
* To build a functional CRUD-based application.

---

# *Functional Requirements*

* Create a new note with title, content, category, and priority.
* View all saved notes.
* Update an existing note.
* Delete a selected note.
* Search notes by keyword or category.
* Store and load notes from JSON.

---

# *Non-Functional Requirements*

* Easy to use and beginner-friendly interface.
* Simple and readable codebase for maintainability.
* Fast performance for small datasets.
* Reliable storage using JSON.
* Portable across Windows, macOS, and Linux.

---

# *System Architecture Diagram *

```
User (Console)
      ↓
Application Logic (Simple Functions)
      ↓
JSON File Storage (notes.json)
```

---

# *Process Flow / Workflow Diagram*

```
Start → Show Menu → User Choice →
(Create / View / Edit / Delete / Search) →
Save Changes → Back to Menu → Exit
```

---

# *Class / Component Diagram*

(Not using classes → simple component structure)

* Components:

  * Input/Output Module
  * Note Operations Module
  * Storage Module (JSON)

# *Sequence Diagram (Example: Create Note)*

```
User → Menu → create_note() → save_notes() → JSON File
```

---

# *Database / Storage Design*

# *ER Diagram (Text Form)*

```
+------------------+
|      NOTE        |
+------------------+
| id               |
| title            |
| content          |
| category         |
| priority         |
| created_at       |
| updated_at       |
+------------------+
```

# *Schema Design (JSON Structure)*

```json
{
  "id": "123",
  "title": "Example",
  "content": "Sample note",
  "category": "Study",
  "priority": "High",
  "created_at": "",
  "updated_at": ""
}
```

---

# *Overview of the Project*

* A simple Python console application to manage personal notes.
* Supports CRUD operations with JSON-based storage.
* Designed for first-semester students learning basic programming.

---

# *Features*

* Create, view, edit, delete notes.
* Search by keyword or category.
* Auto-save to JSON file.
* Easy and lightweight menu-driven interface.
* Offline and portable.

---

# *Technologies / Tools Used*

* Python 3.8+
* JSON for file storage
* Any text editor (VS Code, Notepad++, PyCharm)
* Command Prompt / Terminal

---

# *Steps to Install & Run the Project*

* Install Python 3.8+.
* Download the project folder.
* Open terminal inside the folder.
* Run the command:

  ```
  python notes_app.py
  ```
* Start using the menu options.

---

# *Instructions for Testing*

* Create 2–3 notes and verify they appear in the list.
* Try editing and deleting notes.
* Test searching with keywords.
* Open `notes.json` to confirm notes are saved.

---
