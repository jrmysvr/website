# My website

## Built using [zola](https://www.getzola.org/)
(Hosting with github pages and a google domain - jeremysavor.dev)
References:
* https://medium.com/employbl/launch-a-website-with-a-custom-url-using-github-pages-and-google-domains-3dd8d90cc33b
* https://medium.com/@Tnylnc/tnylnc-how-to-set-up-github-pages-with-google-domains-83bd5a4fbc5c
- https://www.getzola.org/documentation/deployment/github-pages/
- https://github.com/getzola/zola/issues/861#issuecomment-572871260

Github IPs
https://docs.github.com/en/github/working-with-github-pages/managing-a-custom-domain-for-your-github-pages-site#about-custom-domain-configuration

    185.199.108.153
    185.199.109.153
    185.199.110.153
    185.199.111.153

### Setup

> git clone https://github.com/jrmysvr/website

> cd website

> git submodule init
> git submodule update --recursive --remote

_(The current theme is used as a submodule)_

### Run
> zola serve

### CI build with Travis
_See [.travis.yml](.travis.yml)_

