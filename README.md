## COLM

To change the COLM website, first setup your venv. Then: 

> pip install -r requirements.txt

You may also need to install the following packages for linting:

```bash
# mac:
brew install node
```
To see the website run 

> make run

To build the website run

> make freeze

To deploy the website, first clone the main repo and then run:

> cp -fr build/ ../colm-org.github.io
