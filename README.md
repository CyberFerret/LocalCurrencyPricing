# Example localised currency pricing page

This is a sample project showing how we can use simple jQuery plus the [ipdata.co](https://ipdata.co) service to create a SaaS pricing page which shows the user your pricing in local currency when they load the page.

This is so you can build a pricing page similar to the one we have at [HR Partner](https://www.hrpartner.io/pricing.html)

## Live Example

Here is the link to this repo's hosted page, which will show you a live working example:

[https://cyberferret.github.io/LocalCurrencyPricing/](https://cyberferret.github.io/LocalCurrencyPricing/)

* Note: The auto loading of currencies may not work if the page has been loaded more than 1500 times in a day, as that is the ipdata API rate limit!

## Getting an IPData API key

I strongly recommend that you [sign up](https://ipdata.co) for an IPData.co API key.  It is FREE.  If you use my test key within this code, please be aware that it will stop working once we hit the limit of 1500 queries in a day, which is very likely to happen while everyone is testing it out.  Please fork this project, get your own ipdata key and replace the one in the code with it.


## How does it work?

I wrote a whole [blog post](http://devan.blaze.com.au/blog/2018/8/1/building-a-pricing-screen-which-reflects-local-currency) on getting this to work, which explains most of the code.  Feel free to check out the post.



