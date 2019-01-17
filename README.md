### jQuery-Tags-Input
---
https://github.com/xoxco/jQuery-Tags-Input

```js
$('#tags').tagsInput();
$('#tags').tagsInput({
  autocomplete_url:'http://myserver.com/api/autocomplete'
});
$('#tags').tagsInput({
  autocomplete_url: 'http://myserver.com/api/autocomplete',
  autocomplete:{selectFirst:true,width:'100px', autoFill:true}
});
$('#tags').addTag('foo');
$('#tags').removeTag('bar');
$('#tags').importTags('foo,bar,baz');
$('#tags').importTags('');
if ($('#tags').tagExist('foo')) { ... }

$(selector).tagsInput({
  'autocomplete_url': url_to_autocomplete_api,
  'autocomplete': { option: value, option: value},
  'height': '100px',
  'width': '300px',
  'interactive': true,
  'defaultText' : 'add a tag'
  'onAddTag' : callback_function,
  'onRemoveTag': callback_function,
  'onChange': callback_function,
  'delimiter': [',',';'],
  'removeWithBackspace': true,
  'minChars': 0,
  'maxChars': 0,
  'placeholderColor': '#666666'
});
```

```
```

```
```

