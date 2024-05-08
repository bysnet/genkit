<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [genkitx-chromadb](./genkitx-chromadb.md) &gt; [chroma](./genkitx-chromadb.chroma.md)

## chroma() function

Chroma plugin that provides the Chroma retriever and indexer

**Signature:**

```typescript
export declare function chroma<EmbedderCustomOptions extends z.ZodTypeAny>(params: {
    clientParams?: ChromaClientParams;
    collectionName: string;
    createCollectionIfMissing?: boolean;
    embedder: EmbedderArgument<EmbedderCustomOptions>;
    embedderOptions?: z.infer<EmbedderCustomOptions>;
}[]): PluginProvider;
```

## Parameters

<table><thead><tr><th>

Parameter


</th><th>

Type


</th><th>

Description


</th></tr></thead>
<tbody><tr><td>

params


</td><td>

{ clientParams?: ChromaClientParams; collectionName: string; createCollectionIfMissing?: boolean; embedder: EmbedderArgument&lt;EmbedderCustomOptions&gt;; embedderOptions?: z.infer&lt;EmbedderCustomOptions&gt;; }\[\]


</td><td>


</td></tr>
</tbody></table>
**Returns:**

[PluginProvider](./core.pluginprovider.md)
