# The Utility Drawer

In this topic, we’ll look at the Utility Drawer. Specifically, let’s go into-

* Alerts
* Documents
* History
* Comments

![](https://janustraining.blob.core.windows.net/images/lesson9-utilitydrawer.png)

## Alerts

Janus provides messages in several places to let you know about important information. Some of these messages exist as notifications in line with fields to let you know about missing or errant information. Others exist within the _Alerts_ tab of the _Utility drawer._

### Levels of Alerts

Janus uses these levels of information, each increasing the level of impact on your ability to proceed:

1. **Status messages**—Information about an aspect of the system, such as whether the application is online or offline. They also provide information that informs you about your input or actions, but does so only to orient you to available options. For example, _You are editing scratch pad data. To save changes, overwrite case data_. These messages often appear at the top of the case data area but can also exist in the _Alerts_ tab. They use an _i_ icon at the beginning of the message.

![](https://janustraining.blob.core.windows.net/images/lesson9-statusicon.png)

2. **Warning messages**—Information that informs you that your actions or input can have an effect that isn’t optimal. However, you can still proceed with your task. For example, _Verify amount is not too high_. You can still process the case, but Janus wants you to know that your entry might need further attention. These alerts begin with an exclamation point in a triangle.

![](https://janustraining.blob.core.windows.net/images/lesson9-warningicon.png)

3. **Error messages**—Conditions that block you from completing your task. For example, in the disability exam interval field, if you supplied more than three years for the disability exam interval, the message would be, _You cannot enter more than three years_. Until you reduce the years, you cannot calculate the case successfully. These alerts begin with an exclamation point in a circle.

![](https://janustraining.blob.core.windows.net/images/lesson9-erroricon.png)

In addition, messages can exist either as local or global:

1. **Local**—Message conditions that occur on the field or section level. These messages appear at the point of the error.
2. **Global**—Messages that result from a global action such as calculate, preview or send to a reviewer. These messages appear in the Alert section of the _Utility drawer_.

### Local Alerts

Let’s investigate how local alerts appear in Janus. Some fields validate the information you provide immediately after you leave that field. So, for example,  you might accidentally type an extra character in a date field. When you exit the field, Janus displays an error message below the field. Janus also places a vertical bar to the left of the field as well as a thicker border around the field to show you that this field has an error. 

![](https://janustraining.blob.core.windows.net/images/lesson9-localalert.png)

### Global Alerts

When you attempt to calculate a case, Janus checks your values to see if there are any error conditions. 

If there are, Janus opens the _Utility drawer_ automatically with the _Alerts_ tab opened. The tab shows the alerts in the order of priority, with errors at the top. Any alerts that were returned stay in the _Alerts_ tab until the next calculation. If any alert has not been resolved, it will appear again.

Within the _Alerts_ tab, you can dismiss status and warning messages. However, you have to update data or other conditions and then recalculate to dismiss errors.

![](https://janustraining.blob.core.windows.net/images/lesson9-globalalert.png)

## Documents

The Documents tab in the Utility drawer provides access to letters, forms, and other documents you might need to generate from this case.

Here’s how you work with documents:

1. From the _Utility menu_, select **Documents**. Janus opens the _Utility drawer_ and displays the _Documents_ tab.
2. To search for specific documents, enter text in the search field and select the **magnifying glass icon**. Janus shows you documents that match your search.
3. Otherwise, scroll through the documents list. Janus categorizes them in these areas:
    * Internal reports
    * Election letters
    * Letters
    * Explanations 
    
The documents within each category are largely in alphabetical order, with some exceptions to ensure that related documents are placed together in an appropriate order.
4. Select the document you would like to use. Janus displays that document as a PDF. You can view it on screen, download it, or print the document.

### Dynamic Documents

Dynamic documents require you to make decisions and/or enter additional information that will be used to populate the document. The only two dynamic documents in Janus are the _case file report_, _case notices_, and _free-form document_.  With the case file report, you can choose which sections to print. With case notices, you have many options that might even include custom information. For an example let’s look at the _free-form letter_:

1. With the _Utility drawer_ open to _Documents,_ from within the _Letters_ section, select **Free-form letter**. Janus opens the _Free-form letter_ view.
2. Janus lets you know that it will use the data from the case to populate the date, the to: information, and the from: block of text. In the _For your information (custom content)_ field, type the information you want to include in the letter.
3. To see what your choices might look like, select **Preview letter**. Janus opens a PDF preview of the contents. You can  print the letter or download it.
4. To return to the case to adjust details, select the tab in the browser that Janus is open in.

## History

When a change occurs to a case, Janus keeps track of those changes. The _History_ tab of the _Utility drawer_ provides a list with the most recent ones at the top. Each entry has these elements:

* A description of what occurred. For example, “Case calculated.”
* The name of the person who made that change.
* The date and time that it occurred.

## Comments

Janus lets you add case-specific, free-form comments. You can also decide whether to include specific comments in a report. The _Comments_ tab of the _Utility drawer_ provides a list of any existing comments, with the most recent at the top. Each entry has these elements:

* The text of the comment. For example, “I needed to re-enter Maia’s survivor information.”
* The name of the person who made that comment.
* An indication of whether that comment is included in the report.
* The date and time that it was entered.

To search for existing comments, enter text in the search field. As you type, Janus looks for comments that match the text you are typing.

Sometimes you need to add a comment yourself. You might want to let a reviewer understand some aspects of the case. For example, you might want the reviewer to know that the annuitant recently moved. Here’s how you enter comments:

1. From the _Utility menu_, select **Comments**. Janus opens the _Utility drawer_ focused on _Comments_.
2.  Select **Add a comment**. Janus focuses you on a field where you can enter your comment.
3. If you want to ensure that this comment gets added to the Case File report, select the **Include in report **checkbox. 
4. Select **Save**. Janus adds your comment at the top of the list. 

You can edit or delete your own comments after you’ve saved them, too.
