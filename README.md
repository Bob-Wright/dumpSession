# dumpSession
The dumpSession.php program and its companion scripts are a set of simple utiLEETies to manipulate PHP Sessions and Cookies.  Besides hopefully providing some use as generic PHP Session utilites, the codebase is designed to provide some tutorial or self explanatory benefits regarding the subject of simple PHP Sessions.

There are four basic programs.

The first program, makeOneSession.php, does exactly that. It Joins or creates ONE specified PHP Session in the site domain.
The second program, delOneSession.php, deletes ONE specified Cookie/Session or if none is specified and only one exists, deletes that one.
The third program, delAllSessions.php, deletes ALL of the Cookies and Sessions data for the host domain.
The fourth program, dumpSession.php, displays various data about present Cookies and Sessions along with some other select information. If only one Cookie/Session exists dumpSession will join that Session, and if more than one Cookie/Session exists you may specify a Session to join. There are a number of options with this program which can be chosen by query strings. Use <b>dumpSession.php?help</b> to list the options.

The programs (except delAllSessions.php) use query strings to select or set parameters. All of the code is PHP and it echoes some HTML/CSS for page formatting. I wrote these scripts to gain understanding and to assist me in debugging/examining web code that employs Sessions.

Notice if you play with this code in Chrome, Chrome browser has a "feature" to allow you to "Resume where you left off" or reload the previously opened pages. This feature defeats the ordinary "death to Session cookies" when the browser is closed and makes them persist and reappear when the browser reopens.

C&C always welcome.
