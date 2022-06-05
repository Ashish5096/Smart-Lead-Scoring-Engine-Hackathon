# Smart-Lead-Scoring-Engine
Analytics Vidhya Hackathon


<b> Problem Statement </b>


A D2C startup develops products using cutting edge technologies like Web 3.0. Over the past few months, the company has started multiple marketing campaigns offline and digital both. As a result, the users have started showing interest in the product on the website. These users with intent to buy product(s) are generally known as leads (Potential Customers). 

Leads are captured in 2 ways - Directly and Indirectly. 

Direct leads are captured via forms embedded in the website while indirect leads are captured based on certain activity of a user on the platform such as time spent on the website, number of user sessions, etc.

Now, the marketing & sales team wants to identify the leads who are more likely to buy the product so that the sales team can manage their bandwidth efficiently by targeting these potential leads and increase the sales in a shorter span of time.

Now, as a data scientist, your task at hand is to predict the propensity to buy a product based on the user's past activities and user level information.


<br><br>
<b> About Dataset</b>

You are provided with the leads data of last year containing both direct and indirect leads. Each lead provides information about their activity on the platform, signup information and campaign information. Based on his past activity on the platform, you need to build the predictive model to classify if the user would buy the product in the next 3 months or not.


<br><br>
<b>Data Dictionary</b>

You are provided with 3 files - train.csv, test.csv and sample_submission.csv


<br><br>
<b>Training set</b>

train.csv contains the leads information of last 1 year from Jan 2021 to Dec 2021. And also the target variable indicating if the user will buy the product in next 3 months or not


<table>
  <tr>
    <th>Variable</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>id</td>
    <td>Unique identifier of a lead</td>
  </tr>
  <tr>
    <td>created_at</td>
    <td>Date of lead dropped</td>
  </tr>
  <tr>
    <td>signup_date</td>
    <td>Sign up date of the user on the website</td>
  </tr>
  <tr>
    <td>campaign_var (1 and 2)</td>
    <td>campaign information of the lead</td>
  </tr>
  <tr>
    <td>products_purchased</td>
    <td>No. of past products purchased at the time of dropping the lead</td>
  </tr>
  <tr>
    <td>user_activity_var (1 to 12)</td>
    <td>Derived activities of the user on the website</td>
  </tr>
  <tr>
    <td>buy</td>
    <td>0 or 1 indicating if the user will buy the product in next 3 months or not </td>
  </tr>
</table>

<br><br>
<b>Test set</b>

test.csv contains the leads information of the current year from Jan 2022 to March 2022. You need to predict if the lead will buy the product in next 3 months or not.

<table>
  <tr>
    <th>Variable</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>id</td>
    <td>Unique identifier of a lead</td>
  </tr>
  <tr>
    <td>created_at</td>
    <td>Date of lead dropped</td>
  </tr>
  <tr>
    <td>signup_date</td>
    <td>Sign up date of the user on the website</td>
  </tr>
  <tr>
    <td>campaign_var (1 and 2)</td>
    <td>campaign information of the lead</td>
  </tr>
  <tr>
    <td>products_purchased</td>
    <td>No. of past products purchased at the time of dropping the lead</td>
  </tr>
  <tr>
    <td>user_activity_var (1 to 12)</td>
    <td>Derived activities of the user on the website</td>
  </tr>
</table>

