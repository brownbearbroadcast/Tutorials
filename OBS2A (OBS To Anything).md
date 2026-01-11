This tutorial assumes you have installed [OBS](https://obsproject.com/kb/quick-start-guide).

The video portion is extremely straightforward:
1. In OBS, press the “**Start Virtual Camera**” button.
2. In your streaming platform, set the camera to “**OBS Virtual Camera**”

The audio is a bit tricky if you don’t have a spare Digital Audio Interface in/out.

For both, you will

1. In OBS, navigate to the **Settings** (button in the lower right corner).
2. In the pop-up menu, navigate on the left-hand sidebar to **Audio**
3. You may need to scroll down, but click on the dropdown menu under "**Advanced**" labeled “**Monitoring Device**”

Option 1 (Easy): Digital Audio Interface

1. Create a route from your computer to the interface, and back to the computer.
2. Select the designated output (input of the interface) in the drop down menu.
3. In your desired streaming platform, select your designated input (output of the interface).

Option 2 (a bit harder): VB-CABLE

1. Install **[VB-Cable](https://vb-audio.com/Cable/)**. If you work in Corporate A/V or are using this commercially, the license is **[five dollars](https://shop.vb-audio.com/en/win-apps/11-vb-cable.html)**.
2. Follow the prompt and **restart your computer** (seriously).
3. In OBS, select "**CABLE Input (VB-Audio Virtual Cable)**"
4. In your desired streaming platform, select "**CABLE Output (VB-Audio Virtual Cable)**".

In either case, make sure to press **Apply** and then **Okay** in the bottom right corner.

In the **Audio Mixer** pagelet (in the lower middle), click the **Advanced Audio Properties** button (**two gears**), and in the dropdown menus labeled **Audio Monitoring**. and set each source you'd like to use as **Monitor and Output**.
