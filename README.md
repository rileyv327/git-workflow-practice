## PolyHaven

PolyHaven is an opensource 3d asset library. They basically provide a multitude of free textures and assets for 3d development.

[How we handle 80tb and 5m page views a month for under $400](https://blog.polyhaven.com/how-we-handle-80tb-and-5m-page-views-a-month-for-under-400/)

The article is a blog post on their site explaning how they can afford to host such a popular website with huge amounts of downloads while still providing a completely free service.

If found it pretty interesting how they're able to minimize their operating costs. Since the only things that are changing on their site and database are essentially new assets, they're able to cache their data on Cloudfare servers once it's downloaded once and the cached files make up about 85% of all downloads. They can also cache their basic website traffic as well, so about 93% of their traffic ends up being cached, significantly reducing the cost on any backend server they host.

## Comment from You Xu
This article is interest me as well! It is definitely an amazing work to handle such a large amount of data at a low cost.