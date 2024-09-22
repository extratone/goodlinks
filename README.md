Documentation/configurables for Ngoc Luu's [**GoodLinks for iOS/iPadOS/macOS**](https://apps.apple.com/us/app/goodlinks/id1474335294).

## Actions

### Custom Content Template

This placeholder can be substituted for the content variable in any given URL scheme:

`{# }[title]%0A{*}[author]{*}%0A{`}[url]{`}%0A%0A{---}%0A%0A[content-markdown]%0A%0A{---}%0A%0A{```}html%0A[content-html]%0A{```}`

Which will pass the following (decoded) content:

```md
# [title]
*[author]*
`[url]`

---

[content-markdown]

---

```html
[content-html]
````
```



`things:///add?title=[title]&notes={- }{[}[title]{]}{(}[url]{)}{ }{ | }{*}[summary]{*}&tags=[tags]&list-id=9CNZTeHPfd445JtNCjpyf&heading=GoodLinks`