# Type alias: GenerateStreamOptions\<O, CustomOptions\>

```ts
type GenerateStreamOptions<O, CustomOptions>: Omit<GenerateOptions<O, CustomOptions>, "streamingCallback">;
```

## Type parameters

| Type parameter | Value |
| :------ | :------ |
| `O` *extends* `z.ZodTypeAny` | `z.ZodTypeAny` |
| `CustomOptions` *extends* `z.ZodTypeAny` | *typeof* `GenerationCommonConfigSchema` |

## Source

[ai/src/generate.ts:677](https://github.com/firebase/genkit/blob/2b0be364306d92a8e7d13efc2da4fb04c1d21e29/js/ai/src/generate.ts#L677)