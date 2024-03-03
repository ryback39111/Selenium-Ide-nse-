# Objective of this work:  Use of Selenium IDE to record a test automation to download the latest PDF posted on NSE website. The script must download the latest PDF posted when the script is run, and not hardcode the file to download. 


https://github.com/ryback39111/Selenium-Ide-nse-/assets/81157736/a927cb88-39a0-4edc-beb0-3203c6046e7c

Conclusion
As we can see through this video . the test is running 100% fine and downloding the required file without hardcoding the file.
For this I particulalry use - The command **click** with the **target** **css=td[headers="-"]** **a[href*='.pdf']** locates and clicks on a PDF download link within a table cell.  Specifically, it first finds a table cell (<td>) containing the attribute headers="-".  Then within that cell, it finds a link element (<a>) whose href attribute contains the file extension '.pdf'.   Once this link is found, the command simulates a click, triggering the download process. 

For running this through side runner it requires various additional factors that is the pdf download setting in browser should always be Default behaviour > Sites automatically follow this setting when you visit them>Download PDFs for efficient pdf download.

When we use **side runner** we should use selenium web driver to pass additional windows, browser pop ups and download location because selenium ide doesn't comply with these features.

## Command Structure 
<img width="831" alt="Screenshot 2024-03-04 at 1 06 43 AM" src="https://github.com/ryback39111/Selenium-Ide-nse-/assets/81157736/1be56b78-f051-40ce-8433-36e535db7770">

## Log File While Testing 
<img width="1710" alt="Screenshot 2024-03-04 at 1 10 42 AM" src="https://github.com/ryback39111/Selenium-Ide-nse-/assets/81157736/03f242ed-8af8-4462-87bc-e28c094c2d7c">








