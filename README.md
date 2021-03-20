# powerpoint_master-notes
Epiphany number 3,812!!

After years and years of wondering what on earth is going on at Microsoft that they have done no feature changes of significance to PowerPoint, and frustration whenever I change the Notes Master, that I must go to every slide, one by one, and right click on the notes page, click on Notes Layout, select Reapply Master, then click OK (that is 4 clicks per slide!) a solution has landed!!!

Check out the video of this:
https://youtu.be/wEGtnN-t0cU

You can view the article on my web site: https://www.cellstream.com/reference-reading/tipsandtricks/17-apply-master-to-all-notes-pages-in-ms-powerpoint

Now, in order to implement this, you must have the "Developer Tab".  By default, this tab is not present. 

So the first step is to enable this tab. 

Select FILE, then select Options, and a dialogue box will pop up.  In that box, select "Customize Ribbon:

pptdeveloper

You will see on the right (highlighted) that you need to select the Developer box.  Then click OK.

You should now see the Developer Tab.

Click on the Developer Tab.  Select Macros.  In the Macro Name box, type: ApplyMasterToNotes, then click Create.

A dialogue will open.  Paste the code in between the "Sub ApplyMasterToNotes()" and "End Sub"

I suggest you apply this to all presentations so this Macro is available. Now close the dialogue. Don't worry it saved.

Now, go to the View Tab in PowerPoint. Select the Notes Pages View. Click back on the Developer tab. Select Macros. Your Macro is waiting. Select it and run it, and watch every note page get adjusted. What a great feeling!

Once done, save your presentation.  You will have to save it as a "Macro Enabled" PowerPoint - FYI.

Now seriously, how hard would it be for Microsoft to incorporate this as an option?

Enjoy!

I hope you find this article and its content helpful.  Comments are welcomed below.  If you would like to see more articles like this, please support us by clicking the patron link where you will receive free bonus access to courses and more, or simply buying us a cup of coffee!, and all comments are welcome!
