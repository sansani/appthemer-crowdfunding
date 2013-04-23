=== Crowdfunding by AppThemer ===

Author URI: http://appthemer.com
Plugin URI: http://appthemer.com
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_xclick&business=contact@appthemer.com&item_name=Donation+for+Crowdfunding
Contributors: SpencerFinnell, adampickering
Tags: crowdfunding, donations, charity, fundraising, digital downloads, crowd funding, crowdsource 
Requires at least: 3.5
Tested up to: 3.5
Stable Tag: 1.0
License: GPLv3
License URI: http://www.gnu.org/licenses/gpl-3.0.html

A crowdfunding platform in the likes of Kickstarter and Indigogo

== Description ==

Crowdfunding by [AppThemer](http://appthemer.com/fundify.html) is a funding platform for WordPress. An extension that seamlessly integrates with [Easy Digital Downloads](http://wordpress.org/extend/plugins/easy-digital-downloads/), the Crowdfunding plugin lets you crowd source everything from films, games, and music to art, design, and technology.

"Backers" can pledge specified amounts of money towards a project and receive rewards for their contributions. Pledge amounts are only collected if a campaign reaches its goal in the time specified.

Run your own crowdfunding website for anything you can imagine.

Note: The AppThemer Crowdfunding plugin is designed to work alongside the PayPal Adaptive Payments gateway so that pledges are collected but no funds are taken until the campaign reaches its goal. The plugin will also work along side any other gateway that Easy Digital Downloads supports but funds will be taken immediately.

= Features =

Features of the plugin include:

* Crowd fund anything you want!
* Frontend form submission to easily collect campaign information.
* Compatible with PayPal Adaptive Payments API for pre-approved purchases. When a person commits to funding your project they are only charged if your campaign reaches its pre-defined goal.
* Compatible with all standard payment gateways that Easy Digital Downloads supports, i.e Stripe, PayPal Pro/Express (payments will be charged immediately).
* Works both as a donation plugin and a Crowdfunding plugin.
* Easy to theme and integrate into your own site which uses Easy Digital Downloads.

= Premium Themes =

The first compatible theme that has been released is called "Fundify" from [AppThemer](http://appthemer.com/fundify.html).

= Get Involved =

Developers can contribute to the source code of the project on [GitHub](https://github.com/appthemer/crowdfunding)

== Installation ==

1. Install the Easy Digital Downloads plugin and activate it, if you haven't already.
2. Install the AppThemer Crowdfunding plugin and activate it.
3. (Optional) Install the PayPal Adaptive Payments plugin. (https://easydigitaldownloads.com/extension/paypal-adaptive-payments?ref=7)
4. Create a new page for your frontend submission form add this shortcode to the page: [appthemer_crowdfunding_submit] - (this is optional).
5. Go to Campaigns > Add New to create a new campaign.

== Frequently Asked Questions ==

= Does this plugin work with any theme? =

Yes. However, it won't look much different than a standard EDD install. Templates must be modified/created to output relevant crowdfunding information (display amount funded, etc).

== Changelog ==

= 1.0: April 22, 2013 =

https://github.com/AppThemer/crowdfunding/issues?milestone=5&state=closed

* New: Ability to require authentication (registration/login) before submitting a campaign.
* New: Login and Register shortcodes can be placed on any page.
* Fix: Don't show collect funds button once they have already been collected.
* Fix: Limit cart to one pledge per checkout to avoid errors.
* Fix: Show all qualified campaigns on Export CSV section.
* Fix: Don't limit the number of backers to 20 (in terms of count, output, etc).
* Fix: Extra hooks in profile shortcode for better themeability.
* Fix: Update language of "Fixed vs Flexible" to "All-or-nothing vs Flexible" as well as better descriptors.
* Fix: Add Terms & Conditions to submission shortcode if they exist on EDD.
* Fix: Use display name on profile instead of nicename to avoid breaking author archive permalinks.
* Fix: Logged in users can now upload media when adding a campaign via the frontend.

= 0.9: April 8, 2013 =

https://github.com/AppThemer/crowdfunding/issues?milestone=4&state=closed

* New: Set a limit on number of times a pledge amount can be purchased.
* New: Separate area for adding updates to a campaign during it's running.
* New: Site administrators can choose which funding types are available.
* New: Shipping becomes optional. Can toggle when submitting via frontend/backend.
* New: More social fields in profile on campaign page, and author page.
* New: Can set minimum and maximum campaign length in settings.
* Fix: Properly set category when using the frontend submission form.

= 0.8.1: April 1, 2013 =

* Fix: Only show the users campaigns using profile shortcode.

= 0.8: March 31, 2013 =

* New: [appthemer_crowdfunding_profile] Shortcode to allow users to edit their profile, and see their campaigns.
* New: Users can submit multiple campaigns without creating multiple accounts.
* New: Export campaign data of completed campaigns.
* New: Request payout of campaign.

= 0.7: March 26, 2013 =

* New: Funding types -- Fixed (default) or flexible funding. Allow a higher commission to be set on flexible funding.
* New: Settings to specify the page that contains the frontend submission shortcode, as well as an FAQ page.
* Fix: Some more backward compatibility stuff for DateTime functionality on hosts running PHP < 5.3

= 0.6: March 18, 2013 =

* Fix: When adding rewards via frontend, make sure blank fields are added in the correct spot.
* Fix: Always show backer rewards in ascending price order, no matter how they are entered.
* Fix: Don't use getTimestamp() method on DateTime (not supported in 5.2) -- format() instead.
* New: Added french translation to plugin.
* New: Create a user account on campaign submission. This allows campaign authors to edit their campaigns
* New: jQuery validate frontend submission before server validation.
* New: Collect a contact email separate from PayPal for contacting the campaign author

= 0.5: March 14, 2013 =

* Fix: Don't kill the frontend form submission when there are no errors.
* Fix: Save campaign author/organization on frontend form submission.
* Fix: Properly save preview image and/or video on frontend form submission.

= 0.4: March 12, 2013 =

* Release with Fundify theme.

= 0.3-alpha: March 11, 2013 =

* Fix: Better theme support. Check for some EDD templates, as well as standard WordPress files.
* Fix: Actually collect funds!
* Fix: Better errors when submitting a campaign, or collecting funds.
* New: If PayPal Adaptive Payments is not active, track normal payments.
* New: Themes without explicit support will output default EDD variable pricing.

= 0.2-alpha: March 7, 2013 =

* Fix: Better loading of exports.
* Fix: Shipping fixes, backers, etc.
* Fix: Load backers at the correct time.
* Fix: Count amount based on preapproval, not total earnings.
* New: Dont activate if EDD is not active.
* New: Text filters.
* New: Update readme.txt

= 0.1-alpha: March 6, 2013 =

* First official alpha release!