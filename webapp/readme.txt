AUTHORS: Kiri Salij and Rachel Miller

DATA: Information about the passengers aboard the titanic

Data obtained from Kaggle https://www.kaggle.com/c/titanic/data?select=train.csv

STATUS:
FEATURES CURRENTLY WORKING:
- Clicking on various homepage buttons returns the count of those people
- The search page searches passengers by name (also can be sorted by name, age, class, and id)
- Raw data can be sorted by name, age, class, and passenger id
- /help/ in the api works
- Buttons stay highlighted when selected
- Some pie charts displaying data are included on the charts page

NOTES: We decided to just not implement the prices page or the api endpoint that
would obtain the data for the prices graphs. We wanted to focus on making the
features we currently had more polished rather than taking on another large
feature. Another Note: We noticed in our own testing and from the code review
that it would be nice if the order of clicking the all/deceased/survived buttons
and the classes/sex/ages buttons didn't matter, that is you could click 1st
class and then deceased and it would work rather than needing to click deceased
before 1st class. However, while trying to implement this, we ran into a ton of 
problems with the get method returning promises instead of results when called. 
While we spent a lot of time trying to work around this, using global variables and
focusing on what was in what method, eventually we saw that implementing 
this proved more effort than it seemed to be worth. So, we acknowledge that we know
about this issue but we decided to focus our time on other aspects of the project.
