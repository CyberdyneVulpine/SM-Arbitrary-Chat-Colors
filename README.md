# [Any] Arbitrary Chat Colors
**Current Version: 1.1.0**



## Description:

Allows players with access to use any html colour code in chat.  

**Examples:**
 -   Input: this is some #ff00ffpink#ffffff text!
 -   Output:  [![](https://forums.alliedmods.net/image-proxy/c071be02845755e048af1f977768df9489678796/687474703a2f2f636f6e74656e742e73637265656e636173742e636f6d2f75736572732f44617274684e696e6a612f666f6c646572732f4a696e672f6d656469612f39326536383131382d333038332d346433652d383430392d3831306666366232316461612f323031322d30362d30345f303531362e706e67)](http://content.screencast.com/users/DarthNinja/folders/Jing/media/92e68118-3083-4d3e-8409-810ff6b21daa/2012-06-04_0516.png)
 -   Input: #ff0000this text is red, #00ff00this text is green, #0000ffthis text is blue!
 -   Output:  [![](https://forums.alliedmods.net/image-proxy/9f7c4f82c22478896c57b2df0cf59d9ebdcaccbe/687474703a2f2f636f6e74656e742e73637265656e636173742e636f6d2f75736572732f44617274684e696e6a612f666f6c646572732f4a696e672f6d656469612f34316530343065612d666336362d346434372d623334372d3364353138366264386161342f323031322d30362d30345f303531352e706e67)](http://content.screencast.com/users/DarthNinja/folders/Jing/media/41e040ea-fc66-4d47-b347-3d5186bd8aa4/2012-06-04_0515.png)

## Cvars:

-   **chatcolours_version**
    -   Plugin Version

## Install Instructions:

1.  [Install  **Simple Chat Processor (Redux)**](http://forums.alliedmods.net/showthread.php?t=198501).
2.  Place  **ColourChat.smx**  into your addons/sourcemod/plugins/ folder.



## Access Control:

Use chat_colour_override with your admin_overrides.cfg to change who can use chat colours.  
Default access level is *everyone*

## Notes:

**This uses custom includes and will NOT compile on the SourceMod forums. Compile it yourself, or use a [pre-compiled .smx release](https://github.com/CyberdyneVulpine/SM-Arbitrary-Chat-Colors/releases).**  

This currently works in all  **Source 2009**  games.  

## Version History:  

-   **V1.0.0**
    -   Initial Release
-   **V1.1.0**
    -   Code optimizations
    -   Fixed a handle leak
    -   Removed the test command
