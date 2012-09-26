# HTML-AutoCloseTag

This is a fork of a script mirrored at http://www.vim.org/scripts/script.php?script_id=2591

This script automatically closes HTML tags when you finish typing the opening
tag with ">". It does not auto-close tags in comments or self-closing tags.

So, `<body id="foo">`, upon typing ">", will become `<body id="foo">|</body>`, where
`|` is the cursor. But, if you type `<img src="bar.png">`, the script knows to
keep it the same.

