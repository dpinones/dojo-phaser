# Phaser

To start the client application:

```bash
cd client
```

Install dependencies:

```bash
yarn
```

Rename `.env.example` to `.env`

Run the development server:

```bash
yarn dev
```

## Dojo (v0.6.0)

To build the Dojo starter:

```bash
cd dojo-starter
```

Build the project:

```bash
sozo build
```

In another terminal, disable fees:

```bash
katana --disable-fee
```

Migrate:

```bash
sozo migrate
```

To start Torii:

```bash
torii --world 0x446f1f19ba951b59935df72974f8ba6060e5fbb411ca21d3e3e3812e3eb8df8
```
