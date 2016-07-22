# youtube_playlist_download

Using jQuery & ES6

[Allow Pop-Up Chrome Settings](https://support.google.com/chrome/answer/95472?hl=en)

To download youtube playlist, goto [Youtube MultiDownloader][a] & paste youtube playlist url

Open `Chrome Developer Tools` & goto `Console` & paste this

```
$('td>div>a').map((index,link) => {
	window.open(link.href,'_blank');
});
```

[a]: http://youtubemultidownloader.com/playlist.html