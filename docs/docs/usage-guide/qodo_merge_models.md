
The default model used by Qodo Merge (March 2025) is Claude Sonnet 3.7.

### Selecting a Specific Model

Users can configure Qodo Merge to use a specific model by editing the [configuration](https://qodo-merge-docs.qodo.ai/usage-guide/configuration_options/) file.
The models supported by Qodo Merge are:

- `claude-3-7-sonnet` (default)
- `o3-mini`
- `gpt-4o`
- `deepseek/r1`

To restrict Qodo Merge to using only `o3-mini`, add this setting:
```
[config]
model="o3-mini"
```

To restrict Qodo Merge to using only `GPT-4o`, add this setting:
```
[config]
model="gpt-4o"
```

To restrict Qodo Merge to using only `deepseek-r1` us-hosted, add this setting:
```
[config]
model="deepseek/r1"
```


