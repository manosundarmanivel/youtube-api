# Youtube-API-Link-Notes
Here you will all the API's that can be used to fetch the data from youtube with your API-Key

**For Getting the Home Page Content:**

```
export const YOUTUBE_VIDEO_API =
  "https://youtube.googleapis.com/youtube/v3/videos?part=snippet%2CcontentDetails%2Cstatistics&chart=mostPopular&maxResults=50&regionCode=IN&key=" +
  API_KEY;
```

**For Searching the videos using the query:**
```
export const YOUTUBE_SEARCH_API =
  "https://suggestqueries.google.com/complete/search?client=firefox&ds=yt&q=";
```

**For Getting Live videos :**
```
export const YOUTUBE_LIVE_API =
  "https://youtube.googleapis.com/youtube/v3/search?part=snippet&eventType=live&maxResults=25&q=news&type=video&key=" +
  API_KEY;

```
**For Getting Live Streaming Details:**
```
export const YOUTUBE_LIVE_DETAILS =
  "https://www.googleapis.com/youtube/v3/videos?part=liveStreamingDetails,snippet&key=" +
  API_KEY +
  "&id=";
```

**For Getting Live Comment Details:**
```
export const YOUTUBE_LIVE_COMMENT =
  "https://www.googleapis.com/youtube/v3/liveChat/messages?part=snippet,authorDetails&maxResults=2000&key=" +
  API_KEY +
  "&liveChatId=";
```

**For Getting Related Videos:**
```
export const RELATED_VIDEOD_API =
  " https://youtube.googleapis.com/youtube/v3/search?part=snippet&maxResults=25&regionCode=IN&type=video&key=" +
  API_KEY +
  "&relatedToVideoId=";
```

**For Getting the Video Comments:**
```
export const COMMENT_LIST_API = "https://www.googleapis.com/youtube/v3/commentThreads?key="+API_KEY+"&textFormat=plainText&part=snippet&maxResults=50&videoId="`
```

**For Getting the video by keyword:**
```
export const SEARCH_VIDEO_BY_KEYWORD_API = "https://www.googleapis.com/youtube/v3/search?part=snippet&maxResults=50&type=video&key="+API_KEY+"&q="`
```
