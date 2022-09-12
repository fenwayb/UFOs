<h1 Align="Center">
  
  UFOs

  # Overview
  
  <p>For this project we were tasked with using Javascript and HTML/CSS to make a webpage that would interactively display UFO data</p>
  
  ## Results
<p>The webpage successfully displays said UFO data and the table updates based on multiple filters. An example search is shown below</p>

![Screenshot 2022-09-12 170638](https://user-images.githubusercontent.com/106105597/189758694-7448d272-631e-4a90-b7fc-c672210d4be6.png)

<p> to use the webpage you simply input your desired filters and it will automatically update as you type in new filters. To remove a filter simply delete the text you entered for that filter </p>

  ## Summary
<p> One drawback of this design is the fact that everything has to be exact. The most glaring example of this is the date field. As the dataset is written with January to October in single digits (1/xx/xxxx instead of 01/xx/xxxx) if the user writes the date a different way or if they use a different date format (such as month/day/year) they won't get the information they're really searching for. </p>

<p> Additional code would need to be added to more intelligently read the users input for this sort of flexibility. Another feature that could be added would the ability to partial search the comments field, as that field has some of the most useful information in it.</p>
