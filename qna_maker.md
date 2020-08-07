
# QnAmaker query result

[`query_result.py`](https://github.com/microsoft/botbuilder-python/blob/master/libraries/botbuilder-ai/botbuilder/ai/qna/models/query_result.py)

```python
# QueryResult
_attribute_map = {
    "questions": {"key": "questions", "type": "[str]"},
    "answer":    {"key": "answer",    "type": "str"},
    "score":     {"key": "score",     "type": "float"},
    "metadata":  {"key": "metadata",  "type": "[Metadata]"},
    "source":    {"key": "source",    "type": "str"},
    "id":        {"key": "id",        "type": "int"},
    "context":   {"key": "context",   "type": "QnAResponseContext"},
}
```

[`metadata.py`](https://github.com/microsoft/botbuilder-python/blob/master/libraries/botbuilder-ai/botbuilder/ai/qna/models/metadata.py)

```python
# Metadata
_attribute_map = {
    "name":  {"key": "name",  "type": "str"},
    "value": {"key": "value", "type": "str"},
}
```

[`qna_response_context.py`](https://github.com/microsoft/botbuilder-python/blob/master/libraries/botbuilder-ai/botbuilder/ai/qna/models/qna_response_context.py)
[`prompt.py`](https://github.com/microsoft/botbuilder-python/blob/master/libraries/botbuilder-ai/botbuilder/ai/qna/models/prompt.py)

```python
# QnAResponseContext
_attribute_map = {
    "is_context_only": {"key": "isContextOnly", "type": "bool"},
    "prompts":         {"key": "prompts",       "type": "[Prompt]"},
}

# Prompt
_attribute_map = {
    "display_order": {"key": "displayOrder", "type": "int"},
    "qna_id":        {"key": "qnaId",        "type": "int"},
    "qna":           {"key": "qna",          "type": "object"},
    "display_text":  {"key": "displayText",  "type": "str"},
}
```
