<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@genkit-ai/ai](./ai.md) &gt; [Message](./ai.message.md)

## Message class

Message represents a single role's contribution to a generation. Each message can contain multiple parts (for example text and an image), and each generation can contain multiple messages.

**Signature:**

```typescript
export declare class Message<T = unknown> implements MessageData 
```
**Implements:** MessageData

## Constructors

<table><thead><tr><th>

Constructor


</th><th>

Modifiers


</th><th>

Description


</th></tr></thead>
<tbody><tr><td>

[(constructor)(message)](./ai.message._constructor_.md)


</td><td>


</td><td>

Constructs a new instance of the `Message` class


</td></tr>
</tbody></table>

## Properties

<table><thead><tr><th>

Property


</th><th>

Modifiers


</th><th>

Type


</th><th>

Description


</th></tr></thead>
<tbody><tr><td>

[content](./ai.message.content.md)


</td><td>


</td><td>

Part\[\]


</td><td>


</td></tr>
<tr><td>

[role](./ai.message.role.md)


</td><td>


</td><td>

MessageData\['role'\]


</td><td>


</td></tr>
</tbody></table>

## Methods

<table><thead><tr><th>

Method


</th><th>

Modifiers


</th><th>

Description


</th></tr></thead>
<tbody><tr><td>

[data()](./ai.message.data.md)


</td><td>


</td><td>

Returns the first detected `data` part of a message.


</td></tr>
<tr><td>

[media()](./ai.message.media.md)


</td><td>


</td><td>

Returns the first media part detected in the message. Useful for extracting (for example) an image from a generation expected to create one.


</td></tr>
<tr><td>

[output()](./ai.message.output.md)


</td><td>


</td><td>

If a message contains a `data` part, it is returned. Otherwise, the `output()` method extracts the first valid JSON object or array from the text contained in the message and returns it.


</td></tr>
<tr><td>

[text()](./ai.message.text.md)


</td><td>


</td><td>

Concatenates all `text` parts present in the message with no delimiter.


</td></tr>
<tr><td>

[toJSON()](./ai.message.tojson.md)


</td><td>


</td><td>

Converts the Message to a plain JS object.


</td></tr>
<tr><td>

[toolResponseParts()](./ai.message.toolresponseparts.md)


</td><td>


</td><td>


</td></tr>
</tbody></table>