# domain-expiry
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fjrtapsell%2Fdomain-expiry.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Fjrtapsell%2Fdomain-expiry?ref=badge_shield)


# Features
- Allows checking the expiry date of a domain

# Usage
    const domain = require("domain-expiry");
    index.getExpiry("jrtapsell.co.uk")
        .then(p => console.log("jrtapsell.co.uk expires on: " + p);

# Supported TLDs

This list is not exhaustive, if TLDs are not supported feel free to open an issue on GitHub.

- .uk
- .com
- .org
- .tech
- .net

# Issues

Feel free to raise any issues on the linked Github repository.

## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fjrtapsell%2Fdomain-expiry.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Fjrtapsell%2Fdomain-expiry?ref=badge_large)