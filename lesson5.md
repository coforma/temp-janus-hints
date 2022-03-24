# Deep Dive into Service

In this topic we'll take a deep dive into some aspects of the _Service_ section.

One of the helpful things about Janus is that you have great flexibility in how you enter service histories. We know that annuitants have an immensely wide range of how they perform service to the country throughout their careers. In the past, LASs used separate tools to keep track of how to enter a service history. Now, you enter that service pretty much as you encounter it in the claims jacket.

In the topic Opening a New Case, Part 1, we illustrated the three main areas of _Service_: the top-level details of the annuitant’s service, a table for entering each specific period of service, and a way to account for any refunds. Feel free to review that topic for a refresher if you like.

## Entering periods of service

The core of this section is the _Periods of service_ area. Its flexibility provides a way for you to concentrate on entering service details quickly without having to copy data from one place to another. 

To start, again, select **Add service**. Janus displays the four _Periods of service_ list fields. 

For best results, enter time from the top left to the lower right in the case. When you do so, you allow for the most intuitive cascade of conditionality—when you select _Service type_, the values for _Time reported as_ apply to that type of service. For example, if you select _Postal_ as a service type, then _Time reported as_ allows you to select postal-related time. For example, you could select 

* Full-time
* Seasonal full time
* Seasonal part-time
* Intermittent part-time
* Postal flex, or 
* Limited tour

When you select any service type that applies to retirement, for example, _Phased service, Last day of pay (LDOP, disability)_, or _Retirement_, then Janus hides these lists: 

* Retirement coverage
* Time reported as, and 
* Rate reported as

In the same way, Janus helps you enter deposits appropriately. For example, if in _Status of contributions_ you select **Unpaid deposit** or **Paid deposit**, Janus displays the _Rate reported as_ list:

* Annual
* Earnings
* Hourly
* Daily
* Postal flex hourly, or 
* Limited tour

After you enter values for the four lists, Janus displays fields where you can enter details about each period of service that applies to the combination of service type/retirement coverage/time reported as/status of contributions.

Initially Janus puts one period after the four lists, starting with Period 1. In most cases you enter _Start date_ and _End date_. Remember that the end date is the day the annuitant’s service ended. In some cases, you have leave without pay, or LWOP, that you need to enter. When you do, you specify whether that value represents LWOP hours or days.

![](https://janustraining.blob.core.windows.net/images/lesson5-addservice.png)

You can enter additional periods of service at the same time, as long as they have matching attributes (service type/retirement coverage/time reported as/status of contributions). To do so, select **Add another full-time period**. Keep in mind the text of the button adjusts, depending on the type of service you’re entering. When you select this button, Janus creates new blank rows that reflect your particular type/coverage/time/status combination.

When you finish with that entry, select **Save**. Janus closes the form for entering periods of service and displays a table showing the time you just entered. Don’t worry about trying to enter time in any specific order. Janus inserts rows in the table in chronological order by start date. If this results in overlapping periods of service, Janus will let you know.

Whenever you enter multiple, consecutive periods of certain types of service (such as seasonal or intermittent service), Janus collapses them into a summary row. The arrow on the left allows you to expand the row to access the details.

![](https://janustraining.blob.core.windows.net/images/lesson5-caratsummaryrow.png)

## OWCP

Let’s take a look at how you enter Office of Workers' Compensation Programs (OWCP) time. It’s somewhat rare, but it requires a special form to do so.

To enter OWCP time, follow these steps:

1.  Under the Periods of service table, select **Add OWCP**. Janus displays the _OWCP time under P. L. 108-92_ area.

    Janus uses the _Service type_ and _Time reported as_ fields to determine the appropriate multiplier. This is consistent with the data entry strategy for all other types of service in Janus.

2. Similar to how you entered service, fill out the _Start date, End date_, and _Hours of OWCP_. 
3. If necessary, select **Add another OWCP period**. Otherwise, select **Save**.

![](https://janustraining.blob.core.windows.net/images/lesson5-addowcp.png)

Once you save, Janus closes the OWCP fields and displays the table summarizing your entries. It also displays the total time the annuitant was on OWCP, shown as whole years and months, without any additional days. If you need to, you can override these values.

### Other Tips

Keep in mind that you can edit any row in a service or OWCP table. To do so, 

1. Select the pencil icon on the right of the row. Janus opens the details of that row. 
2. When you finish making your changes, select **Save.**

Janus can handle quite complex service histories, as you can tell. 
