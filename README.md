# Python

![Banner](./banner.svg)

## Using docker

Create a file like `HellowWorld.py` and run

```bash
docker run -it --rm --name my-running-script -v $(pwd):/usr/src/myapp -w /usr/src/myapp python:3 python HellowWorld.py
```

Note: *replace `$(pwd)` with `%CD%` if you're working under DOS.*

Some Python samples scripts: [https://linuxhint.com/python_scripts_beginners_guide/#post-67157-02](https://linuxhint.com/python_scripts_beginners_guide/#post-67157-02)
