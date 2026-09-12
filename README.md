# Holy Downloader

A GitHub Actions workflow to download files, medias, and feeds directly into your repository.

Fork the repository, go to **Actions** -> **Download From URL**, paste your URL(s), and run the workflow.

## Currently Offering

* **Downloads:** `aria2`
* **Media extractors:** `yt-dlp` - Used For Youtube, `spotdl` - Used for Spotify, `gallery-dl` - Used for General Media Exctraction [see supported sites](https://github.com/mikf/gallery-dl/blob/master/docs/supportedsites.md)
* **Feed support:** RSS and Atom feeds

## Secrets

Configure these in **Settings** > **Secrets and variables** > **Actions** if you're going to use extractors:

| Secret | Purpose |
| :--- | :--- |
| `YOUTUBE_COOKIES` | Authenticated YouTube downloads |
| `YOUTUBE_PO_TOKEN` | YouTube PO tokens |
| `SPOTIFY_CLIENT_ID` | Spotify client ID |
| `SPOTIFY_CLIENT_SECRET` | Spotify client secret |
