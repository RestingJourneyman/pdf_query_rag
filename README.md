# PDF Query RAG

## Project Initialization

### Development Workflow

1. **Branch Naming**: Each developer should create their own development branch named `<developer_name>_dev`. For example, if the developer's name is Alice, the branch should be named `alice_dev`.
2. **Commit Changes**: Developers should commit all their changes to their respective development branches.
3. **Code Review**: Each development branch will be reviewed by other developers before merging.
4. **Merge to Test Branch**: After the code review, the development branch will be merged into the `test` branch.
5. **Testing**: The `test` branch will be tested on a dummy deployment area to ensure everything works as expected.
6. **Merge to Main Branch**: If the tests pass, the `test` branch will be merged into the `main` branch.

### Git Initialization

1. **Navigate to Project Directory**: Open Git Bash and navigate to your project directory:
   ```sh
   cd path/to/your/project
   ```
2. **Initialize Git Repository**: Initialize a new Git repository:
   ```sh
   git init
   ```
3. **Create Development Branch**: Create your respective development branch:
   ```sh
   git checkout -b <developer_name>_dev
   ```
   Replace `<developer_name>` with your name.
4. **Add Files**: Add all files to the staging area:
   ```sh
   git add .
   ```
5. **Commit Changes**: Commit the files to the local repository:
   ```sh
   git commit -m "Initial commit"
   ```
6. **Add Remote Repository**: Add the remote repository URL:
   ```sh
   git remote add origin https://github.com/your-username/your-repository.git
   ```
7. **Push Development Branch**: Push your development branch to the remote repository:
   ```sh
   git push -u origin <developer_name>_dev
   ```

### Installing Libraries from requirements.txt

1. **Create Virtual Environment** (Optional but recommended):
   ```sh
   python -m venv myenv
   ```
   Replace `myenv` with your preferred environment name.
2. **Activate Virtual Environment**:
   ```sh
   myenv\Scripts\activate
   ```
3. **Install Libraries**: Install all the libraries listed in the `requirements.txt` file:
   ```sh
   pip install -r requirements.txt
   ```

That's it! You have successfully initialized the project, created your development branch, and installed the necessary libraries. If you have any questions or need further assistance, feel free to ask! 😊