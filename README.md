# reachability-with-maven-example
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2FLeonardoDortaBejarano%2Freachability-with-maven-example.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2FLeonardoDortaBejarano%2Freachability-with-maven-example?ref=badge_shield)


This repository includes example project for reachability walkthrough.

- You will need jdk8+ installed (`java` must be in PATH)
- You will need maven installed (`mvn` must be in PATH)

```bash
# Install fossa-cli
; curl -H 'Cache-Control: no-cache' https://raw.githubusercontent.com/fossas/fossa-cli/master/install-latest.sh | bash

# Check fossa-cli version
; fossa --version

# Build project (required)
; mvn package

# Run Analysis
# Docs: https://github.com/fossas/fossa-cli
; fossa analyze --project reachability-with-maven-example --fossa-api-key MY_FOSSA_API_KEY
```

You can also refer to example in our [CI](./.github/workflows/ci.yml).

## License
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2FLeonardoDortaBejarano%2Freachability-with-maven-example.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2FLeonardoDortaBejarano%2Freachability-with-maven-example?ref=badge_large)