# Semantic Search Engine Optimization for your xt:Commerce shop #

![http://bachelor.siegerth.com/xt_semantic_turning.png](http://bachelor.siegerth.com/xt_semantic_turning.png)

This free extension module for **xt:Commerce** automatically adds rich data-markup to your shop pages **so that search engines like Google, Yahoo, and Bing can display richer item previews in the search results ("Rich Snippets")** with information about
  * prices,
  * availability,
  * delivery options,
  * images, etc.

This typically **increases Click-Through-Rates (CTR) by up to 30%.** At the same time, **your shop will be more accessible** for
  * browser extensions and
  * mobile applications.

For more information about GoodRelations and Semantic SEO, see http://purl.org/goodrelations/

# Installation #
Simply download the extension and **extract it in your plugins folder** of your xt:Commerce installation.
Then, install it using the xt:Commerce Plugin Module. You will have to provide a few additional parameters in a simple dialog - and that's it! **You will be all set for the next generation of Search Engine Optimization :-)**

**Note:** After installing the module, **it can take between 2 - 8 weeks until Google will show rich snippets** for your pages, depending on the general ranking of your site. See also [here if Google is not showing Rich Snippets for your site](http://wiki.goodrelations-vocabulary.org/FFAQ#Why_is_Google_not_showing_rich_snippets_for_my_pages.3F).

**Important:** Please submit the URI of your sitemap (e.g. http://www.la-mousson.de/sitemap.xml) to the GoodRelations Notification Service at http://gr-notify.appspot.com. This will help search engines to find and update your products more easily.

# Support #
If you have questions regarding this extension, **please post to the GoodRelations mailing list** (subscription required):

  * http://ebusiness-unibw.org/cgi-bin/mailman/listinfo/goodrelations

# How does it work? #

The extension module takes the product information from the existing xtCommerce database and passes it to the HTML templates. Then, it inserts the rich RDFa data markup into the HTML page just before sending it to the client.

A few parameters are not provided by the default xtCommerce database. For those, the module includes a simple backend configuration menu, in which you set the additional parameters.

# Why is this module free? #
The work on this module has been carried out by Kevin Siegerth as part of his Bachelor Thesis and been supervised by Uwe Stoll and Prof. Martin Hepp at the Universität der Bundeswehr München.

# Acknowledgments #
The work on this extension module has been supported by the [German Federal Ministry of Research (BMBF)](http://www.bmbf.de/en/) by a grant under the KMU Innovativ program as part of the [Intelligent Match project](http://www.intelligent-match.de/) (FKZ 01IS10022B).

![http://www.productontology.org/static/bmbf.png](http://www.productontology.org/static/bmbf.png)
