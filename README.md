# MAD Practical 3 - Event-Handler
Continuing from last week, you will be adding interactivity to your app. <br/>
Follow the instructions below to complete your app.

1. Modify the onClickListener of left button to show a Toast message. The toast message will show `Followed` if the user click on the `Follow` button, and vice versa.

![Toast Message](/images/p2_toast.png)

2. Create a new Empty Activity with the following configuration,
    * Activity Name: ListActivity
    * Generate a Layout File: Checked
    * Layout Name: activity_list
    * Launcher Activity: Checked
    * Source Language: Java

3. In the `activity_list` layout file, create an `ImageView`, position it in the middle of the screen.

![ImageView in middle of Activity](/images/p2_img.png)

4. Create an `onClickListener` for the image created in previous step. Upon clicking the image, an `AlertDialog` will appear as shown in the figure below.

![AlertDialog](/images/p2_alert.png)

5.	Upon clicking the `View` button, a random integer will be generated. The `MainActivity` (created in previous practical) will be launched, and the random integer is sent over.

6.	Modify the `MainActivity` to display the random integer together with the name. 

![Updated Profile page](/images/p2_final.png)

# CHALLENGE
7. Create a new Empty Activity with the following configuration,
    * Activity Name: MessageGroup
    * Generate a Layout File: Checked
    * Layout Name: activity_message_group
    * Launcher Activity: Unchecked
    * Source Language: Java

8. Create an event listener for the `Message` button. Upon clicking on the button, `MessageGroup` created in previous step will be launched.

<img src="/images/q8.PNG" width="216px"/>

9. Modify the layout of `MessageGroup` to as shown in the image below.

<img src="/images/q9.PNG" width="512px"/>

10. Fragments are commonly used in Android applications. They are an extension to Activities. <br/>Research and discover how to implement loading of fragment within an activity. <br/><br/>Implement `MessageGroup` as illustrated in the image below.<br/><br/>[https://guides.codepath.com/android/creating-and-using-fragments#embedding-a-fragment-in-an-activity]

<img src="/images/q10.PNG" width="512px"/>

To submit your practical, remember to commit the changes and push to remote repository.
