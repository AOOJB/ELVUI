# ELVUI Mod

Includes: <br>

Math.lua mod:<br>
Changed the formatted text so that every tag that results with a "-" between numbers is replaced with a " | ".<br>
Added PERCENT_CURRENT textformatting style. which means every tag that uses "current-percent" can be written "percent-current" to change them around. <br>
Changed minimum max value for number to also show %. Changed to 200, everything below 200 wont show % also. Specifically changed so powers wont show % also when majority is capped at 100-150 except mana. <br>

Tags.lua mods:<br>
current health with absorbs tag(current health + absorbs in the same number). Text format: [health:current-with-absorbs] <br>
current health and percentage with absorbs tag. Text format: [health:current-percent-with-absorbs] <br>
same tag as above except reversed numbers. Text format: [health:percent-current-with-absorbs] <br>
current health deficit with absorbs tag(Shows ur current health + absorbs relative to ur max hp). Text format: [health:currentdeficit-with-absorbs] <br>

Pull both files. <br>
Go to "AddOns\ElvUI\Core\General" and replace remove the current files and replace. <br>
Or just copy paste the entire code from here to each file. <br>
