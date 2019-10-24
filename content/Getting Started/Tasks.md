---
title: "Task"
date: 2019-10-24T14:51:17+05:30
draft: true
---

### <span class="mw-headline" id="About_Tasks">About Tasks</span>

Tasks are actions that need to be taken to resolve a Case. A Task can be created by a Case Agent when working on a Case, or they can be created automatically by Process definitions and Service Level Agreement (SLAs).

<dl>

<dd>

<dl>

<dd>

<table style="width: 85%; margin-left: border-collapse: collapse; background: #FBFBFB; border: 1px solid #aaa; border-left: 10px solid #ffb400;">

<tbody>

<tr>

<td style="padding: 0.25em 0.25em;" align="left" valign="top" width="35px">

<img src="http://agileappscloud.info/aawiki/images/2/2a/Notepad.png" / >

</td>

<td>

**Note:** Tasks can be created manually, and they can be created by a [Process](/aawiki/index.php/Process "Process"). Generally, processes run on cases, but they can be defined for other objects, as well. Tasks, however, do not support processes.

</td>

</tr>

</tbody>

</table>

</dd>

</dl>

</dd>

</dl>

### <span class="mw-headline" id="Working_with_Tasks">Working with Tasks</span>

#### <span class="mw-headline" id="Completing_Tasks">Completing Tasks</span>

You can see multiple tasks at once in the **Tasks** tab. You can choose to see all of the tasks you are responsible for, all open tasks regardless of owner, or one of several other views.

When viewing a a Case record or some other record, the **My Tasks** area of the sidebar shows tasks related that are relevant to that record. Click **[Complete]** to mark a task as done.

<dl>

<dd>[![CaseMyTasks.png](/aawiki/images/d/dd/CaseMyTasks.png)](/aawiki/index.php/File:CaseMyTasks.png)</dd>

</dl>

#### <span class="mw-headline" id="Working_with_Process_Tasks">Working with Process Tasks</span>

When a [Process](/aawiki/index.php/Process "Process") runs, it creates tasks in the sequence defined by the process model. Here, for example, an evaluation process has begun, creating a task for Aaron Acme:

<dl>

<dd>[![ProcessTask.png](/aawiki/images/a/a3/ProcessTask.png)](/aawiki/index.php/File:ProcessTask.png)</dd>

</dl>

Processes are listed in the sidebar, along with tasks assigned to the current user.

To monitor the progress of the process, click the process name in the sidebar, as shown by the red arrow in the screenshot above. When you do, a window opens, displaying the process diagram. Here, the simple two-step process is displayed, with the next task(s) to be performed highlighted in red:

<dl>

<dd>[![ProcessInProgress.png](/aawiki/images/9/9e/ProcessInProgress.png)](/aawiki/index.php/File:ProcessInProgress.png)</dd>

</dl>

#### <span class="mw-headline" id="Creating_Tasks">Creating Tasks</span>

When viewing a Case record or some other record, click **Add Task** to begin a collaboration:

<dl>

<dd>[![CaseNewTask.png](/aawiki/images/2/20/CaseNewTask.png)](/aawiki/index.php/File:CaseNewTask.png)</dd>

</dl>

A dialog pops up that lets you choose the type of task to create:

<dl>

<dd>[![TaskSingleStep.png](/aawiki/images/4/46/TaskSingleStep.png)](/aawiki/index.php/File:TaskSingleStep.png)</dd>

</dl>

> ##### <span class="mw-headline" id="Single_Step">Single Step</span>
> 
> This option is the default. For this simple task type, you say what needs to be done, who needs to do it, and when you need it.
> 
> ##### <span class="mw-headline" id="Multi_Step">Multi Step</span>
> 
> A [Multi Step Task](/aawiki/index.php/Multi_Step_Task "Multi Step Task") lets you define a sequence of steps, where each step begins only when the previous step has been done. (Each step becomes a task for the designated user. When the task is completed, a new task is generated for the next step in the procedure.)
> 
> <dl>
> 
> <dd>[![TaskMultiStep.png](/aawiki/images/0/05/TaskMultiStep.png)](/aawiki/index.php/File:TaskMultiStep.png)</dd>
> 
> </dl>
> 
> For an approval step, you specify the point to go to if the approval request is rejected.
> 
> When approval _is_ granted, the next step in the sequence is carried out.
> 
> ##### <span class="mw-headline" id="Task_Form">Task Form</span>
> 
> The **Task Form** option opens up the full Task form. This is the form you would would see if you were in the Tasks tab and you clicked **[New Task]**. That form lets you put more detailed instructions in the Description field. It also lets you specify values for any fields that may have been added to the Tasks object.

<div class="printfooter">Retrieved from "[http://agileappscloud.info/aawiki/index.php/Tasks](http://agileappscloud.info/aawiki/index.php/Tasks)"</div>

<div id="catlinks" class="catlinks">

<div id="mw-normal-catlinks">[Category](/aawiki/index.php/Special:Categories "Special:Categories"): <span dir="ltr">[Case Management](/aawiki/index.php/Category:Case_Management "Category:Case Management")</span></div>

</div>
