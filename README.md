# Project_on_Search_for_Good_Indian_Food
Understanding how Yelp analysis can improvise in the Search for Good Indian Food, because food HAS to be Good!

-2 potential ways for providing secondary ratings to make it easier for
Yelp users to select between many different restaurants of the same cuisine – a rating that gives
more weight to reviewers who have reviewed other restaurants of the same cuisine, and an
“Immigrant Rating” of those with Yelp user names that suggest they might have ethnic expertise
with that cuisine.
-Both methods seemed to have enough users in the Yelp database to provide meaningful rankings
(at least 10% and as many as 27% of reviewers in the 10 most popular cuisines have reviewed
other restaurants of that cuisine, roughly 10% of the reviewers of Indian food have names that
would qualify for the “Immigrant Rating”).
-Both methods showed they could be useful for selecting between many different restaurants of a
cuisine (both successfully identified 1 candidate from at least 6 identically rated restaurants in
Tempe, Arizona).
-The 2 methods yield different results with some overlap in some cities. In general, the
“Immigrant Rating” had more of an impact and tended to be more negative. The range of the
“Weighted Rating” was -1.14 to 0.77 stars with a mean/median of around 0. The range of the
“Immigrant Rating” was -1.92 to 0.31 stars with a mean/median of around -0.4.
-Comparing the 2 methods with all of the cities in the Yelp database, the “Immigrant Rating”
provided more direct information (in 8 cities where there was a choice, it honed in on one
recommendation all 8 times, versus this happening 55% of the time with the “Weighted Rating”).
However, there is a tradeoff of a loss of inclusivity (there were 3 cities that didn’t have enough 4-
star restaurants to qualify for the “Immigrant Rating”). The “Immigrant Rating” was
recommended as the best way to “cut throught the clutter.”
-If the “Immigrant Rating” is used in Yelp in the form of a badge that a restaurant gets if it has an
immigrant rating of 4 or higher, information is lost in 3 cities (we no longer have a clear top
choice). This loss of information can be countered by tweaking the rating so that it accepts a
rating of 3.5 in cities with no “Immigrant Ratings” of 4. Based on this, we recommend exploring
using the “Immigrant Rating” in the form of an “authenticity badge” using that tweak.
