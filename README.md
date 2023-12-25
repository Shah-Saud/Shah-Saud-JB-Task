# Shah-Saud-JB-Task
 Android Screenshot App using service


#Android Assessment Task 

1: Implement a Foreground Service that runs on app startup. The service should 
have a Foreground Notification with two remote action buttons: "Screenshot" 
and "Cancel.". 
2: On clicking the Screenshot button close the notification tray. Capture a 
screenshot of the current opened mobile window and save each captured 
screenshot to the mobile gallery. On clicking the Cancel button close the 
application. Ensure that no service is left running in the background. 
3: Display a RecyclerView on the main screen to list all captured screenshots. On 
every screenshot image item there should be a button, when you click this button 
a Menu Dialog should appear allowing you to perform delete, share and open the 
image in next activity. 
4: When any change (save or delete of screenshot) occurs, update your data in 
your main screen RecyclerView using best practice. 
5: Implement a Google AdMob interstitial ad that appears when any image item 
is clicked. Ensure proper handling of interstitial ad callbacks. 
6: Every third row of the RecyclerView should be a smart native ad, i.e., the first 
and second rows should contain three screenshots image items, and the third row 
should contain a smart native ad (AdMob). 
7: Integrate a swipe refresh layout with the RecyclerView and incorporate 
LiveData and Coroutines to enhance the overall user experience, providing a 
seamless and efficient interface.
