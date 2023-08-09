<div style="text-align: center;">
 <h1>Flask APP Demo</h1>
</div>

---


![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)  ![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white) ![SonarLint](https://img.shields.io/badge/SonarLint-CB2029?style=for-the-badge&logo=sonarlint&logoColor=white)
![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)  ![VScode](https://img.shields.io/badge/Visual_Studio_Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white) ![Intellij](https://img.shields.io/badge/IntelliJ_IDEA-000000.svg?style=for-the-badge&logo=intellij-idea&logoColor=white) ![Notepad++](https://img.shields.io/badge/Notepad++-90E59A.svg?style=for-the-badge&logo=notepad%2B%2B&logoColor=black)
---
1. Install packages
```bash
pip install -r requirements.txt
```
2. Run for concurrency
```bash
gunicorn --workers 3 --bind 0.0.0.0:5000 wsgi:app
```

3. Test API to generate Pascal triangle

```bash
curl --location --request POST 'http://localhost:5000/pascal?n=7'
```

### Contact Me

![Developer](/img/developer_shape.png)

**Email :** [Developer](mailto:prince@developer.co.zw)

**WhatsApp/Mobile :** [+263717983773](tel:+263717983773)
