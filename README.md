execute `SimpleApp.py`
```powershell
python SimpleApp.py
```

aaa
bbbbb
a
a
c
b

bb
bb

**example**
```powershell
python D:\app\spark-3.1.2-bin-hadoop2.7\examples\src\main\python\pi.py
```

**memo**
* 以下のようなエラーが出たら
  * `Missing Python executable 'python3'`
  * `Python was not found but can be installed from the Microsoft Store`
  PySparkはデフォルトでは、`python3`というコマンドを叩こうとする。
  自分の環境では、`python`コマンドでpython3.8を呼び出しているので、
  システム環境変数で、`PYSPARK_PYTHON`:`python`としてあげることで、
  PySpark内部で`python`コマンドを叩いてくれるようになる。
