<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@genkit-ai/flow](./flow.md) &gt; [StepsFunction](./flow.stepsfunction.md)

## StepsFunction type

**Signature:**

```typescript
export type StepsFunction<I extends z.ZodTypeAny = z.ZodTypeAny, O extends z.ZodTypeAny = z.ZodTypeAny, S extends z.ZodTypeAny = z.ZodTypeAny> = (input: z.infer<I>, streamingCallback: StreamingCallback<z.infer<S>> | undefined) => Promise<z.infer<O>>;
```
**References:** [StreamingCallback](./core.streamingcallback.md)
