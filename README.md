# dailymail-tcs
Extract Title, Content and Summary (tcs) for the DailyMail dataset and output to a folder.

You will need the download directory where the HTML file of DailyMail is.
You will need the directory to the stories from DailyMail where the content and summary is available.

This tool will help extract the title, content and summary and output it to another directory with the same filename as in the stories or downloads directories.

# Install:
sudo pip install dailymail_tcs

# Usage:
from dailymail_tcs import tcs

tcs.extract([dailymail_download_directory],[dailymail_stories_directory],[output_directory])

# Example:
tcs.extract("/data/corpus/dailymail/dailymail/downloads/","/data/corpus/dailymail/dailymail/stories/","./dm_test/")
