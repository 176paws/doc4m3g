# Intro

M<sup>3</sup>G offers some of its functionalities through an application programming interface (API). In particular, a [RESTful HTTP API](https://en.wikipedia.org/wiki/Representational_state_transfer) that allows you to interact with M<sup>3</sup>G purely as data that can be uploaded, accessed, searched for, etc. via [HTTP requests](https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol).

HTTP basically allows you to GET, POST, PUT, DELETE etc. resources on a remote server. These resources are identified via URLs (=uniform resource locator). URLs usually consists of a protocol (e.g. HTTP), a domain (our servers), a path (a place on our servers), and query parameters (additional options).

At present, M<sup>3</sup>G provides 5 main "groups" of operations:

 - [Network](https://gnss-metadata.eu/__test/site/api-docs#/Network)
 - [License](https://gnss-metadata.eu/__test/site/api-docs#/License)
 - [Metadata](https://gnss-metadata.eu/__test/site/api-docs#/Metadata), [Product](https://gnss-metadata.eu/__test/site/api-docs#/Product) and [Update](https://gnss-metadata.eu/__test/site/api-docs#/Update) (i.e. for getting info, export or update some sections of station site logs in M<sup>3</sup>G, respectively)

Within most of these resource "groups", you find endpoints that either allow you to retrieve info on a given M<sup>3</sup>G entry (i.e. a network, a station) or to ask a query to locate many M<sup>3</sup>G entries at the same time (see the [M<sup>3</sup>G swagger dashboard](https://gnss-metadata.eu/__test/site/api-docs)).

One can start to test M<sup>3</sup>G API thanks to different tools and libraries. For example, one could use:

- an HTTP program like [*curl*](https://curl.haxx.se/) to directly use M<sup>3</sup>G API from within a shell
- [*requests*](https://requests.readthedocs.io/en/master/), a generic Python HTTP library
- the browser, via the [M<sup>3</sup>G swagger dashboard](https://gnss-metadata.eu/__test/site/api-docs) describing some of M<sup>3</sup>G function calls, based on an [OpenAPI spec](https://swagger.io/specification/)

Here you can find some examples for common M<sup>3</sup>G tasks using the various options.

<a href="https://twitter.com/intent/tweet?button_hashtag=LoveTwitter&ref_src=twsrc%5Etfw" class="twitter-hashtag-button" data-dnt="true" data-show-count="false">Tweet #M3G_GNSS</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
