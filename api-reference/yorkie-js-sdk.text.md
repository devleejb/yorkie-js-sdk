<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [yorkie-js-sdk](./yorkie-js-sdk.md) &gt; [Text](./yorkie-js-sdk.text.md)

## Text class

`Text` is an extended data type for the contents of a text editor.

<b>Signature:</b>

```typescript
declare class Text<A extends Indexable = Indexable> 
```

## Constructors

|  Constructor | Modifiers | Description |
|  --- | --- | --- |
|  [(constructor)(context, text)](./yorkie-js-sdk.text._constructor_.md) |  | Constructs a new instance of the <code>Text</code> class |

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [length](./yorkie-js-sdk.text.length.md) |  | number | <code>length</code> returns size of RGATreeList. |

## Methods

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [checkWeight()](./yorkie-js-sdk.text.checkweight.md) |  | <code>checkWeight</code> returns false when there is an incorrect weight node. for debugging purpose. |
|  [createRange(fromIdx, toIdx)](./yorkie-js-sdk.text.createrange.md) |  | <code>createRange</code> returns pair of RGATreeSplitNodePos of the given integer offsets. |
|  [delete(fromIdx, toIdx)](./yorkie-js-sdk.text.delete.md) |  | <code>delete</code> deletes the text in the given range. |
|  [edit(fromIdx, toIdx, content, attributes)](./yorkie-js-sdk.text.edit.md) |  | <code>edit</code> edits this text with the given content. |
|  [empty()](./yorkie-js-sdk.text.empty.md) |  | <code>empty</code> makes the text empty. |
|  [getID()](./yorkie-js-sdk.text.getid.md) |  | <code>getID</code> returns the ID of this text. |
|  [select(fromIdx, toIdx)](./yorkie-js-sdk.text.select.md) |  | <code>select</code> selects the given range. |
|  [setStyle(fromIdx, toIdx, attributes)](./yorkie-js-sdk.text.setstyle.md) |  | <code>setStyle</code> styles this text with the given attributes. |
|  [toString()](./yorkie-js-sdk.text.tostring.md) |  | <code>toString</code> returns the string representation of this text. |
|  [toTestString()](./yorkie-js-sdk.text.toteststring.md) |  | <code>toTestString</code> returns a String containing the meta data of the node for debugging purpose. |
|  [values()](./yorkie-js-sdk.text.values.md) |  | <code>values</code> returns values of this text. |
