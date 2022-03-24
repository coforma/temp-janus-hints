# Using Scratch Pad and Face Brief

Welcome to Janus, the new retirement services application to help you adjudicate retirement claims. 

In this topic, we’ll look at two modes or ways to view data. 

* The first is _Scratch pad_, which takes a temporary approach to case data so you can run different scenarios.
* The second is _Face brief_, which allows you to directly alter the data that Janus sends to the mainframe.

In covering each we’ll talk about—

* When to use scratch pad or face brief
* Accessing the data
* Modifying the data
* Returning to case data

## Scratch Pad

### When to Use Scratch Pad

Depending on the details of the case, you might want to model how different values might change a benefit calculation. Sometimes that scenario includes answering customer questions when the claim is assigned to another specialist. Other times it might be that you want to just try out different approaches to an annuity computation, perhaps based on any information received after a claim is active or is submitted to review. 

Keep in mind that you can use scratch pad almost at any time in Janus.

### Accessing Scratch Pad Data

When you are ready to access scratch pad data, follow these steps:

1. From the _Action Bar_, select **Additional case actions**.
2. From the list of actions that appears, select **Edit scratch pad data**. 

Janus changes the way section headers look, so that you know you are viewing scratch pad data. Janus adds an icon in each section header of _SP_. 

![](https://janustraining.blob.core.windows.net/images/lesson7-SPheader.png)

As you scroll through the case, just like in the case data view, Janus keeps the section header fixed to the top of the view until you scroll down far enough to replace that section header. And each section header has the SP icon in it. 

### Modifying Data

When Janus opens the scratch-pad data, fields look just like they do when you edit case data. As you move through the scratch-pad data, you make the changes you need to, reviewing and validating the results as you go. Janus displays messages to let you know what you need to address to resolve the messages, warnings, and errors.** **

To get rid of all your modifications, from the _Action Bar_, select **Reset scratch pad**. Janus restores the original case data in the fields you had changed. You are still in scratch-pad mode, though, at this point. Continue to work in scratch pad until you meet the goals you need to when using scratch pad.

If you want to commit your changes to the case data, from the _Action Bar_, select **Overwrite case data**. When you do, Janus returns you to viewing the case data and displays this message at the top of the case: “You replaced all case data with data from scratch pad.” Make sure you fully agree with the changes that you brought over from scratch pad. If not, to reverse the changes, select **Undo** next to the alert message. Janus then displays the message, “Case data has been restored.”

**Note:** If you dismiss the information message (the one that says,  “You replaced all case data with data from scratch pad”)  or if you make changes to the case data, you cannot then undo the overwrite.


### Returning to Case Data

To return to viewing case data (assuming you’ve not overwritten case data), follow these steps:

1. Scroll to the top of the case.
2. In the _Scratch Pad Message Area_, select **Exit scratch pad **—the **_ _**link on the right side of the message area. Janus changes the view to the case data.  You can also use the _Action Bar_ and select **View case data**.

To return to viewing scratch pad data, again—

1. From the _Action Bar_, select **Additional case actions**.
2. From the list of actions that appears, select **Edit scratch pad data**. 

## Face Brief

### When to Face Brief

Depending on the details of the case, you might have to override certain case data, for example, specific information based on a court-ordered action. Face brief allows you to make modifications to the case data being sent to the mainframe to account for changes you can’t otherwise make in Janus. Of course, this topic can’t go into detail about all possible scenarios. But know that Janus enables you to perform those actions you need to when you face-brief a case.


### Accessing Face Brief Data

When you are ready to face-brief a case, follow these steps:

1. Make sure you calculate the case first. Once you’ve ensured that you have calculated the case, you can brief the case.
2. From the _Action Bar_, select **Additional case actions**.
3. From the list of actions that appears, select **Edit face brief data**. 

Note how the case changes. At the top in the _Face brief message area_, Janus lets you know that you are editing face-brief data. In the body of the case, Janus displays non-editable, read-only data in a compact view. Any items you _can_ edit appear in form fields, for example, _Gross to net_ or the _FERS data file_. Too, note that you _don’t_ see the FERS data file in the case data view.

![](https://janustraining.blob.core.windows.net/images/lesson7-facebrief.png)

When you access face brief data, Janus adds an icon (using the letters “FB”)  in each section header. As you scroll through the case, just like in the case data view, Janus keeps the section header fixed to the top of the view until you scroll down far enough to replace that section header. And each section header has the FB icon in it.  Again, the presence of read-only areas also signals that you’re in face-brief view.

### Modifying Data

When you modify data in Face-brief view, Janus highlights the field with a yellow background. It also adds the word **modified** in parentheses after the field label. In addition, the _Face brief message area_ provides the text: “**Face brief** data has been modified. To edit case data again, you must reset Face brief data.” In this way, Janus lets you know that you are editing face-brief data. These interface changes allow you to quickly scan through a case you have modified. 

When you want to ensure that your modifications work, from the _Action Bar_, select **Validate**. Of course, that’s because you’re not actually calculating the case, but you are ensuring the changes you have made don’t create any alert conditions. If they do, then Janus displays messages to let you know what you need to address to resolve the messages, warnings, and errors.** **

To get rid of all your modifications, from the _Action Bar_, select **Reset face brief data**. Janus restores the original case data in the fields you had changed.  You can then edit the case data as you need to.

### Returning to Case Data

To return to viewing case data, follow these steps:

1. Scroll to the top of the case.
2. In the _Face Brief Message Area_, select **View case data **—the **_ _**link on the right side of the message area. Janus changes the view to the case data.  Note: You can also use the _Action Bar_ and select **View case data**.

To return to viewing face brief data, again—

1. From the _Action Bar_, select **Additional case actions**.
2. From the list of actions that appears, select **Edit face brief data**. 
