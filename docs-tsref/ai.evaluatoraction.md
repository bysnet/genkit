<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@genkit-ai/ai](./ai.md) &gt; [EvaluatorAction](./ai.evaluatoraction.md)

## EvaluatorAction type

**Signature:**

```typescript
export type EvaluatorAction<DataPoint extends typeof BaseDataPointSchema = typeof BaseDataPointSchema, CustomOptions extends z.ZodTypeAny = z.ZodTypeAny> = Action<typeof EvalRequestSchema, typeof EvalResponsesSchema> & {
    __dataPointType?: DataPoint;
    __configSchema?: CustomOptions;
};
```
**References:** [Action](./core.action.md)
