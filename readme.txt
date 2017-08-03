=== Meet Your Commenters ===
Contributors: Artberri
Donate link: http://www.berriart.com/donate/
Tags: plugin, dashboard, admin, widget, social networks, social graph, google, comments
Requires at least: 2.5
Tested up to: 2.7
Stable tag: 1.1

Displays web pages and social networks' profiles of your commenters in the dashboard.

== Description ==

When someone comments on your blog and writes a comment with his/her URL, is leaving more information than you think. This plugin displays web pages and profiles of those users in the dashboard, so you can add them as friends if you are in the same social network.

This is possible thanks to the Google Social Graph API. The profiles are showed because the commenter claims them as its owner on his web linking them with `rel="me"`. The ones which are with italic font are not reliable and they could not be of the user.

Comments, questions and bug reports are welcome: [http://www.berriart.com/meet-your-commenters/](http://www.berriart.com/meet-your-commenters/ "Meet Your Commenters")

== Installation ==

1. Extract and upload the directory `meet-your-commenters` to the `/wp-content/plugins/` directory
1. Activate plugin
1. That's all

REQUIREMENTS

* 1.1 version runs on Wordpress >= v2.7
* 1.0 version runs on Wordpress >= v2.5 and < v2.7
* `allow_url_fopen` option or cURL enabled 

== Frequently Asked Questions ==

= Why does the plugin contain a file called JSON.php?  =

This is to make it compatible with PHP < 5.2.0, because the previous versions don't recognize the json_decode function.

= I installed it but it doesn't work! =

Have you the requirements? You must have `allow_url_fopen` option or cURL enabled.

== Screenshots ==

[http://www.berriart.com/imagenes/myc-page.png  Preview of the plugin's page]

[http://www.berriart.com/imagenes/myc-widget.png  Preview of the plugin's dashboard widget]

