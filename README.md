Reply for Annotator Plugin
==================
##Reply Annotator Plugin

reply-annotator.js is a plugin for Annotator. This project was created to give a reply to the annotations

The reply plugin allow you to reply text annotations and video annotations with Open Video Annotator.

##Installation

To use the tool you need to install the [Annotator plugin](https://github.com/okfn/annotator/) to annotate text. But if you want to annotate video you will need the [Open Video Annotation plugin](https://github.com/CtrHellenicStudies/OpenVideoAnnotation).

In addition add reply-annotator.min.js and reply-annotator.min.css CDN distributed file to your head tag, just after
videojs:

```html
	<head>
		<!-- Annotator -->
		<script src="http://ajax.googleapis.com/ajax/libs/jquery/1.7/jquery.min.js"></script>
		<script src="http://assets.annotateit.org/annotator/v1.2.7/annotator-full.min.js"></script>
		<link rel="stylesheet" href="http://assets.annotateit.org/annotator/v1.2.7/annotator.min.css">

		<!--Reply Pluging-->
		<script src="build/reply-annotator.min.js"></script>
		<link href="build/reply-annotator.min.css" rel="stylesheet">
	
	</head>
```

