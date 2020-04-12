# LumiaWOATestSite

This repository contains the base files required to compile the LumiaWOA webpages.

This site and the LumiaWOA project is not affilated with Microsoft.

## Build instructions
1. Have a copy the [Hugo](https://gohugo.io/) static site generator installed.
2. Clone this repository.
3. Navigate to the root and run `hugo server`.

Refer to the [Hugo Documentation](https://gohugo.io/documentation/) for additional command line options and the general Hugo syntax.

Remember to adjust `baseURL` in `config.yaml` to the domain that will be hosting the website before you deploy live.

## Additional resources
* [Microsoft Fluent UI](https://developer.microsoft.com/en-us/fluentui#/) — General design guidance and resources.
* [lazysizes](https://github.com/aFarkas/lazysizes) — For lazyloading images in browsers that don't support native lazyload.
