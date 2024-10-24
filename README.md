


> Written with [StackEdit](https://stackedit.io/).


# Adhan  :mosque:
It is a Windows application linked to ***timesprayer***[^1]: site that lets you know the prayer times and reminds you of them .

### A look at the welcome interface:

![alt text](https://github.com/AmmarAloufy/test1/blob/main/UI.png?raw=true)



## Key Features: :key:
* **Prayer Times:**  Displays accurate prayer times based on your location.
* **Athan Alert:** when the call to prayer is approaching
* **Customizable Alerts:** Allows you to adjust alert sounds.
* **UI/UX Flexibility:** Features a user-friendly, flexible interface, making it accessible for all skill levels.
* **Widgets:** Offers desktop widgets for quick access to prayer times

## Installation Guide: :memo:
1. Download from ***github***[^2].
2. Open program.
3. Select loction install.

>**note:** if you want program start with windows :
> 1. Open setting.
> 2. Click on startup with windows.

## User Guide: :mag:

### How to activate the adhan alarm:
 - [x] Fajr
  - [x] Dhuhr
  - [x] Asr
  - [ ] ~~Maghrib~~
 - [x] Isha

---
### Collaboration
| Feature|Description | 
|--|--|
|  Task Assignments|Assign specific prayer times and alert responsibilities to others. | 
|  Community Notifications| Send prayer-related announcements or events to all users in the network. | 

---
###  Example of a prayer report generated in JSON format:
```json
{
  "prayers": [
    {"name": "Fajr", "time": "05:02 AM", "athan_alerts_sent": 50},
    {"name": "Dhuhr", "time": "12:05 PM", "athan_alerts_sent": 45},
    {"name": "Asr", "time": "03:23 PM", "athan_alerts_sent": 40},
    {"name": "Maghrib", "time": "05:51 PM", "athan_alerts_sent": 60},
    {"name": "Isha", "time": "07:21 PM", "athan_alerts_sent": 55}
  ],
  "total_users": 100,
  "date": "2024-10-22"
}

```
---
## Troubleshooting: :bomb:

 - Use the program without an Internet connection.
 - The widget is not appearing on the desktop.
 - The program doesn't start with Windows.

## Advanced Usage: :dart:

 - **Advanced Notifications:** set multiple notifications for each prayer (e.g., 15 minutes before prayer).
 - **Multiple Location Support:** Add multiple locations by entering city names or coordinates.



[^1]:https://timesprayer.com/
[^2]:https://github.com/AmmarAloufy/test1


<!--stackedit_data:
eyJoaXN0b3J5IjpbLTQwMTc4MzgxMywtNzIzNDk2MjgxLDIwMz
EzMjM5NzldfQ==
-->