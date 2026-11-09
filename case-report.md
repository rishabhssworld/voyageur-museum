# Case Report: The Voyageur Compass

## Culprit

Walt Henderson took the Voyageur Compass.

## Evidence

1. The staff notes show that alarm code 4471 belonged to W. Henderson and that he received an after-hours key in September.
   Location: commit 72f5d74, staff-notes.txt.

2. Code 4471 disarmed the alarm at 00:15, and the loading dock opened at 00:19 without a badge swipe.
   Location: commit 629628b, security-log.txt.

3. A matching compass appeared for auction under the seller “WH Antiquities”.
   Location: legacy/old-index.html, lines 11–12.

## Means, motive and opportunity

Means: His after-hours key could have allowed him to open the loading dock without a badge swipe, and his alarm code allowed him to disarm the alarm, as it doesn't directly shows that a key has been used.
Motive: The auction listing under “WH Antiquities” suggests that Henderson stole the compass to sell it for money.
Opportunity: Henderson had asked for Display Case 7 to be moved beside the loading dock, putting the compass close to an exit he could access after hours. Evidence: legacy/old-style.css, lines 11–12.

## Other suspects

Priya Nandakumar is cleared because the security log shows she left the building at 23:52, before the alarm was disarmed at 00:15, and she had no alarm code on file.
Evidence: commit 629628b, security-log.txt, and the suspects table in case-file.html

Marcel Brisebois is cleared because his delivery was supervised and the loading dock was locked at 18:45 after the delivery. Also, he didn't have any alarm code.
Evidence: commit 629628b, security-log.txt

Gaston Lavoie is cleared in this case because CCTV showed him at the front desk at 22:30, and his alarm code was 2210, while the code used to disarm the alarm was 4471.
Evidence: commit 629628b, security-log.txt, and commit 72f5d74, staff-notes.txt.
