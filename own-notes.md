# to build own 
```
# prereqs
pip3 install build

apt install python3.10-venv
```

```
# build 
python3 -m build
```

```
# instal
filename=$(cd dist/; ls *.whl)
pip3 install dist/$filename
```

