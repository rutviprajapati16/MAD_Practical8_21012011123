**Practical-8:**

**Study:** BroadcastReceiver, Service, TextClock, TimePickerDialog, Calendar Class, SimpleDateFormat Class, PendingIntent, AlarmManager, getSystemService() method, sendBroadcast() method, MediaPlayer, startService(), stopService() method, Intent.getStringExtra(), Intent.putStringExtra(), MaterialCardView

**AIM:** What is BroadcastReceiver? Difference between Service and BroadcastReceiver. Create an Alarm application by using service & BroadcastReceiver by following below instructions.

1.Create MainActivity according to below UI design.

2.Create AlarmBroadcastReceiver class

3.Create AlarmService Class

4.Add android.permission.SCHEDULE_EXACT_ALARM Permission in Manifest file

**Ans:**

Broadcast in android is the system-wide events that can occur when the device starts, when a message is received on the device or when incoming calls are received, or when a device goes to airplane mode, etc. Broadcast Receivers are used to respond to these system-wide events. Broadcast Receivers allow us to register for the system and application events, and when that event happens, then the register receivers get notified.

Apps can use services to do long-running processes in the background, such as downloading files from a server, or checking for email, or checking your location. Although services don't show up or interact with you directly, they still show up in the "Running apps" list. Broadcast receivers are the third kind of component. Like services, they only exist in the background and don't interact with you directly. But unlike services, they can't stay running or perform long tasks: they exist to respond to events. And unlike activities and services, more than one broadcast receiver can be started in one go.


**Output:**

**Light Theme:**

<img src="https://github.com/rutviprajapati16/MAD_Practical8_21012011123/assets/97946004/04c6b0c6-d473-401d-9a8e-da08f22b625e" height="400" width="250">
<img src="https://github.com/rutviprajapati16/MAD_Practical8_21012011123/assets/97946004/236caa98-a686-4d45-82b4-81d2e94ef319" height="400" width="250">
<img src="https://github.com/rutviprajapati16/MAD_Practical8_21012011123/assets/97946004/bf8282d1-a48e-4c73-aacc-bd9119685e4a" height="400" width="250">


**Dark Theme:**

<img src="https://github.com/rutviprajapati16/MAD_Practical8_21012011123/assets/97946004/40c02815-40c3-4028-b8ce-aaba88542fbb" height="400" width="250">
<img src="https://github.com/rutviprajapati16/MAD_Practical8_21012011123/assets/97946004/4cfbe5df-7083-4e3b-a322-7afa245fa85c" height="400" width="250">
<img src="https://github.com/rutviprajapati16/MAD_Practical8_21012011123/assets/97946004/8a5bb133-95f7-4e21-8c14-1b858d8ab429" height="400" width="250">


