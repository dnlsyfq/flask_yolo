
1. Not pyenv
2. pip install -r requirements.txt
3. pip install pip-run --user
4. mklink python36.exe C:\Users\Dan\AppData\Local\Programs\Python\Python36
5. ssh
    ```
    import sys
    import subprocess

    # implement pip as a subprocess:
    subprocess.check_call([sys.executable, '-m', 'pip', 'install','<packagename>'])
    ```
6. YOLOv5-Flask    