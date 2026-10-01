# czechify-skill

An agent skill that adds proper Czech diacritics to text written without them,
without changing sentence structure or tone. It also points out likely typos.

```
> /czfy Ahoj, potrebuju si to jeste promyslet, ozvu se zitra.

Ahoj, potřebuju si to ještě promyslet, ozvu se zítra.
```

## Install

### Agent Skills

```bash
npx skills add dvdkouril/czechify-skill

# or upgrade an existing install
npx skills upgrade dvdkouril/czechify-skill
```

### Claude Code (plugin)

Add the marketplace and install the plugin:

```
/plugin marketplace add dvdkouril/czechify-skill
/plugin install czechify@czechify-skill
```

## Usage

Ask your agent to "czechify" or "czfy" a piece of text, or invoke `/czfy`
directly.

## License

MIT
