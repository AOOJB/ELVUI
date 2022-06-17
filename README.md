# ELVUI Mod

Includes: <br>

Math.lua mod:<br>
Changed the formatted text so that every tag that results with a "-" between numbers is replaced with a " | ".<br>
Changed so small numbers wont also show % when its irrelevant. Like most classes power which caps at 150, where knowing % is not needed. Only applies to the modded tags. <br>
Modded Formats in Math.lua: <br>
divider-current <br>
current-percent2 <br>
divider-current-percent <br>
divider-current-percent2 <br>
divider-percent-current <br>
<br>
current and percent is interchangable on most tags.<br>

Modded tags in Tags.lua:<br>
[health:current-percent-with-absorbs] <br>
[health:percent-current-with-absorbs] <br>
[health:currentdeficit-with-absorbs] <br>
[classpower:divider-current-percent2:shortvalue] <br>

Download both files. <br>
Go to "AddOns\ElvUI\Core\General" and remove "Math.lua" and "Tags.lua" and replace with the files you downloaded. <br>
Or just copy paste the entire code from here to each file. <br>

29/04/22 <br>
Change to Math.lua. <br>
Made it possible to do "-divider" or "divider-" to make a | between tags. Example would be [health][divider-power] would show "healh | power" so adding "-divider" or "divider-" adds a | after or before the tag. <br>

14/06/22 <br>
Change to Math.lua <br>
Added "current-percent2" format to Math.lua which shows "current (percent%)" instead of "current | percent%".

15/06/22 <br>
Change to Math.lua and Tags.lua <br>
Changed Math.lua to not return some numbers as 0 and it wont return capped numbers between 200 and 50000. <br>
Added a tag to tags.lua that adds a divider based on if theres a number before or not. <br>

16/06/22 <br>
Changed Math.lua to return health even if capped. <br>
Changed Tags.lua added health = true to some health tags. <br>

17/06/22 <br>
Changed Math.lua, changed how shortvalue works so it returns one decimal.<br>