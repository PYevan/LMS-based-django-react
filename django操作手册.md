在Windows操作系统上，如果你使用`py -m venv`创建了一个虚拟环境，可以通过以下指令来激活它：

1. 打开命令提示符（Command Prompt）或PowerShell。

2. 导航到包含虚拟环境的目录。例如，如果你的虚拟环境名为`venv_django`并位于当前目录下，你可以使用以下命令：
   ```sh
   cd C:\Users\user\Desktop\Lessons\Django React LMS\backend
   ```

3. 激活虚拟环境：
   ```sh
   venv_django\Scripts\activate
   ```

激活后，你的命令提示符会显示虚拟环境的名称，例如：
```
(venv_django) C:\Users\user\Desktop\Lessons\Django React LMS\backend>
```

以下是具体步骤和指令：

1. 打开命令提示符或PowerShell。

2. 导航到虚拟环境所在目录：
   ```sh
   cd C:\Users\user\Desktop\Lessons\Django React LMS\backend
   ```

3. 激活虚拟环境：
   ```sh
   venv_django\Scripts\activate
   ```

激活后，你可以运行Django管理命令，例如创建应用：

1. 创建 `core` 应用：
   ```sh
   python manage.py startapp core
   ```

2. 创建 `userauths` 应用：
   ```sh
   python manage.py startapp userauths
   ```

3. 创建 `api` 应用：
   ```sh
   python manage.py startapp api
   ```

完成后，如果需要退出虚拟环境，可以使用以下命令：
```sh
deactivate
```