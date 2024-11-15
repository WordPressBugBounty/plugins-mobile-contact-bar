=== Mobile Contact Bar ===
Contributors: anna.bansaghi
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=YXJAZ7Q5EJFUA
Tags: social media, icon, cta button, call to action, woocommerce cart
Requires at least: 4.6
Tested up to: 6.7
Requires PHP: 5.3
Stable tag: 3.0.5
License: GPLv2
License URI: https://www.gnu.org/licenses/gpl-2.0.en.html

Allow your visitors to contact you via mobile phones, or access your site's pages instantly.



== Description ==

Mobile Contact Bar is a compact and highly customizable plugin, which allows your visitors to contact you directly via mobile phones, or access your site's pages instantly.

The settings page is available under the *Settings &rarr; Mobile Contact Bar* menu in the WordPress dashboard.



= Features =

* Icons for social media, call-to-actions, or any links to web pages
* Simple and intuitive styling with the aid of the Real-time Model
* Built-in icon picker with [Font Awesome 6](https://fontawesome.com/) integration
* Customizable URLs using query string parameters
* No data collection from your website's visitors
* Super easy to use, no coding required!



= Special Actions =

* Scroll to Top of the page
* WooCommerce Cart with Item Counter



= Supported Protocols =

* `http`
* `https`
* `mailto`
* `skype`
* `sms`
* `tel`
* `viber`



= Tested with =

* Twenty Twenty-Four
* Twenty Twenty-Three
* Twenty Twenty-Two
* Twenty Twenty-One
* Twenty Twenty
* Twenty Nineteen
* Twenty Seventeen
* Twenty Sixteen
* Twenty Fifteen
* Twenty Fourteen
* Twenty Thirteen
* Twenty Twelve
* Twenty Eleven
* Twenty Ten



== Installation ==

= First time Mobile Contact Bar user =

Thank you for choosing Mobile Contact Bar! In order to create your bar, simply activate the plugin and visit the plugin's page by clicking on *MCB Contact Bar* in your left navigation menu.
Once the plugin page loads, open the *Bar* box, choose the *Display on Devices* option, select the device type to enable the bar and then press the *Save Changes* button at the top of the page.
Mobile Contact Bar will automatically create a default bar with a couple of buttons for you.

= Adding buttons to your bar =

To add more buttons to your bar, open the *Button List* box, find a particular list item, select the checkbox, customize the icon and fill in the URI field.
In order to add more buttons, click on the *New Button* or on one of the icons at the top of the list.


= Positioning and styling your bar =

To set options for bar (positions, colors, borders, width, height, space, placeholder, etc.), open the *Bar* box and check the changes on the *Real-time Model*.
Open the *Icons*, *Badges*, or *Toggle* box and set options for icons, badges, or toggle, respectively.


== Frequently Asked Questions ==

= JavaScript disabled =
The plugin works fine without JavaScript on the front-end of your site.
We use JavaScript on the front-end in two cases:
1. if the toggle is activated, then the plugin has an option for saving the toggle state in a cookie, and
2. *Scroll to Top*, *Back in History*, and *Forward in History* actions use inline JavaScript for their functionality.

= Cookies =
You have full control over the single cookie which is called *mobile_contact_bar_toggle*.

= Cleaning the cache =
If your site is cached via a caching plugin such as WP Fastest Cache or Cache Enabler, then it is important to clean those caches after the Contact Bar has been enabled.
Also, if you disable the Contact Bar then the caches need to be cleaned again.

= Custom colors for each button =
Currently there is no built-in support in the plugin itself for adding different colors. But it is possible to add custom CSS to your site via Theme Customization, as described in this thread: [different-color-for-each-button](https://wordpress.org/support/topic/different-color-for-each-button-3/)



== Screenshots ==

1. Button List meta box
2. Icons, Toggle meta boxes
3. Bar meta box
4. Settings &rarr; Mobile Contact Bar



== Changelog ==

= 3.0.5 =
* [Fix] Security fix with `esc_attr`

= 3.0.4 =
* [Fix] Security fix with `sanitize_text_field`

= 3.0.3 =
* [Fix] Update FA version number

= 3.0.2 =
* [Fix] Location Dot icon name changes in FA 6

= 3.0.1 =
* [Fix] Scroll Top and Shopping Cart icon name changes in FA 6 [scroll-top-broke](https://wordpress.org/support/topic/mobile-add-scroll-top-broke-after-last-update-v3-0-0/)

= 3.0.0 =
* [Upgrade] Font Awesome 6.5.1 [font-awesome-6](https://wordpress.org/support/topic/font-awesome-6-2/)

= 2.1.0 =
* [Add] Add viber protocol [viber-chat](https://wordpress.org/support/topic/problem-whit-link/), [how-to-add-viber-button](https://wordpress.org/support/topic/how-to-add-viber-button/)
* [Fix] Let the + sign be optional in tel and sms protocols [telephone-remove](https://wordpress.org/support/topic/telephone-remove/)
* [Fix] Decode / encode query string [e-mail-body](https://wordpress.org/support/topic/e-mail-body/)
* [Update] Font Awesome 5.15.4

= 2.0.9 =
* [Fix] Missing contact field "checked" notice

= 2.0.8 =
* [Fix] Add `rel="noopener"` for links opening in new tab [links-to-cross-origin-destinations-are-unsafe](https://wordpress.org/support/topic/links-to-cross-origin-destinations-are-unsafe-7/)

= 2.0.7 =
* [Fix] Do not show meta boxes on foreign pages [menu-bar-settings-appearing-for-ohter-users-than-admin](https://wordpress.org/support/topic/menu-bar-settings-appearing-for-ohter-users-than-admin/)

= 2.0.6 =
* [Fix] Domain Path

= 2.0.5 =
* [Fix] License version
* [Fix] Requires at least has been changed to 4.6

= 2.0.4 =
* [Fix] Add padding zero to toggle

= 2.0.3 =
* [Fix] Add margin and padding to list items
* [Update] Font Awesome 5.13.0

= 2.0.2 =
* [Fix] Forgotten log message in source [your-update-just-broke-my-site](https://wordpress.org/support/topic/your-update-just-broke-my-site-2/)

= 2.0.1 =
* [Fix] Extracted cookie into an option Toggle:Cookie
* [Fix] Restored Bar:Opacity option [a-few-more-minor-things-in-2-0](https://wordpress.org/support/topic/a-few-more-minor-things-in-2-0/)
* [Update] Font Awesome 5.0.13

= 2.0.0 =
* [Upgrade] Reimplement plugin with new options in the database
* [Upgrade] Font Awesome 5.0.12 [can-add-support-fontawesome-v5-0-8](https://wordpress.org/support/topic/can-add-support-fontawesome-v5-0-8/)
* [Rename] `mcb_front_render_html` to `mcb_public_render_html`
* [Deprecate] `mcb_admin_update_contacts` and `mcb_admin_update_settings` filters
* [Add] UI for managing contacts and details (add, delete, modify) [a-couple-of-more-feature-suggestions](https://wordpress.org/support/topic/a-couple-of-more-feature-suggestions/)
* [Add] Option for setting label on the toggle [a-couple-of-more-feature-suggestions](https://wordpress.org/support/topic/a-couple-of-more-feature-suggestions/)
* [Add] Option for adding space above/below the bar [contact-bar-overlaying-footer-credits-on-site](https://wordpress.org/support/topic/contact-bar-overlaying-footer-credits-on-site/), [position](https://wordpress.org/support/topic/position-20/), [hidding-menu](https://wordpress.org/support/topic/hidding-menu/)
* [Add] Storing toggle state in a cookie [toggle-state](https://wordpress.org/support/topic/toggle-state/), [toggle-issue](https://wordpress.org/support/topic/toggle-issue/)
* [Add] WhatsApp [a-couple-of-feature-ideas](https://wordpress.org/support/topic/a-couple-of-feature-ideas/), [whatsapp-chat](https://wordpress.org/support/topic/whatsapp-chat/)
* [Add] WooCommerce Cart with Item Counter action [a-couple-of-feature-ideas](https://wordpress.org/support/topic/a-couple-of-feature-ideas/)

= 1.4.1 =
* [Fix] Bar width and bar alignment issues

= 1.4.0 =
* [Add] Option for setting bar width [bar-width-2](https://wordpress.org/support/topic/bar-width/)
* [Add] Icon for Instagram [no-instagram-icon](https://wordpress.org/support/topic/no-instagram-icon/)
* [Fix] Plugin upgrade on network

= 1.3.1 =
* [Test] Tested up to WordPress 4.9

= 1.3.0 =
* [Add] Icon for texting (sms) [text-with-pre-filled-option](https://wordpress.org/support/topic/text-with-pre-filled-option/)

= 1.2.3 =
* [Fix] array_filter() issue

= 1.2.2 =
* [Fix] array_filter() issue

= 1.2.1 =
* [Fix] Empty arrays issues

= 1.2.0 =
* [Add] UI for sorting contacts
* [Add] Option for setting subject, body, cc, bcc of email [add-subject-and-body-to-email](https://wordpress.org/support/topic/add-subject-and-body-to-email/)
* [Add] Refreshed option page UI using meta boxes
* [Fix] Prepared plugin for localization
* [Fix] Sanitized phone number and add a plus sign (+) prefix
* [Update] Font Awesome 4.7.0

= 1.1.2 =
* [Fix] Left aligned icons in the CSS [does-your-plugin-support-the-hemingway-theme](https://wordpress.org/support/topic/does-your-plugin-support-the-hemingway-theme/)
* [Update] Font Awesome 4.6.3

= 1.1.1 =
* [Fix] Admin styles
* [Fix] Public styles
* [Update] Font Awesome 4.6.1

= 1.1.0 =
* [Add] Option for Bar:Opening links in a new tab [no-instagram-icon](https://wordpress.org/support/topic/no-instagram-icon/)

= 1.0.1 =
* [Fix] Improved setting and contact validation (sanitization)
* [Fix] Set the default value of the fixed bar position to true
* [Fix] Removed obsolated workarounds

= 1.0.0 =
* [Upgrade] Official release

= 0.1.1 =
* [Fix] Default option issue during network activation

= 0.1.0 =
* [Add] Initial release



== Upgrade Notice ==

= 3.0.0 =
* Supported Font Awesome version is 6. Please, update your icons accordingly.

= 2.0.0 =
* Structure of the plugin's option has been changed, supported Font Awesome version is 5.

= 1.0.0 =
* Official release.
