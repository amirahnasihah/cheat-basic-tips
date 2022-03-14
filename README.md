# Cheat Sheets or Keyboard Shortcuts found

All goes to the original owner.

# Problems

Anaconda pip install mpyc Error pip-script.py is not present

>I want o to install mpyc package using anaconda command prompt CMD. but it returns this error, How to address to solve such an issue.
>Error 'D:\Ananconda3\Scripts\pip-script.py' is not present.
>(base) C:\Users\dell>pip install mpyc
>Script file 'D:\Ananconda3\Scripts\pip-script.py' is not present.

pip is broken in your Anaconda Version.
Try,with `(base)` active as you have now.

```
conda install --force-reinstall pip
# Or
python -m ensurepip --default-pip
```
