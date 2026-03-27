# xspfgen

Convert proprietary playlist formats to [XSPF](https://www.xspf.org/).

**Supported formats:** `.plist` `.m3u` `.m3u8` `.pls` `.yaml` → `.xspf`

### What is XSPF?

> XSPF (pronounced "spiff") is the XML format for sharing playlists.
>
> - It is portable. You should be able to carry a playlist from one place to another.
> - It is well-engineered. Most playlist formats have bugs that make life harder for programmers and users.
> - It is free (as in liberty) and open. No proprietary lock-in.
>
> — [xspf.org](https://xspf.org/)

### Why?

Music streaming services export playlists in proprietary formats which
hinders playlist sharing across platforms.

`xspfgen` lets you convert any playlist
format to an open standard (XSPF) for cataloging and sharing playlists
in any context. You can:

- Host it on your website just like RSS.
- Version control your playlists with `git`. It's just XML.
- Import into a SQL database to analyze your music library.
- Submit your playlists to MusicBrainz.
- Parse your playlists with any programming language.
- Migrate between music services without losing your library.
- Upload it to cloud storage as a portable backup.
