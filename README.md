# docker-ijulia

[![License](https://img.shields.io/github/license/uchida/docker-ijulia.svg?maxAge=2592000)](https://tldrlegal.com/license/creative-commons-cc0-1.0-universal)

docker image for [IJulia](https://github.com/JuliaLang/IJulia.jl) notebook, [Jupyter](http://jupyter.org/) interactive environment with [Julia language](http://julialang.org).

Docker image is available as [auchida/ijulia](https://hub.docker.com/r/auchida/ijulia/) in Docker Hub.

## Image tags

- `0.4`, `latest`

## Usage

```console
$ docker run -d -p 8888:8888 -v $PWD:/data auchida/ijulia
```

## License

Contents on this repository are dedicated to [![CC0](http://i.creativecommons.org/p/zero/1.0/80x15.png "CC0")](https://creativecommons.org/publicdomain/zero/1.0/).
No rights reserved.

License for distributed Docker images follows all of [Debian Project](https://www.debian.org/legal/licenses/), [Julia language](https://github.com/JuliaLang/julia/blob/master/LICENSE.md) and [Anaconda End User License Agreement](https://docs.continuum.io/anaconda/eula) and [IJulia](https://github.com/JuliaLang/IJulia.jl/blob/master/LICENSE.md) and its dependencies.
