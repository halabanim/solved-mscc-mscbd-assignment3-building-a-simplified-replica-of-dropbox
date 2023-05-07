Download Link: https://assignmentchef.com/product/solved-mscc-_mscbd-assignment3-building-a-simplified-replica-of-dropbox
<br>
Assignment 3: Building a simplified replica of

<h1>1           Assignment Information</h1>

<table width="322">

 <tbody>

  <tr>

   <td width="156">Course:</td>

   <td width="166">MSCC/MSCBD</td>

  </tr>

  <tr>

   <td width="156">Stage / Year:</td>

   <td width="166">1</td>

  </tr>

  <tr>

   <td width="156">Module:</td>

   <td width="166">Cloud Computing</td>

  </tr>

  <tr>

   <td width="156">Semester:</td>

   <td width="166">2</td>

  </tr>

  <tr>

   <td width="156">Assignment:</td>

   <td width="166">3 of 3</td>

  </tr>

  <tr>

   <td width="156">Date of Issue:</td>

   <td width="166">2021-03-04</td>

  </tr>

  <tr>

   <td width="156">Assignment Deadline:</td>

   <td width="166">2021-05-23 (End of week 12)</td>

  </tr>

  <tr>

   <td width="156">Assignment Submission:</td>

   <td width="166">Upload to Moodle</td>

  </tr>

  <tr>

   <td width="156">Assignment Weighting:</td>

   <td width="166">24% of Module</td>

  </tr>

 </tbody>

</table>

<h1>2           Introduction</h1>

<strong>NOTE: read the whole assignment brief first before implementing it contains very important information</strong>

In this assignment you will be building a simplifed replica of the Dropbox cloud service. You will be required to have storage available for users where they can create arbitrary directory structures and can upload files and download files from the service. There should also be some access to some basic file sharing between accounts.

It is recommended that the structure of the assignment is closely followed with the brackets as you will need to get the directory structure working first before you will be able to upload and download files or attempt the later brackets after this.

<strong>Very Important: Take note of the grade brackets listed below. These are meant to be completed in order. If you skip a bracket or do not complete a bracket following brackets will not be considered for marking. You should be well capable of producing strong and generally robust software by now. For example if there are six brackets and you fail the third one, then the fourth, fifth, and sixth brackets will not be marked. Documentation brackets will be treated separately from Coding brackets.</strong>

You should also be aware that I will remove marks for the presence of bugs anywhere in the code and this will incur a deduction of between 1% and 15% depending on the severity. If you have enough of these bugs it is entirely possible that you may not score very many marks overall. I want robust bug free code that also validates all user input to make sure it is sensible in nature.

Also note that the percentage listed after the bracket is the maximum mark you can obtain if you complete that many brackets without error. Everything in all brackets is mandatory.

<h1>5           Coding Brackets</h1>

<ol>

 <li>Bracket 1

  <ul>

   <li>Write the shell of an application that has a working login/logout service.</li>

   <li>Create models of a user, directory, and file using appropriate datatypes.

    <ul>

     <li>If a user logs in for the first time a user model should be created for them.</li>

     <li>a default root directory (path of /) should also be created for this user.</li>

    </ul></li>

  </ul></li>

</ol>

<ol start="2">

 <li>Bracket 2  Add the ability for a user to create a directory (Bracket failure if the same directory name is allowed in the current directory) • Add the ability for a user to delete a directory (Bracket failure if the wrong directory is removed)</li>

 <li>Bracket 3

  <ul>

   <li>Add the ability to change into a directory</li>

   <li>Add the ability to go up a directory with the special entry (path of</li>

  </ul></li>

</ol>

../)

<ul>

 <li>If a user is in their root directory don’t display (path of ../)</li>

</ul>

<ol start="4">

 <li>Bracket 4  Allow the user to upload a file to the current directory and store it in the cloud storage bucket. This should not overwrite a file that is already there. If a file is already there ask the user if they want to overwrite it.

  <ul>

   <li>Allow the user to delete a file from the current directory (Bracket failure if the wrong file is deleted.</li>

   <li>Allow the user to download a file from the current directory to the local machine.</li>

  </ul></li>

 <li>Bracket 5  Prevent the deletion of a directory that still has files remaining. Provide an appropriate warning to the user. • Prevent the deletion of a directory that still has directories remaining. Provide an appropriate warning to the user.</li>

 <li>Bracket 6  Add in the ability to detect duplicate files in the current directory. Display the files that match • Add in the ability to detect duplicate files in a user’s entire dropbox.</li>

</ol>

Display the files and paths that match

<ol start="7">

 <li>Bracket 7

  <ul>

   <li>Add the ability to share files read only between multiple user accounts 8. Bracket 8 (80%) UI design: Well thought out UI design that is intuitive and easy to use.</li>

  </ul></li>

</ol>