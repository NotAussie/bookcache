> [!NOTE]
> `bookcache` requires `poetry` to be installed. We recommend to install it to your base Python installation for ease of use. 

# 📚 Build Instructions

To build `bookcache` from source run `poetry build`, then a new `dist` folder should be generated. 

# 📦 Publishing Instructions

To publish `bookcache` you'll first need to setup `poetry` to use a PyPI, you can find instructions for it [here](https://python-poetry.org/docs/repositories/#configuring-credentials), if you've setup `poetry` to use PyPI already then simply run `poetry publish --build` (`--build` rebuilds the `dist` to make sure its up to date).