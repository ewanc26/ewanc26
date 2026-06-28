# AT Protocol Architecture & Ecosystem

I build tools that empower users to own their data and move it freely across the decentralized web. My ecosystem centers on the AT Protocol (ATProto).

## Personal Data Sovereignty
I believe in owning your data. AT Protocol lets me host my own PDS (Personal Data Server), control my identity, and take my content anywhere.

### Data Pipelines
My tools act as bridges to the ATProto ecosystem:
- **Audio**: Malachite imports music history from Spotify and Last.fm into the `fm.teal.alpha` lexicon.
- **Social**: Opal migrates microblog history into `app.bsky.feed.post` records.
- **Visual**: Jasper imports Instagram photos and videos to Grain or Spark.
- **Documentation**: Bismuth converts rich documents into portable Markdown.

## Infrastructure
My PDS runs at `eurosky.social`. NixOS configurations for my hosts are managed via the `ewanc26/nix` repository, with starter templates in `ewanc26/nix-starter`.

## Identity
- **DID**: `did:plc:ofrbh253gwicbkc5nktqepol`
- **Handle**: `ewancroft.uk`
- **PDS**: `eurosky.social`
