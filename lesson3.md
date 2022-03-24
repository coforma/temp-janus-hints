# Opening a New Case, Part 1

In this topic we'll talk about opening a new case and the sections you work with to adjudicate a case. 

First, either select a case from the list, or type the case number into the _Open a case_ field and select OK. The case opens.  You can start with any section you want to, but in this topic, let’s start at the top with _Health benefits._

## Health Benefits

By default, Janus pulls the current healthcare benefits plan from the mainframe. Depending on the case, you might have to change the original health plan or add a plan change. To change the original plan, begin typing in the list field to the left of the down-pointing arrow. Janus matches your typed characters to bring up items that match.

Some things to keep in mind about how selection lists like this work in Janus. You can browse through a list or select the down-pointing arrow and scroll through the list.

To search through a list, select the field area to the left of the down-pointing arrow and begin typing. Janus matches the characters you type with items that might be in the list.

Sometimes you need to enter a plan change. To do so, follow these steps:

1. First, select **Add a plan change**.
2. Next, select the new plan. 
3. After you select a plan from the list, in the _Effective date_ field, enter the date the plan became effective.

Note that Janus currently can handle up to six plan changes.

## Life Insurance

Let’s look at how you account for an annuitant’s life insurance coverage. If the annuitant is eligible to so, select the checkbox **Customer is eligible to continue basic life insurance**. Janus expands the area to display details about that coverage. Here’s how to fill out that area:

1. In the Basic life insurance amount field, enter the amount of life insurance coverage for the annuitant. Keep in mind that you need to round any value up to the nearest thousands of dollars and then add $2,000 to that value. 
2. In the Post-retirement reduction list, select the amount of any reduction.

Now you can account for any optional coverage. 

1. If the annuitant has elected standard optional coverage, select the check box **Customer has elected standard optional coverage** under _A. Standard optional insurance_.
2. If they’ve also elected additional optional coverage, select the level of coverage in the _B. Additional insurance_ list. Janus lists it as a multiple of their salary. In most cases, annuitants elect a reduced amount or a non-reduced amount. 
3. Finally, if the annuitant has indicated they want family optional insurance, select the amount of that optional coverage in the _C. Family optional insurance_ list.

Sometimes you need to account for a change in coverage

1. First, select **Add a coverage change** that goes into effect after the commencing date.
2. Next, in the _Effective date_ field, enter the date the change to insurance coverage became effective.
3. In the same way that you filled out the initial elections, select the appropriate options. 

## Customer

Now we'll move to the Customer area. 

Here you account for details about the annuitant themselves. By default, the mainframe populates the Agency code list (indicating the agency from which they retired), the annuitant’s date of birth, the Social Security number, and their mailing address. Let’s take a look at the way you enter information into this area.

1. Enter their last name, first name, and any middle initial they might have. Keep in mind that the values might be adjusted or shortened, based on the values that the mainframe accepts.
2. Check that the _Agency code_ list item is accurate. If not, select the correct code.
3. Check the date of birth and the Social Security number fields. 
4. Check the _Federal Income Tax (FIT) basis _field. 
    1. If the annuitant has a Social Security number, this field is **1 US person with US source of income ** or **5 US person with foreign source of income**.
    2. If the annuitant does _not_ have a Social Security number, Janus displays _999999999 _in the Social Security field. In that case, select the appropriate list item (such as **3  Foreign person with foreign source of income)**.
5. In the _Gender_ area, select the radio button that most likely applies to the annuitant.
6. In the _Marital status_ area, select the radio button that indicates whether the annuitant is married or is single. 
7. In the _Phone number _field, enter the annuitant’s phone number. You can enter just the 10 numbers without entering any parentheses or dashes. Janus provides those automatically.
8. In the _Email address_ field, enter the annuitant’s email address where they want to be contacted.

Sometimes an annuitant has a mailing address different from the one you see in the case. Any address you enter will go into letters you generate from Janus. To add a mailing address, follow these steps:

1. Deselect **Same as payment address. **Janus displays fields for filling out a_ correspondence address_.
2. Note that_ Address line 2_ is optional. Sometimes you need to add additional information, such as the name of a designated representative or perhaps an apartment number.
3. Some annuitants reside outside the United States. In the _Country_ list, select that country. Janus replaces _State_ with _Province/region_ and _ZIP_ with _Postal code_. 

## Survivor

In the Survivor section, you indicate whether the annuitant has designated someone to receive the survivor benefits after death. Janus detects whether the case is a CSRS or a FERS case and gives you appropriate options in the _Survivor election_ field:

For CSRS cases, you can select— 

* None
* CSRS full, or
* CSRS partial.--

If it’s a FERS case, you can select—

* None
* FERS full, or 
* FERS half.

When you select anything other than _None_, Janus displays additional fields. These self-explanatory fields allow you to provide identity information for the survivor. 

## Military

The Military section lets you indicate whether the annuitant has any military service as well as whether that service resulted in retired pay. If it did, you indicate whether the annuitant has waived that retired pay.

## Service

The main thing to keep in mind with the _Service_ section is that you enter service history as you find it in the case jacket. When you encounter a type of service, Janus generally has a way to enter that time. Let’s take a look.

_Service_ has three main areas: the overall identifier of the annuitant’s service, a table for entering each specific period of service, and a way to account for any refunds. 

At the top of the _Service_ section, you enter the annuitant’s coverage at retirement, their retirement type, and any aggregate unused sick leave and overseas service. Finally, you enter the agency service computation date (SCD).

![](https://janustraining.blob.core.windows.net/images/lesson3-service.png)

Let’s take a look at entering periods of service. When you first encounter a case in Janus, it doesn’t show any service history. To enter the annuitant’s history, follow these steps:


1. Select **Add service**. Janus displays four list fields. \
By using a combination of the four fields that appear, you can account for pretty much any service history. As you make choices in the lists, Janus uses conditional logic to display choices that pertain to your entries.
2. In the _Service type_ list, select the service type, for example, civilian, postal, air-traffic controller, and so on.
3. In the _Retirement coverage_ list, select that coverage type, for example, CSRS, FERS, ORDS, and so on.
4. In the _Time reported as_ list, identify the way the service was reported, for example, full time, part time, seasonal, and so on.
5. In the _Status of contributions _list, identify whether the annuitant’s history has any type of contributions. It accounts for whether the contributions were never refunded or are eligible for a paid or unpaid deposit or redeposit.

Using these four fields, you can account for a large number of service history scenarios. A later topic takes an in-depth look at the Service section. For now, realize that you use these lists to set up the accounting for any period of service.

To identify refunded service, follow these steps:

1. In the _Refund _area, select **Add refund.** Janus displays a row for refund identification.
2. Enter the start date and end date for that refund.
3. In the _Type_ list, select that type of refund, for example, FERS, CSRS - Pre-10/90 , or CSRS - Post-10/90.

While a service history can get complex, Janus accounts for most scenarios, without the need to go to a separate calculator or time converter.

## Salary

Now let’s look at the _Salary_ section.

Similar to _Service_, the _Salary_ section consists of two main areas: Pay changes and comparison groups. For the most part, you will use the pay changes area.

When you open a new case in Janus, it provides three blank rows for pay changes. As you enter the pay information, Janus helps make it easier for you: 
- When you select a type of pay change, by default Janus repeats that information in the other two displayed rows.
- That way you can concentrate on entering just the start date and the amount.

As you need to enter more pay rates, select **Add a pay change**. Janus adds a new row at the end of the pay changes. 

To put the pay changes in order, select **Sort pay changes by date**. You don’t _have_ to do this, because when you calculate or reload the page, Janus automatically sorts pay changes chronologically by start date within a group.

To indicate when the pay records end, provide a date in the _End date_ field.

In some cases, you need to account for periods that include tours of duty or unpaid deposits (or both). To account for this, select the **Tours of duty** or the **Unpaid deposits **checkboxes at the top of the section.

Sometimes you want to compare how different periods of pay might affect the tabulation of the high three salary amounts. To create a comparison group, select **Add a comparison group**. Janus displays a table similar to the pay changes area. We’ll take a deeper dive into salary in a later topic.

## Contributions

Finally, the Contributions section provides a way to capture the amounts of monies the annuitant put into retirement. Just like the _Pay change_ area, _Annual contributions_ displays three empty rows. The _Type_ field follows the same automation logic as for pay changes. In addition, as you enter contributions, Janus provides totals next to what you are filling out.

Keep in mind that you can enter multiple annual contribution amounts for the same year. 

Janus reminds you that you need to calculate the case to determine whether this annuitant is eligible for an annuity supplement.

The topic “Opening a New Case, Part 2” looks at the post-calculation sections as well as the _Action Bar_.
