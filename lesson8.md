# Lesson Eight Script: Reviewing and Reissuing Cases
Welcome to Janus, the new retirement services application to help you adjudicate retirement claims. 

In this lesson, we’ll look at how you—
- Review cases
- Trigger cases
- Reissue cases

Depending on your role and the Janus permissions that come with it, you might be responsible for reviewing the retirement cases that LASs have submitted. You want to ensure that they’re accurate and free of errors. Once you’re satisfied with your analysis, you can trigger the case, queueing its data up to be sent to the mainframe.

## Reviewing a Case
First, start from the *Home* page. In the *Open a case* field, enter the case number to review. You can also scan through the list of cases for ones whose status is *In review*. 

Next, open a case to review. When you open it, note that the *Action bar* looks a little bit different than it does for an LAS working on the case. You can—
- View a summary of the case
- Send the case back to the LAS for edits
- Send the case to the mainframe by triggering it

When you review the case, look for anomalies or inaccuracies. Your years of experience as well as training give you that unique perspective. As you find any issues that might need to be addressed, add a comment so the LAS will know why you are sending the case.

To add a comment—
1. From the *Utility drawer* icons, select **Comments**. Janus opens the *Utility drawer*. Add your comment as appropriate. 
2. Make sure you preface your comments with the LAS’s name, if possible. For example, you might say, “Note for Pat: You have created too many salary records but don’t have a proper high-3. Please correct and resubmit.”
3. When you finish adding comments, you can close the *Utility drawer*.

Once you finish with your comments, you can send the case back to the LAS. To do so, from the *Action bar*, select **Send back to edit**. Janus keeps the status of the case as In review.

## Triggering a Case
When your analysis indicates that there are no issues with the case you’re reviewing, you’re ready to commit the case to the mainframe. To do so—
1. From the *Action bar*, select **Trigger case**. Janus sends the data to the mainframe and closes the case, returning you to the *Home* page.
2. The *Home* page displays a message confirming that you have triggered the case.
3. Now you can work on another case.

Remember that triggered case data isn’t fully committed until after the 6:00p.m. Eastern time zone mainframe run. If you find that you need to change something in that triggered case, if it’s before the 6:00p.m. cutoff, you can send the case back to the original LAS for changes. To do so—
1. From the *Action bar*, select **Send back to edit**. Janus puts the case into *Edit* status.
2. Notify the LAS that you have pulled the case back so changes can be made. 
3. Once everything is in order, trigger the case again.
**Note:** Once the cutoff passes, you cannot pull a case back from having been triggered. Instead, you need to reissue the case. 

## Reissuing a Case
In some cases, after a case is triggered, you need to make some changes to that case as well as the annuity. For example, additional missing service comes in that RS didn't know was out there. Perhaps the original agency didn't transmit that information to RS...so the LAS adjudicated the case with incomplete information. Perhaps they worked at the IRS for 10 years but never got credit for that time.

So Janus enables you to retrieve an already triggered case, put it into a state where you can make changes, and then re-trigger the case. Here’s how you do that:
1. From the *Home* page, find the case you need to reissue. You can use the search facility to find cases assigned to you, scroll through the list of cases, or enter the number in the *Open a case* field.
2. When the case opens, because it has already been triggered, first you need to check whether there is a payment match. In the *Action bar*, select **Begin reissue process**. Janus determines whether there is in fact a payment match. 
3. If so, Janus displays the message, “Mainframe payment version was created. Payment match succeeded. You may reissue the case” at the top of the case.
4. Either select the link reissue the case or, in the *Action bar*, select **Create version to reissue**. Janus creates a new version that enables you to make the appropriate changes you need to make. Now Janus lets you know that it created a reissue version. You can make case data changes as you need to.
5. Once you have done so, select **Calculate**. 
6. Once everything is ready, select **Send for review**.

At this point, your reviewer can proceed to review the case.

In the event Janus does not find a payment match, Janus displays the message, “Mainframe payment version was created. Payment match failed. To reissue, adjust case data and check again for payment match.” You need to review your case data entries. Once you adjust any data, select **check again for payment match**. Janus performs another payment match.

## Canceling a Reissue
Sometimes you need to cancel a case that Janus reissued. To do so—
1. From the *Action bar*, select **Additional case actions**.
2. From the menu, select **Cancel reissue**. Janus then displays a message box. It lets you know that the mainframe payment and the reissue versions both will be deleted. 
3. If you want to proceed with the cancellation process, select **Yes, cancel reissue process.**
4. If you do not want to proceed with the cancellation process, select **No, do not cancel**. 

##End
Thanks for attending this Janus lesson.
