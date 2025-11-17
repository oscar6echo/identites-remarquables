# Build PDF

```sh
# install
sudo apt install pandoc

# replace html by latex for images

# <img src="./img/identite-1.jpeg" alt="Première identité" width="250">
# <img src="./img/identite-2.jpeg" alt="Seconde identité" width="250">
# <img src="./img/identite-3.jpeg" alt="Troisième identité" width="250">

# ![Première identité](./img/identite-1.jpeg){width=250px}
# ![Seconde identité](./img/identite-2.jpeg){width=250px}
# ![Troisième identité](./img/identite-3.jpeg){width=250px}

# build pdf
pandoc README.md -o README.pdf
```
