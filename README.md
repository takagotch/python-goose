### python-goose
---
https://github.com/grangier/python-goose

```py
// tests/extractors/authors.py

from base import TestExtractionBase

class TestArticleAuthor(TestExtractionBase):

  def test_author_schema(self):
    article = self.getArticle()
    fields = ['authors']
    self.runArticleAssertions(article=article, fields=fields)
```

```
```

```
```

