# Hxckr Courses Curriculum

This repository contains the curriculum for various courses offered by Hxckr. Each course is organized into a dedicated folder, with the curriculum stored in a markdown file. Below is an overview of the structure and the purpose of each component within the repository.

## Table of Contents

1. [Course Structure](#course-structure)
2. [Curriculum Format](#curriculum-format)
3. [Adding a New Course](#adding-a-new-course)

### Course Structure

Each course is stored in a dedicated folder within the `courses` directory. The folder name typically corresponds to the course title. Inside each course folder, you will find the following components:

- `curriculum.md`: This markdown file contains the detailed curriculum for the course. It outlines the modules, lessons, and topics covered in each course.
- `starter-code/`: This files contains the starter code for the course.
- `modules/`: This directory contains subdirectories for each module within the course.
- `instructions.md`: This file contains the instructions for the course.

### Curriculum Format

The curriculum is organized using a structured format to ensure consistency and clarity. Here is an example of the expected format:

```bash
Course Name
├── curriculum.md
├── starter-code
├── module1
│   ├── instructions.md
│   └── tests
├── module2
│   ├── instructions.md
│   └── tests
├── module3
│   ├── instructions.md
│   └── tests
│......
```

### Adding a New Course

To add a new course, follow these steps:

1. **Create an issue**:
   - Open an issue in the repository with the course name, description, and curriculum.

2. **Add curriculum**:
   - Create a new markdown file named `curriculum.md` inside the course folder.
   - Use the existing curriculum format as a template to structure the content for your course.

3. **Add starter code**:
   - Create a new file named `starter-code` inside the course folder.
   - Add the starter code files for the course.
   - The starter code should be written such that it can be used for the whole course.

4. **Add each module**:
    - for each topic in the curriculum, create a new folder inside the course folder.
    - inside each folder, add the instructions for the module and the tests.
    - the tests should be written such that they can be used to run the code in the module.

5. **Review and iterate**:
   - Review the curriculum and starter code for any necessary updates or improvements.
   - Iterate on the curriculum and starter code until you are satisfied with the course content.

## Contributing

We welcome contributions to the Hxckr Courses Curriculum repository! If you have suggestions for improving the curriculum or adding new courses, please open an issue or submit a pull request.
