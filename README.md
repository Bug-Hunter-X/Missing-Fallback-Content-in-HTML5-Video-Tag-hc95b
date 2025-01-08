# Missing Fallback Content in HTML5 Video Tag

This repository demonstrates a common yet easily overlooked error in HTML5 video embedding: the absence of fallback content when the primary video source fails to load.  The bug and solution illustrate the importance of providing alternative content for browsers that don't support the specified video format or when the video file is inaccessible.

## Bug Description
The provided `bug.html` file includes an `<video>` tag referencing an MP4 video.  However, it lacks a fallback mechanism. If the browser doesn't support MP4, the video player shows nothing.

## Solution
The `solution.html` file rectifies this by adding fallback content and multiple sources (WebM and Ogg). This ensures that the video player provides appropriate feedback or an alternative regardless of browser capabilities or network problems. 

## How to Run
1. Clone the repository.
2. Open `bug.html` and `solution.html` in your web browser.  Observe the differences in handling video playback.