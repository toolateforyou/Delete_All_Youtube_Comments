# Delete_All_Youtube_Comments
Script to automate deleting all of your youtube comments

1. Go to youtube.com, Log into your account. You should now be at youtubes home page.

2. In the top left corner, click the ≡ menu icon. A sidebar menu on the left should have expanded showing home, shorts, subscriptions etc. Scroll down and click "History". (If having troubling getting to history, click [HERE](https://www.youtube.com/feed/history) to be taken there.

3. On the right side, click "Comments". "Your YouTube Comments" page will open.

4. Press the F12 key on the keyboard on this page. A developer menu will open. Click on the console tab at the top. type:

 
5. Paste this script below, then press enter. It may warn you, and in some instances ask you to type "allow pasting" (without parentheses) then press enter. Do as it says. Now paste the script and hit the enter key.

You can minimize the window while it finishes. Best to do this in a private browser window so no extensions are enabled.

Original code credit goes to [RubenPonce](https://github.com/RubenPonce/Delete-Your-Youtube-Comments), before I modified it.

> [!NOTE]
> If not sticking and comments are still showing up as not being deleted, try adjusting sleep value intervals to:
> ```
> await sleep(6000);
> ```
> and second sleep value to:
> ```
> await sleep(12000);
> ```



------------------------------------------------------------------------------------
