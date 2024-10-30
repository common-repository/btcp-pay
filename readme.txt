=== BTCP Pay === 
Contributors: mattpass
Tags: bitcoin, cryptocurrency, widget
Stable Tag: trunk
Requires PHP: 5.0
Tested up to: 3.4.0
Requires at least: 3.0.1
License: GPLv2
License URI: http://www.opensource.org/licenses/GPL-2.0

Enables users of your WordPress site to hit a button to make a Bitcoin Private payment to you.

== Description ==

Allows users to make Bitcoin Private payments when using your WordPress site.

Install then activate the plugin and it'll take you to the settings page, asking you to copy your widget code from your account on the btcppay.com site into the textarea shown.

After pasting in your widget code and hitting submit, you can then use the widget in a couple of ways:

Usage within areas you control from Admin, eg post pages, can use WordPress's 'Shortcodes':
- Fixed value use: [btcp_pay_widget]
- Attribute value use: [btcp_pay_widget amount="987.654"]

Usage within code, eg templates, can use the PHP function:
- Fixed value use: btcp_pay_widget();
- Function argument value use: btcp_pay_widget(987.654);

= Guides and support =

You can find further information regarding this plugin at https://docs.btcppay.com/integrations/wordpress and get support via your account on btcppay.com also.

= Feedback =

We welcome feedback regarding the plugin use as well as ideas to improve and enhance.

= Git Development =

The GitHub repo at https://github.com/BTCPrivate/btcp-widget contains widget and plugin code. As an open source solution, we welcome dev help via pull requests.