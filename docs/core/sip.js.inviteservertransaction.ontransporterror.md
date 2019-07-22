<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [sip.js](./sip.js.md) &gt; [InviteServerTransaction](./sip.js.inviteservertransaction.md) &gt; [onTransportError](./sip.js.inviteservertransaction.ontransporterror.md)

## InviteServerTransaction.onTransportError() method

First, the procedures in \[4\] are followed, which attempt to deliver the response to a backup. If those should all fail, based on the definition of failure in \[4\], the server transaction SHOULD inform the TU that a failure has occurred, and MUST remain in the current state. https://tools.ietf.org/html/rfc6026\#section-8.8

<b>Signature:</b>

```typescript
protected onTransportError(error: Error): void;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  error | <code>Error</code> |  |

<b>Returns:</b>

`void`
