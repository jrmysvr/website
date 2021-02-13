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

---

### Using [Bloom](bloom.sh):

_Adding the widget to the website_

```
<script type="text/javascript">
window.$bloom = { project: '01779b69-e002-d356-e522-b5931e56b9bb' };
(function(){d=document;s=d.createElement("script");s.src="https://bloom.sh/libs/bloom.js"; s.async=1;d.getElementsByTagName("head")[0].appendChild(s);})();
</script>
```
