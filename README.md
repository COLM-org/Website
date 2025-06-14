## COLM

> [!warning]
> The content of this repository was moved to `colm-org/colm-org.github.io`, which has been updated to deploy to GH pages from GH actions instead of being built from branch. For more details, see commit [ec196b9ecdd4388d034812ca6b2239fd66c21aa4](https://github.com/COLM-org/colm-org.github.io/commit/f8ba9bce8e1871dda2cccffd194adff2f4e02a73). Thus, this page is archived and is maintained for reference.

To change the COLM website, first setup your venv. Then: 

```bash
pip install -r requirements.txt
```

To see the website run 

```bash
make run
```

To build and update the website run:

```bash
# make freeze will build the website into the build/ directory
make freeze

# To deploy the website, first clone the main repo and then copy:
cp -fr build/ ../colm-org.github.io

# Then commit and push the changes to the main repo
cd ../colm-org.github.io
git add .
git commit -m "Update website"
git push
```
