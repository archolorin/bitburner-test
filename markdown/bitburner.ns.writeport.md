<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [bitburner](./bitburner.md) &gt; [NS](./bitburner.ns.md) &gt; [writePort](./bitburner.ns.writeport.md)

## NS.writePort() method

Write data to a port.

<b>Signature:</b>

```typescript
writePort(port: number, data: string | number): Promise<PortData>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  port | number |  |
|  data | string \| number |  |

<b>Returns:</b>

Promise&lt;[PortData](./bitburner.portdata.md)<!-- -->&gt;

The data popped off the queue if it was full.

## Remarks

RAM cost: 0 GB

Write data to that netscript port.

