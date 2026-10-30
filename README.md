# Python 自动化测试实验

使用 GitHub Actions 在 push 和 pull_request 时运行 pytest。

```bash
python -m pip install -r requirements.txt
python -m pytest -v
```

calculator.py 提供 add 和 multiply。test_calculator.py 含 2 个测试函数、4 条断言。
