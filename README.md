# awaitinput

Async/await function to read input from the user.

Usage:

```typescript
import input from "awaitinput"

const main = async () => {
	const input = await input("What is your name? ")
	console.log(`Hello, ${input}!`)
}

main().catch(console.error)
```
