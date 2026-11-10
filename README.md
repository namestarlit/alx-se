# ALX Software Engineering

A collection of my coursework and projects from the ALX Software Engineering
programme, bringing the original repositories together in one place.

The index below links directly to those repositories, where the project files,
instructions, commit history, and contributor credits live. This collection
includes both individual exercises and team projects.

## Foundation

### Core coursework

| Repository | Topics |
| --- | --- |
| [Zero day](https://github.com/namestarlit/alx-zero_day) | Introductory Git exercises |
| [Pre-course](https://github.com/namestarlit/alx-pre_course) | Git practice and repository workflows |
| [Low-level programming](https://github.com/namestarlit/alx-low_level_programming) | C, pointers, memory allocation, data structures, and file I/O |
| [Higher-level programming](https://github.com/namestarlit/alx-higher_level_programming) | Python, SQL, object-relational mapping, JavaScript, and web requests |
| [System engineering and DevOps](https://github.com/namestarlit/alx-system_engineering-devops) | Shell scripting, Linux, networking, web servers, deployment, and troubleshooting |

### C and algorithms

| Repository | Project |
| --- | --- |
| [printf](https://github.com/namestarlit/printf) | A custom implementation of formatted output in C |
| [Simple shell](https://github.com/namestarlit/simple_shell) | A command-line shell in C |
| [Monty](https://github.com/namestarlit/monty) | A bytecode interpreter using stacks and queues |
| [Sorting algorithms](https://github.com/namestarlit/sorting_algorithms) | Sorting implementations and complexity analysis |
| [Binary trees](https://github.com/namestarlit/binary_trees) | Tree operations, traversals, and properties |
| [RSA factoring challenge](https://github.com/namestarlit/RSA-Factoring-Challenge) | Integer factorization exercises |
| [Fix My Code Challenge](https://github.com/namestarlit/Fix_My_Code_Challenge) | Debugging exercises across existing programs |

### AirBnB clone

The AirBnB project spans four repositories, progressing from a console and data
models to a web application with an API and a dynamic interface.

| Repository | Focus |
| --- | --- |
| [AirBnB clone](https://github.com/namestarlit/AirBnB_clone) | Console, models, file storage, and static web pages |
| [AirBnB clone v2](https://github.com/namestarlit/AirBnB_clone_v2) | Database storage, Flask pages, and deployment scripts |
| [AirBnB clone v3](https://github.com/namestarlit/AirBnB_clone_v3) | REST API |
| [AirBnB clone v4](https://github.com/namestarlit/AirBnB_clone_v4) | Dynamic web interface |

## Backend specialisation

| Repository | Topics |
| --- | --- |
| [Backend Python](https://github.com/namestarlit/alx-backend-python) | Type annotations, asynchronous programming, unit and integration testing |
| [Backend JavaScript](https://github.com/namestarlit/alx-backend-javascript) | ES6, promises, classes, TypeScript, Node.js, and testing |
| [Backend storage](https://github.com/namestarlit/alx-backend-storage) | MySQL, MongoDB, and Redis |
| [Backend user data](https://github.com/namestarlit/alx-backend-user-data) | Personal data handling, basic and session authentication, and an authentication service |
| [Backend](https://github.com/namestarlit/alx-backend) | Pagination, caching, internationalization, and queues |
| [Interview exercises](https://github.com/namestarlit/alx-interview) | Algorithms and problem-solving exercises |
| [Files Manager](https://github.com/namestarlit/alx-files_manager) | File management project using Node.js, MongoDB, and Redis |

## Browse locally

The `foundation/` and `specialisation/` directories contain Git submodules pinned
to recorded commits. To download the collection and its project contents, use
Git with SSH access to GitHub:

```bash
git clone --recurse-submodules git@github.com:namestarlit/alx-se.git
cd alx-se
```

If you have already cloned this repository:

```bash
git submodule update --init --recursive
```

The linked repositories may have newer commits than the versions recorded here.
Each project has its own instructions and dependencies; there is no shared build
or test command for the collection.
