# feincms-articles changelog

## v1.1.1

* Move ArticleAdmin into bases.py
* Fix use of ARTICLE_MODELADMIN_CLASS setting

## v1.1

* Update category extension registration method to FeinCMS 1.9.3 standard.
* Create BaseArticle abstract model to allow subclassing.

## v1.0

* Migrate extensions to inherit from ``feincms.extensions.Extension``. Support
 for ``register(cls, admin_cls)``-style functions is removed in FeinCMS v1.9.

## v0.4

* Fix extension fields broken in admin since last release.
* Added fixes for python 3.3 (Py3.3 doesn't work yet because feincms 1.8 is not yet out.)

## v0.3

*Note: NOT compatible with feincms < 1.7.*

* Added ContentModelMixin to Article to integrate with feincms 1.7.
