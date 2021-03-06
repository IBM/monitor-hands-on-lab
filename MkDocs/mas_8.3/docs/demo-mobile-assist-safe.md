# Manage - Mobile - Assist - Safety Lab

!!! note
    Please follow the `Action` statements to navigate the steps and perform the lab.

## Service Request to Work Order

Within Manage EAM, the newly created Service Request can be automated into a WO, tasks and labor are assigned and the status changed to approved.   It is beneficial to have records processed without human intervention to increase the throughput rates and allow those resources to work on more value-add activities.
In some cases, a manual review by a supervisor may occur where they can drill into related history records against the PUMP, they can also link directly to the monitor dashboard to review the details of the anomaly/alert.  Part of the evaluation may or may not give enough information to know exactly what needs to be addressed, so in this case an inspection should be performed. The supervisor can approve the work order and assign the appropriate resource.
 <br>

## Execute Work Order
As a technician, I can login to Maximo Mobile EAM and from the navigation page, tap My Schedule to see work that has been assigned to me whether I’m in the break room, on the other side of the plant, or even offline.<br>
`Action:` Go into Maximo Mobile, click My Schedule. 

![img](/img/mas_8.3/mobile_schedule.png){: style="height:400px;width:250px;margin-left:40px"}

!!! note
    Main Screen could look like Tiles or Tabs depending which display setting you choose. This main screen is currently using Tabs.

I see a new work order assigned to me, which is presented to me in order of priority so that I am focused on the right job at any given time in my shift. 

![img](/img/mas_8.3/work_orders.png){: style="height:400px;width:250px;margin-left:40px"}

I can look at all my work in a list, or use the map view to see work nearby and perform additional tasks like route optimization so I get to the correct location in the most efficient way. The location information can help direct me to the proper asset within the plant to perform the work order tasks.<br>
`Action:` Click on the map view icon in top right corner, then go back to My Schedule using the List menu next to Map icon.

![img](/img/mas_8.3/map_1.png){: style="height:400px;width:250px;margin-left:40px"}
![img](/img/mas_8.3/map_2.png){: style="height:400px;width:250px;margin-left:40px"}

As I arrive at the site of my next work order I check in with my Safety Officer so they know my location.

I open the newly assigned work order and follow the indicated touch point to Start the Work.  This will begin recording the time spent on these tasks.   
`Action:` Click Start Work in the work order that was generated from Monitor, then go into the Work Order.

![img](/img/mas_8.3/start_work.png){: style="height:400px;width:250px;margin-left:40px"}
![img](/img/mas_8.3/enter_work.png){: style="height:400px;width:250px;margin-left:40px"}

Within the details of the WO, I can also see additional information including links in the long description that could take me back to monitor to see details of the anomaly.   
`Action:` Click on alert-based work order, Show the long description of the work order which includes hyperlinks back to Monitor.

![img](/img/mas_8.3/long_description.png){: style="height:400px;width:250px;margin-left:40px"}
![img](/img/mas_8.3/monitor_links.png){: style="height:400px;width:250px;margin-left:40px"}

By following the applications guidance, I tap on the blue highlighted TASK icon. Here I can see the individual steps needed to complete the inspection.<br> 

![img](/img/mas_8.3/work_tasks_1.png){: style="height:400px;width:250px;margin-left:40px"}

It’s important that as a new technician that I have clear instructions available to me to ensure I’m performing the correct steps and gathering the proper information needed to complete this work. In Maximo Mobile, it is all about presenting the right information, in the right place, at the right time. 

I can now Start the inspection process.<br>
`Action:` Click the Start button.

![img](/img/mas_8.3/inspectionwo.png){: style="height:400px;width:250px;margin-left:40px"}

`Action:` Review the inspection questions and respond All is normal except vibration and noise which are high indicating a problem.

![img](/img/mas_8.3/inspectionwo2.png){: style="height:400px;width:250px;margin-left:40px"}


I was going through the possible causes of what could be causing the vibration. There is nothing in the skid that seems to be causing instability, but I suspect that the O-ring may be worn out or deteriorated.  

FOLLOW UP WORKORDER IS TYPICALLY CREATED TO INDIVIDUALLY CAPTURE THE TIME AND MATERIALS
It should be replaced, but since I am not familiar with how to do this, I use Maximo Assist to see if there is additional steps or instruction that would be useful. 

## Assist Queries

From the Mobile navigator, I click ‘Assist’ to open the search page where I can enter the search criteria.

`Action:` Open the Maximo Mobile app and enter “Replace Pump O-Ring”, then select return.

Here I see the AI-powered search results arranged by most relevant recommendations at the top and organized in decreasing order of confidence. The AI shows me recommendations from manuals, historical work orders, previous collaboration sessions, training content – all of these different types of data sources are available for me to search against.  

 

If there are historical work orders, I can also look at additional details such as tasks, logs, failure reports or I can select on it to see exactly what was done in the past.

`Action:` Show historical work order. 

 

I can also further refine the search results by selecting the filter option.

`Action:` Turn on the filter for asset type (`PUMP`), and manufacturer (`ABB`) and select done.  

 

I now see even more refined search results and the top result is now a maintenance manual. By giving the AI model feedback for the recommendations and marking them as relevant or not-relevant I am continuously training the AI models in real-time and improving the recommendations. 

`Action:` Select the `Yes` option in the search result, open up top result. 

Selecting the top recommendation in the search result presents the manual opened up and scrolled down to where the AI detects the most relevant passage which is highlighted in blue. This is really helpful especially in troubleshooting scenarios where there are surrounding images, and this can further help me get visual aid on the actions to take.  

 



## Contact Remote Expert

In this case, I can see the O-ring replacement instructions with visuals. I am able to follow them until I attempt to remove the O-ring. Even following these instructions, it seems like the O-ring will not come off easily, and I don’t want to risk damaging it. I could use some additional instructions to perform the fix So I choose to contact a remote expert for assistance. 

`Action:` Select the `Contact Expert` option in the top right – type `replace O-ring` in the search field for (What do you need advice about?) 

Here I can see the online experts organized by area of expertise, and can also see the experts with top skill matches based on the work context. I see someone in the pump group is online so I initiate a collaboration request with them using the blue touchpoint. Soon, I receive a notification that they accepted the request and I initiate the session and can now use my mobile devices camera to show them what I see. 

 

`Action:` Select `Pump Group` to accept the request  

`Action:` Select `START` to accept the request 



In this scenario we do not require audio but there are options to use voice or if we’re in a noisy environment we can use text to communicate.   

`Action:` Turn audio off on both devices so it doesn’t interfere. 

As I show my phone, the expert on their side views a stream of near-real time images and can select on one of them to provide what actions I should take. I’m going to indicate where exactly I’m stuck so the expert can provide some guidance. The expert can either enter pointed annotations or sketch on the screen directly using Augmented Reality.   There are also options with the annotations to mark them as a safety hazard so that the technician is careful as they perform the recommended action. 


`Action:`  Select blue button on the bottom right corner - Technician adds annotation - ‘this is stuck’ (red 		arrow is only pointing to annotation just made, not a part of Assist) 

`Action:` Expert adds any instruction “pry here”, either in chat or draw using sketch. 

 

This now shows up on the technicians view exactly where the expert had marked it which is the same experience they would have had if the two were next to each other.     

You will notice that even when my phone is pointed in a different direction, the green arrow will direct me to the new annotation so I don't miss it.    

`Action:` Move phone away from annotations. 

The action of providing leverage to remove the o-ring worked and I’m able to now complete the rest of the tasks involved with replacing the part. I’ll end the collaboration session which will create a session summary with all of the chat transcripts and the guidance that was provided. This now can be added to the AI knowledge base for future reference. 

`Action:` Select the end the session icon in the top left corner, then select `Yes`. 







## Close Work Order

Now that I have completed all the tasks for this work order, I also go ahead and add this to the comments in the work order work log that "Replaced O-Ring"<br>   
`Action:` Open the worklog by clicking on the worklog touchpoint and type in the description 

![img](/img/mas_8.3/empty.png){:style="height:400px;width:800px"}

I then need to record the failure information so that accurate data on the cause and remedy for this problem is available to support future analysis.  This information gathering is invaluable for Health and Predict as it provides rich qualitative data from the human-in-the-loop, to supplement our precise quantitative data coming from Monitor, to pinpoint exactly how, why, and when failures occurred. These failure codes for excessive vibration can now be used to update health and failure prediction dates later by a Reliability Engineer.<br>
`Action:` Select Report Work Icon in same view of the other icons. Add Failure Class ‘Pump Failures’, Problem ‘Stopped’, Cause ‘Vibration’ and Remedy ‘Replaced Part’. 

![img](/img/mas_8.3/failure_report.png){: style="height:400px;width:175px;margin-left:40px"}
![img](/img/mas_8.3/failure_1.png){: style="height:400px;width:175px;margin-left:40px"}
![img](/img/mas_8.3/failure_2.png){: style="height:400px;width:175px;margin-left:40px"}

I need to record the part that was used during the work and add that I used material ‘o-ring’ to the WO actuals.<br>
`Action:`  Add + to the Materials section, O-ring, qty 1

![img](/img/mas_8.3/empty.png){:style="height:400px;width:800px"}


I want to also record the time it took to execute the steps of the WO and complete the WO. This data will help future planners and schedulers to estimate how long work like this typically takes, and more efficiently plan and assign these types of jobs. And I also add the unplanned parts and materials I used in replacing the o-ring.<br>
`Action:` Add time or stop the clock and close out the work order by selecting Complete work.

![img](/img/mas_8.3/timecard1.png){: style="height:400px;width:250px;margin-left:40px"}
![img](/img/mas_8.3/timecard2.png){: style="height:400px;width:250px;margin-left:40px"}


As the technician is leaving the site they slip on a wet floor and fall and are unable to get up. This is a man-down situation.   

<b>TRANSITION:</b>  I’m now going to hand it over to the Safety Officer who is monitoring the technicians across the plant.




 


 


