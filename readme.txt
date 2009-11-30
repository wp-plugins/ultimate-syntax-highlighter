=== The Ultimate Syntax Highlighter ===
Contributors: peterryan, samarudge
Tags: code, syntax, highlighter, javascript, blog, html
Requires at least:2.0.0
Tested up to: 2.2.2
Stable tag: 1.5.1

This plugin makes using the Google Syntax highlighter by Alex Gorbatchev to highlight code snippets within WordPress simple. It has been improved by Sam Rudge to allow the addition of the short tag [hlight lang="language"][/hlight]

== Description ==

This plugin easily integrates the [Google Syntax Highlighter](http://code.google.com/p/syntaxhighlighter) by [Alex Gorbatchev](http://code.google.com/u/alex.gorbatchev) into WordPress.

= Feature summary =

* 100% client side, no server dependency
* Multiple languages support
* Wide browser support
* Very lightweight
* Easily added with the shortcode [hlight lang="language"][/hlight]

= Languages Supported =

* C++  (cpp, c, c++)
* C#  (c#, c-sharp, csharp)
* CSS (css)
* Delphi (delphi, pascal)
* Java (java)
* Java Script (js, jscript, javascript)
* PHP (php)
* Python (py, python)
* Ruby (rb, ruby, rails, ror)
* Sql (sql)
* VB (vb, vb.net)
* XML/HTML (xml, html, xhtml, xslt)

== Installation ==

1. Extract plugin into /wp-content/plugins directory.
2. Activate the plugin.
3. Specify your code snippets in your blog post using the shortcode [hlight lang="Language"][/hlight]

Here is an example to produce ruby syntax highlighting once the plugin is activated: 

	[hlight lang="ruby"]
	def my_ruby_snippet
	  blog_post.should(be_highlighted)
	end
	[/hlight]

== Screenshots ==

1. Simple Ruby Example