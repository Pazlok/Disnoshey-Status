[Disnoshey](https://scp-fanon.fandom.com/wiki/User:Disnoshey) is a Fandom bot for the [SCP Fanon Wiki](https://scp-fanon.fandom.com), created by me, Pazlok. The code will ***not*** be open-sourced for the forseeable future because:
1. I don't want people stealing the code.
2. The code itself should be pretty easy to recreate, anyways.

# Capabilites
- Single delete
- Batch delete
- Batch protect
- Batch unprotect
- Single undelete
- Batch undelete
- Add delete template
- Batch rollback
- List ≤500 pages in a category

# Other Possible Inclusions
- Identify and remove dead/broken links
- Auto-delete pages
- Page categorization (unlikely)
- Auto-add delete template on condition
- Add certain templates on certain pages
- Identify and remove broken redirects (unlikely)

# Scrapped Ideas
- **Single protect**: Felt redundant
- **Auto add deletion template on AI-generated pages**: Can't do this without paying.
- **Batch move**: Too complicated setup.
- **Batch add delete templates** I can really only find maybe two scenarios when this is used.
- **Generate list of pages with <1000 bytes**: There's already a feature for this, making it redundant.

# Todo
- [ ] Add help module
- [ ] Add cosmetic changes
- [ ] Add logging

# Note on Rate Limits
Like any good API, Fandom's (or rather, MediaWiki's) API has rate limits. I just thought it would be good to mention it. I should also note that these will only be the "important" ones.
**Move:** 20 hits every 60 seconds
**Purge:** 30 hits every 60 seconds
**Rollback:** 10 times every 60 seconds
