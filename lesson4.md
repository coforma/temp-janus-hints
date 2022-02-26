# Lesson Nine Script: The Utility Drawer
Welcome to Janus, the new retirement services application to help you adjudicate retirement claims. 

In this lesson, we’ll look at the Utility Drawer. Specifically, let’s go into—
- Alerts
- Documents
- History
- Comments
![](https://janustraining.blob.core.windows.net/images/lesson9-utilitydrawer.png)

## Alerts
Janus provides messages in several places to let you know about important information. Some of these messages exist as notifications in line with fields to let you know about missing or errant information. Others exist within the _Alerts_ tab of the _Utility_ drawer. 

### Levels of Alerts
Janus uses these levels of information, each increasing the level of impact on your ability to proceed:

1. **Status messages**—Information about an aspect of the system, such as whether the application is online or offline. They also provide information that informs you about your input or actions, but does so only to orient you to available options, for example, the message *You are editing scratch pad data. To save changes, overwrite case data*. These messages often appear at the top of the case data area but can also exist in the *Alerts* tab. They use an *i* icon at the beginning of the message. ![](https://janustraining.blob.core.windows.net/images/lesson9-statusicon.png)

2. **Warning messages**—Information that informs you that your actions or input can have an effect that isn’t optimal. However, you can still proceed with your task. For example, *Verify amount is not too high*. You can still process the case, but Janus wants you to know that your entry might need further attention. These alerts begin with an exclamation point in a triangle.  {:.some-class}![](https://janustraining.blob.core.windows.net/images/lesson9-warningicon.png)

3. **Error messages**—Conditions that block you from completing your task. For example, in the disability exam interval field, if you supplied more than three years for the disability exam interval, the message would be, *You cannot enter more than three years*. Until you reduce the years, you cannot calculate the case successfully. These alerts begin with an exclamation point in a circle. ![](https://janustraining.blob.core.windows.net/images/lesson9-erroricon.png)

In addition, messages can exist either as local or global:
- **Local**—Message conditions that occur on the field or section level. These messages appear at the point of the error.
- **Global**—Messages that result from a global action such as calculate, preview or send to a reviewer. These messages appear in the Alert section of the Utility drawer.

### Local Alerts
Let’s investigate how local alerts appear in Janus. Some fields validate the information you provide immediately after you leave that field. So, for example,  you might accidentally type an extra character in a date field. When you exit the field, Janus displays this error message: 
**Dates must contain between four and eight numbers. Separators are optional. No letters or special characters.**

Janus also places a vertical bar to the left of the field as well as a thicker border around the field to show you that this field has an error. 

![](https://janustraining.blob.core.windows.net/images/lesson9-localaert.png)

### Global Alerts
When you attempt to calculate a case, Janus checks your values to see if there are any error conditions. 
If there are, Janus opens the *Utility* drawer automatically with the *Alerts* tab opened. The tab shows the alerts in the order of priority, with errors at the top. Any alerts that were returned stay in the *Alerts* tab until the next calculation. If any alert has not been resolved, it will appear again.

Within the *Alerts* tab, you can dismiss status and warning messages. However, you have to update data or other conditions and then recalculate to dismiss errors.

![](https://janustraining.blob.core.windows.net/images/lesson9-globalalert.png)

## Documents
The *Documents* tab in the *Utility* drawer provides access to letters, forms, and other documents you need to process the case. Here’s how you work with documents:

1. From the Utility menu, select Documents. Janus opens the Utility drawer and displays the Documents tab.
2. To search for specific documents, enter text in the search field and select the magnifying glass icon. Janus shows you documents that match your search. 
3. Otherwise, scroll through the documents list. Janus categorizes them in these areas:
	- Internal reports
	- Election letters
	- Letters
	- Explanations
		The documents within each category are largely in alphabetical order, with some exceptions to ensure that related documents are placed together in an appropriate order.
		
4. Select the document you would like to use. Janus displays that document as a PDF. You can view it on screen, download it, or print the document.

### Dynamic Documents
Dynamic documents require you to make decisions and/or enter additional information that will be used to populate the document. The only two dynamic documents in Janus are the *case file report* and *case notices*. With the case file report, you can choose which sections to print. With case notices, you have many options that might even include custom information. Rather than going into all possibilities, let’s just look at how to access this area:

1. With the *Utility* drawer open to *Documents*, from within the *Letters* section, select **Case notices**. Janus opens the *Case notices view*.
2. Select options based on your needs. For example, to indicate to an annuitant that health benefits have been canceled, select the **Include in case notice letter** checkbox underneath *Health benefits canceled*. Each area opens a specific set of further options to adjust details of the letter.
3. To see what your choices might look like, select **Preview letter**. Janus opens a PDF preview of the contents.
4. To return to the case to adjust details, select **Go back to case**.

## History
When a change occurs to a case, Janus keeps track of those changes. The *History* tab of the *Utility* drawer provides a list with the most recent ones at the top. Each entry has these elements:

- A description of what occurred. For example, “Case calculated.”
- The name of the person who made that change.
- The date and time that it occurred.

## Comments
Janus lets you add case-specific, free-form comments. You can also decide whether to include specific comments in a report. The *Comments* tab of the *Utility* drawer provides a list of any existing comments, with the most recent at the top. Each entry has these elements:
- The text of the comment. For example, “I needed to re-enter Maia’s survivor information.”
- The name of the person who made that comment.
- An indication of whether that comment is included in the report.
- The date and time that it was entered.

To search for existing comments, enter text in the search field and select the **magnifying glass icon**. Janus shows you comments that match your search.

Sometimes you need to add a comment yourself. You might want to let a reviewer understand some aspects of the case. For example, you might want the reviewer to know that the annuitant recently moved. Here’s how you enter comments:
1. From the *Utility* menu, select **Comments**. Janus opens the *Utility* drawer focused on *Comments*.
2.  Select **Add a comment**. Janus focuses you on a field where you can enter your comment.
3. If you want to ensure that this comment gets added to the Case File report, select the **Include in report** checkbox. 
4. Select **Save**. Janus adds your comment at the top of the list. 

## End
Thanks for attending this Janus lesson.
