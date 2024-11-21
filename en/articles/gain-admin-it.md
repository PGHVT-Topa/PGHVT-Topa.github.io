# Gain admin privileges on any IT computer

This is a simple guide on how you can log in as the hidden Administrator account in Windows 10 and 11

> ## Requirements
>
> - A [windows installation media USB](https://www.microsoft.com/en-us/software-download/windows10ISO) (must be windows 10 or 11)

## Boot into USB

1. Plug the USB drive into the computer

2. Open the start menu, hold **Shift** and click **Restart** then wait

3. When you see a blue **Choose an option** screen click on **Use a device**

4. Find your USB drive in the list and click it

## Replace sticky keys executable (sethc.exe)

1. After it loads, press **Shift** and **F10** (no need to install anything)

2. In the cmd window type *notepad* and hit **Enter**

3. In notepad click **File**, then **Open** \| OR \| Press **Ctrl** and **O**

4. Navigate to *C:\Windows\System32*

5. Find *sethc.exe* and delete it, or rename it to something else

6. Find *cmd.exe* and copy it, then paste it

7. Refresh the window by either closing it and opening it again, or pressing **F5**

8. Find *cmd - Copy.exe* and rename it to *sethc.exe*

9. Close everything and restart (also unplug the USB drive)

## Enable Administrator account

It is also possible to make your own account an administrator, but its generally not a good idea.

1. On the lock screen, press **Shift** until a cmd window opens

2. In it type *net user administrator /active:yes* and hit **Enter**

3. Close cmd and log into the **Administrator** account

 - With that account you can install anything without any issue

## Deactivate the Administrator account

Because the teacher might check your computer after class its best to disable the Administrator account.

1. In the start menu type *cmd* and click on **Run as administrator**

2. Type *net user administrator /active:no*

Once you log out, the Administrator account will again become hidden.