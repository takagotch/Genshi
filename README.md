### genshi
---
https://github.com/edgewall/genshi

https://genshi.edgewall.org/

```py
// genshi/tests/core.py

class StreamTestCase(unittest.TestCase):
  
  def test_render_utf8(self):
    xml = XML('<li>xxx xxx</li>')
    self.assertEqual(u'<li></li>'.encode('utf-8'), xml.render(encodeing='utf-8'))
  
  def test_render_unicode(self):
  
  

```

```
```

```
```


