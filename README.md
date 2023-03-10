<h1><b>Bug Reporting Software Quality Assurance</b></h1>

> 🔍 Finding a bug is one thing, but documenting it is just as important.

Good bug reporting is needed to help the developer easier to understand our bugs report, so that will make our work quick and save much time for both Engineer and QA.

## <b>🍳 Preparations</b>
<li>Collect all required data</li>
<li>Have access to design file</li>
<li>Mastering the Product Requirement Document (PRD)</li>
<li>Know root cause of the bugs</li>
<li>Know your main and support team</li>

## 🎯 Bugs Priority and Severity
### Bugs priority
Priority is how quickly a bug should be fixed and eradicated from the website. Bug priority indicates the sense of urgency in dealing with a bug on our website.
<li>P0 - "Must-now" aka "Critical"</li> 
<li>P1 – "Must-have" aka "Major"</li> 
<li>P2 – "Important to have" aka "Minor"</li> 
<li>P3 – "Nice to have" aka "Low"</li>

### Bugs severity
Bug severity defines how serious a bug is and how badly it affects functionality.
<li>Critical</li> 
<li>Major</li> 
<li>Minor</li> 
<li>Low</li>

#### Notes:
<li><b>Development bug</b>: If QA found a critical bug, it should be set as [P0] on the bug development ticket.</li>
<li><b>Production bug</b>: Immediately raise on the related channel and mention stakeholder, please provide the isolated case and proof (log, video, etc) and create a Production bug ticket.</li> 

## 🎼 Bug title
It must be very detailed and intuitive, so the developer can have an idea of what the bug is just by reading the title  –  usually, the title is a short summary of the bug's description and reflected the bug itself.

## 📝 Bug descriptions
The bug's description must have the following structure:
<li>Steps to reproduce the bug</li>
<li>Actual result</li>
<li>Expected result</li>

## 🌲 Environment
If your ticket management product have an "Environment" placeholder, QA should write down the following information:
<li>Device</li>
<li>Operating System (OS)</li>
<li>Firmware</li>
<li>Account used and password</li>
<li>Testing environment</li>
<li>Testing app version</li>
<li>Connection type <i>(if applicable)</i></li>

## 🍿 Bug evidence
Bug evidence in software quality assurance is information gathered about a bug or defect in software during testing. It helps identify the cause of the bug and determine a solution for fixing it, in order to improve the quality of the software.
<li>Any pertinent screenshots, videos, or log files should be attached.</li>
<li>Bug reports usually require both a video and a screenshot, depending on the nature of the issue.</li>
<li>If the issue requires steps to trigger the bug, then a video is required.</li>
<li>If the bug is, say, a minor UI issue that is always present, then a screenshot will suffice.</li>
<li>Logs are also required no matter the issue.</li>
<li>For application crashes, it requires both system logs and crashes log dumps, otherwise, developers are left searching for a needle in a haystack, and this saves them valuable time.</li>
<li>Make sure you give the right attachment. Not every bug need video, sometimes it's better to put it as an image.</li>


## 🎉 Conclusion
<b>Mandatory information QA needs to include:</b>
<li><b>Where</b>: The location of the bug.</li>
<li><b>When & How</b>: Specify the condition, how to make the bug easily reproduced.</li>
<li><b>What</b>: The bug, itself. What happened to the AUT. (Application under test).</li>
<li><b>Reproduce rate</b>: How many tries you did/how many tries the bug actually happen?.</li>
<li><b>Consequence</b>: If the bug happen, what is the impact to the AUT & User’s experience?.</li>
<li><b>Workaround</b>: Any way for the bug, so it will not happen? Or if the bug happen, can it be restored to the normal condition?.</li>
<li><b>Version</b>: Occurs in version or Fix in version.</li>
<li><b>Linked issues</b>: <i>if any</i></li>
</br>
I hope this repository is helpful for you! If you have any other questions, feel free to open an issue or submit a pull request.
