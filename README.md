A robot that searches emag for different products, scrapes data, writes in an exel and finally sends the exel to a predefined email address.

Way of operation:

1) After running, a pop-up window will open suggesting that you enter the name of the file where you will write the downloaded data. (example name file: "example.xlsx")
2) A new pop-up window opens asking you to enter a file from which to read the input data. The project was tested on 3 input files, which can be found in the Resources folder. (example name file: "TestData1.xlsx")
3) The robot will use google chrome and will open a new page on www.emag.ro.
4) It will search the search bar for each product in the input file.
5) A new pop-up window will open allowing you to enter an option from the "Availability" section on the site.
6) A new pop-up window for the "Relevance" section.
7) The robot will click on the easybox option and then scrape the data which you will write to the output file set above.
8) To send the mail, it will take over the credentials from windows manager.


The most important files / folders:

1) "/Resources" that will contain all the activities described.
2) "/DataTest" that will contain the data corresponding to the input.
3) "config.json"  some general configurations.
