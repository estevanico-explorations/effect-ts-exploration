# Code Snippets

Error handling ([Discord Thread](https://discord.com/channels/795981131316985866/1232414242788081766))

Reading file line-by-line ([Discord Thread](https://discord.com/channels/795981131316985866/1232657662001287199))
```ts
const program = P.Effect.gen(function* (_) {
  const fs = yield* _(P.FS.FileSystem)
  const file = yield* _(
    fs.stream(filePath).pipe(
      P.Stream.decodeText,
      P.Stream.splitLines,
      P.Stream.tap(P.Console.log),
      P.Stream.runDrain,
    )
  )
})
```

Implementing a TCP Server ([Discord Thread](https://discord.com/channels/795981131316985866/1232680019302678568))
