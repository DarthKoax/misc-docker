# Build it
docker built . -t yt-dlp-ffmpeg

# Run it
Apply any settings as normal from https://github.com/yt-dlp/yt-dlp
```
docker run -it --rm -v $PWD:/app -w /app yt-dlp-ffmpeg yt-dlp "https://www.youtube.com/watch?v=dQw4w9WgXcQ&pp=ygUXbmV2ZXIgZ29ubmEgZ2l2ZSB5b3UgdXA%3D"
```

