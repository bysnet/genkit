<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@genkit-ai/ai](./ai.md) &gt; [generate](./ai.generate.md)

## generate() function

Generate calls a generative model based on the provided prompt and configuration. If `history` is provided, the generation will include a conversation history in its request. If `tools` are provided, the generate method will automatically resolve tool calls returned from the model unless `returnToolRequests` is set to `true`<!-- -->.

See `GenerateOptions` for detailed information about available options.

**Signature:**

```typescript
export declare function generate<O extends z.ZodTypeAny = z.ZodTypeAny, CustomOptions extends z.ZodTypeAny = typeof GenerationCommonConfigSchema>(options: GenerateOptions<O, CustomOptions> | PromiseLike<GenerateOptions<O, CustomOptions>>): Promise<GenerateResponse<z.infer<O>>>;
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

options


</td><td>

[GenerateOptions](./ai.generateoptions.md)<!-- -->&lt;O, CustomOptions&gt; \| PromiseLike&lt;[GenerateOptions](./ai.generateoptions.md)<!-- -->&lt;O, CustomOptions&gt;&gt;


</td><td>

The options for this generation request.


</td></tr>
</tbody></table>
**Returns:**

Promise&lt;[GenerateResponse](./ai.generateresponse.md)<!-- -->&lt;z.infer&lt;O&gt;&gt;&gt;

The generated response based on the provided parameters.
