# Username OSINT

## Why investigate usernames?

Usernames are often reused across multiple sites. Investigating a username helps link a target’s accounts and footprint.

## Tools

- [Sherlock](https://github.com/sherlock-project/sherlock) — Searches 300+ social networks.
- [Maigret](https://github.com/soxoj/maigret) — Alternative tool with even more sites.
- [Namechk](https://namechk.com/) — Web tool for quick username checks.

## How to confirm the real target?

- Look for consistent profile pictures or linked emails.
- Check posting style and language.
- Use advanced OSINT to find linked profiles (e.g., email leaks).
- Cross-reference details from multiple platforms.

## Example Sherlock command:

```bash
python3 -m sherlock username
