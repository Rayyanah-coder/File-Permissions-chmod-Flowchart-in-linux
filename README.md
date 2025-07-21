# File-Permissions-chmod-Flowchart-in-linux
This project demonstrates a fundamental understanding of Linux file permissions using the `chmod` command. It includes a flowchart that explains how file permissions work
---

## 🎯 Task Objective

- Understand Linux file permissions (`r`, `w`, `x`)
- Create a flowchart illustrating how permissions apply to:
  - User (owner)
  - Group
  - Others
- Apply the `chmod` command to give a file the permission: `rwxrwxr-x` (i.e., 775)
see test.png
---

## 🔧 Permissions Breakdown

The permission string `rwxrwxr-x` means:

| Who      | Permissions | Binary | Octal |
|----------|-------------|--------|-------|
| User     | `rwx`       | 111    | 7     |
| Group    | `rwx`       | 111    | 7     |
| Others   | `r-x`       | 101    | 5     |

Total octal representation: **775**

---

📊 Flowchart
The project includes a flowchart image (see flowchart.jpeg)
