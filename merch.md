---
author_staff_member: Jarrett - KB0ICT
date: 2021-03-27T05:00:00.000+00:00
title: Merch
categories: []

---
<<div id='collection-component-1621343851577'></div>

<script type="text/javascript">

/*<!\[CDATA\[*/

(function () {

  var scriptURL = '[https://sdks.shopifycdn.com/buy-button/latest/buy-button-storefront.min.js](https://sdks.shopifycdn.com/buy-button/latest/buy-button-storefront.min.js "https://sdks.shopifycdn.com/buy-button/latest/buy-button-storefront.min.js")';

  if (window.ShopifyBuy) {

    if (window.ShopifyBuy.UI) {

      ShopifyBuyInit();

    } else {

      loadScript();

    }

  } else {

    loadScript();

  }

  function loadScript() {

    var script = document.createElement('script');

    script.async = true;

    script.src = scriptURL;

    (document.getElementsByTagName('head')\[0\] || document.getElementsByTagName('body')\[0\]).appendChild(script);

    script.onload = ShopifyBuyInit;

  }

  function ShopifyBuyInit() {

    var client = ShopifyBuy.buildClient({

      domain: 'hamrs-app.myshopify.com',

      storefrontAccessToken: '82bed28184a9a2aac5c6750307a7d1de',

    });

    ShopifyBuy.UI.onReady(client).then(function (ui) {

      ui.createComponent('collection', {

        id: '263538770069',

        node: document.getElementById('collection-component-1621343851577'),

        moneyFormat: '%24%7B%7Bamount%7D%7D',

        options: {

  "product": {

    "styles": {

      "product": {

        "@media (min-width: 601px)": {

          "max-width": "calc(33.33333% - 30px)",

          "margin-left": "30px",

          "margin-bottom": "50px",

          "width": "calc(33.33333% - 30px)"

        }

      },

      "button": {

        ":hover": {

          "background-color": "#4b9ec8"

        },

        "background-color": "#53b0de",

        ":focus": {

          "background-color": "#4b9ec8"

        }

      }

    },

    "text": {

      "button": "Add to cart"

    }

  },

  "productSet": {

    "styles": {

      "products": {

        "@media (min-width: 601px)": {

          "margin-left": "-30px"

        }

      }

    }

  },

  "modalProduct": {

    "contents": {

      "img": false,

      "imgWithCarousel": true,

      "button": false,

      "buttonWithQuantity": true

    },

    "styles": {

      "product": {

        "@media (min-width: 601px)": {

          "max-width": "100%",

          "margin-left": "0px",

          "margin-bottom": "0px"

        }

      },

      "button": {

        ":hover": {

          "background-color": "#4b9ec8"

        },

        "background-color": "#53b0de",

        ":focus": {

          "background-color": "#4b9ec8"

        }

      }

    },

    "text": {

      "button": "Add to cart"

    }

  },

  "option": {},

  "cart": {

    "styles": {

      "button": {

        ":hover": {

          "background-color": "#4b9ec8"

        },

        "background-color": "#53b0de",

        ":focus": {

          "background-color": "#4b9ec8"

        }

      }

    },

    "text": {

      "total": "Subtotal",

      "button": "Checkout"

    }

  },

  "toggle": {

    "styles": {

      "toggle": {

        "background-color": "#53b0de",

        ":hover": {

          "background-color": "#4b9ec8"

        },

        ":focus": {

          "background-color": "#4b9ec8"

        }

      }

    }

  }

},

      });

    });

  }

})();

/*\]\]>*/

</script>