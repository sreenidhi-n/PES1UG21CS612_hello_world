# Building A CI Pipeline With GitHub Actions

- **CI Pipeline**: Automates building, testing, and deploying software.
- **GitHub Actions**: Tool to automate tasks in your development process.

### **Pre-requisites**
- GitHub account
- Basic Git, GitHub, CMake, C++ knowledge

### **Project Setup**
1. **Initialize Git Repository**:
   - Update `SRN` in `CMakeLists.txt`.
   - Create GitHub repo named `SRN_hello_world`.
   - Push files using Git commands.
   - **Screenshot (a)**: Repo after file upload.

2. **Create GitHub Actions Workflow**:
   - Go to Actions tab -> New workflow -> Set up a workflow yourself.
   - Paste provided workflow code.
   - **Screenshot (b)**: Pasted workflow code.

3. **Monitor Workflow**:
   - Edit `main.cpp`, add “This is `<SRN>`”.
   - **Screenshot (c)**: Build success after changes.
   - **Screenshot (d)**: `main.cpp` after update.
   - **Screenshot (e)**: Status of the build after passing.
