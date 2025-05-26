## COLM

To change the COLM website, first setup your venv. Then: 

```bash
pip install -r requirements.txt
```

To see the website run 

```bash
make run
```

To build the website run

```bash
make freeze
```

To deploy the website, first clone the main repo and then run:

```bash
cp -fr build/ ../colm-org.github.io
```
