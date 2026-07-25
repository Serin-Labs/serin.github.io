# serin-labs.github.io

This repository is intentionally almost empty.

Serin Labs moved from `serin-labs.github.io` to **<https://serin-labs.com>**. This
repo exists only so GitHub Pages keeps issuing a permanent redirect for the old
address, so that existing links and search results continue to resolve.

The `CNAME` file is the entire mechanism: it tells GitHub's edge to answer every
request to `serin-labs.github.io/<path>` with a `301` to `serin-labs.com/<path>`.
GitHub reports a "DNS record is not properly configured" warning for this repo,
because `serin-labs.com` points at the site's own origin server rather than at
GitHub Pages. That warning is expected. The redirect works regardless, and the
`github.io` host keeps its own certificate.

**Do not delete the `CNAME` file**, and do not make this repository private.
Either would break the redirect and start returning 404s for every inbound link
to the old domain.

The site source now lives in a private repository.

## History

Commits before 2026-07-25 are the full history of the site while it was published
from here. They are left in place deliberately; nothing depends on them.
