# PostgreSQL Installation Guide for Windows

## Introduction

PostgreSQL is a powerful, open-source object-relational database system. It has a strong reputation for reliability, feature robustness, and performance. This guide provides step-by-step instructions for installing PostgreSQL on your Windows system.

## Installation

### Windows

1. **Download the Installer:**
   - Visit the official PostgreSQL [download page](https://www.enterprisedb.com/downloads/postgres-postgresql-downloads).
   - Download the installer for the latest version(16.3) of PostgreSQL .

2. **Run the Installer:**
   - Double-click the downloaded `.exe` file to run the installer.
   - Follow the installation wizard. You can choose the default options or customize the installation as needed.

3. **Set Up Environment Variables (Optional):**
   - Add PostgreSQL bin directory to your PATH environment variable. This step is optional but can simplify command-line usage.
   - Open Control Panel → System and Security → System → Advanced system settings → Environment Variables.
   - Edit the `Path` variable and add the path to the PostgreSQL `bin` directory (e.g., `C:\Program Files\PostgreSQL\<version>\bin`).

## Post-Installation Setup

1. **Accessing PostgreSQL:**
   - Use the `psql` command-line tool to access PostgreSQL:
     ```sh
     psql -U postgres
     ```

2. **Creating a Database:**
   - Create a new database with:
     ```sh
     createdb redscope
     ```
3. **Run the sql queries ( provided in the redscope-server )**

