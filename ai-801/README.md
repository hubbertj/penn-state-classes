# AI 801: Foundations of Artificial Intelligence

This directory contains homework assignments, programming projects, and research notes for the AI 801 course at Penn State. 

## 🛠 Tech Stack
- **IDE:** VS Code with Jupyter Extension
- **Environment:** Docker (`jupyter/scipy-notebook`)
- **Primary Language:** Python 3
- **Textbook:** *Artificial Intelligence: A Modern Approach (4th Edition)* by Russell & Norvig

## 📂 Directory Structure
- `/notebooks`: Jupyter notebooks for Part II of weekly assignments.
- `/assignments`: Theoretical responses (Part I) and final PDF submissions.
- `/resources`: Course syllabus, schedule, and textbook reading summaries.

## 🚀 Environment Setup
To ensure a consistent development environment and avoid local dependency issues, all code is run within a Docker container.

### Start the Environment
```bash
docker run -d -p 8888:8888 \
  -v $(pwd)/notebooks:/home/jovyan/work \
  jupyter/scipy-notebook