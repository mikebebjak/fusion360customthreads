# Autodesk Fusion360 Custom Threads

The new Thread feature in Autodesk Fusion360 is very handy because it allows you to quickly make threads instead of creating paths and sweeps but it only contains a few common threads.

I had a project that required a GPI 38-400 plastic thread (on many plastic bottles like a maple syrup one from Kirkland) and I couldn't find a close thread that existed.
Fortunately there is a way to create an XML file (thanks ChatGPT) that has the thread data and then insert it into the correct folder (this was the hard part).
Follow the steps in this article: https://www.autodesk.com/support/technical/article/caas/sfdcarticles/sfdcarticles/Custom-Threads-in-Fusion-360.html

On my PC the path was: C:\Users\mike_\AppData\Local\Autodesk\webdeploy\production\[most-recent-cloud-ID]\Fusion\Server\Fusion\Configuration\ThreadData

When I added my XML I was able to see it populate in the Thread tool in Fusion and it worked great!

XML file is attached as well as the modified Kirkland maple syrup cap that lets a lot less syrup through.

Below is the original red lid and the modified lid with a tighter spout. Enjoy wasting less syrup! :)

![image](https://github.com/user-attachments/assets/0c530fda-c6da-47a4-83ac-c2632b64099a)

![image](https://github.com/user-attachments/assets/f1914e2b-fc93-4a0b-aa1a-2657c93ab008)

![image](https://github.com/user-attachments/assets/7d0e774c-b5b7-4a08-b77d-1eae153bdcac)
