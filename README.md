one-button.org/leanderhutton.com Theme
======================================

Very heavily modifed Monospace theme. Almost to the point of none recognition.

Original theme from: https://github.com/getpelican/pelican-themes/tree/master/monospace

For use with Markdown code highlighting: 

	MARKDOWN = {
	    'extension_configs': {
	        'markdown.extensions.codehilite': {'css_class': 'highlight', 'linenums': 'False'},
	        'markdown.extensions.extra': {},
	        'markdown.extensions.meta': {},
	    },
	     'output_format': 'html5',
	}

Also, you might want to include the `DESCRIPTION` option (it appears in the left sidebar):

    DESCRIPTION = 'My blog and stuff ...'
