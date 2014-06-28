<!--dox @defgroup NimbusKitCurrencies Currencies -->
<div id="github" feature="Currencies"></div>
![](https://github.com/NimbusKit/currencies/raw/master/docs/gfx/currencies_banner.gif "")

Currencies provides tools for the accurate exchange, bill splitting, and displaying of money in any currency.

Where is the Source?
====================

This library is part of NimbusKit+, a collection of specialized, well-documented libraries that complement the NimbusKit ecosystem of libraries. All of the NimbusKit+ libraries are available for purchase in binary form at [Featherless Software Design](https://www.etsy.com/shop/thefeatherless) on Etsy. For source access, please contact Jeff Verkoeyen for more information.

Full documentation is available at [v2.nimbuskit.info](http://v2.nimbuskit.info/NimbusKitCurrencies.html).

Adding it to your Project
=========================

Drag Currencies.framework into your Xcode project. Ensure that the framework is added to your app target.

You can now import the Currencies header and start using its features.

```objc
#import <Currencies/Currencies.h>
```

Requirements
------------

Must be compiled with the iOS 6 SDK or above.

Version History
===============

1.0.0 TBD
-----

Initial release. Includes:

- CURCurrencyGroup: for complex multi-currency calculations.
- CURExchangeRateTable: an NSCoding-compliant table of exchange rates.
- CURExpenseAccountant: a powerful yet concise class for accurately working with expenses made in multiple currencies by any number of actors, with specific weighting on a per-actor basis.

Credits
=======

Currencies was built by [Jeff Verkoeyen](http://jeffverkoeyen.com/) ([featherless](http://twitter.com/)).

License
=======

Currencies is licensed under the [NimbusKit+ Commercial Development license](http://nimbuskit.com/pluslicense).
