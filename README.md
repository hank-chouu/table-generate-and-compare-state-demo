# 安裝步驟

1. [安裝 python](https://www.codingspace.school/blog/2021-04-07)

2. 在 windows powershell 輸入 

```
git clone https://github.com/hank-chouu/table-generate-and-compare-state-demo.git
cd table-generate-and-compare-state-demo
pip install virtualenv
virtualenv venv
.\venv\Scripts\activate.ps1
pip install -r requirements.txt
```

3. vscode 打開這個資料夾，打開 table_create.ipynb （可能會需要先安裝 vscode jupyter extensions）

4. 點選上方 Run All，會跳出 select python kernel，點選 Python Enviroment 後點選 venv

![select python kernel](https://i.imgur.com/4VfHKW9.png)

![choose venv](https://i.imgur.com/e06R8w0.png)

5. compare_state.ipynb 的執行方式，重複步驟 3~4 即可


