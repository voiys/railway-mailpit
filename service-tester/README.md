# service-tester

First install dependencies:

```bash
bun install
```

To run a smoke test agains the insecure service copy over the `.insecure.env.example` and replace with your own values.

```bash
cp .insecure.env.example .env
```

Then run the following command:

```bash
bun test:insecure
```

To run a smoke test agains the secure service copy over the `.secure.env.example` and replace with your own values.

```bash
cp .secure.env.example .env
```

Then run the following command:

```bash
bun test:secure
```
