Download Link: https://assignmentchef.com/product/solved-homework-03-selection
<br>
<h2>Goals</h2>

<ul>

 <li>Get familiar with ​<strong>boolean</strong>​ expressions</li>

 <li>Get familiar using ​<strong>if-then-else</strong>​ statements</li>

 <li>Get familiar using ​<strong>switch</strong>​ statements</li>

</ul>

<h2>Introduction</h2>

The types of programs you currently have the ability to create must strictly adhere to just one possible path of execution. This means that your programs can really do only one type of action or calculation, such as generating a username or displaying the area of a triangle. Selection, using ​<strong>if-then-else</strong>​ and/or ​<strong>switch</strong>​ statements, opens up a new world of possibilities by allowing a computer to evaluate one or more conditions, then act on them.




For instance, instead of making separate programs to let a user calculate the area of circles, triangles, and squares, you can now build all of that functionality into one program, and present the user with a menu to choose from. You will experiment with the use of selection to determine menu choices below.




<h2>Description</h2>




For this homework, your task is to create a program that prompts a user for their choice of processor, memory, storage, graphics, and mouse or trackpad. The program should then display the total price of the desktop computer with the desired specifications. Since we are dealing with money, please display the total price with two decimal places.




Note that the starting price of the desktop to be customized is ​<strong>4999.0</strong>​. The pricing is based off of the machine <u>​</u><u>here</u><u>​</u>. Please use the example output below to see how your program should look. The output you get on your screen should match that in the picture — please be careful with typos. Below is the cost to be added for each component.




<strong> </strong>Upgrade costs




<strong>Processor </strong>




<table width="624">

 <tbody>

  <tr>

   <td width="312"><strong>Component </strong></td>

   <td width="312"><strong>Additional cost </strong></td>

  </tr>

  <tr>

   <td width="312">8-core Intel Xeon W</td>

   <td width="312"><strong>0.0 </strong></td>

  </tr>

  <tr>

   <td width="312">10-core Intel Xeon W</td>

   <td width="312"><strong>800.0 </strong></td>

  </tr>

  <tr>

   <td width="312">14-core Intel Xeon W</td>

   <td width="312"><strong>1600.0 </strong></td>

  </tr>

  <tr>

   <td width="312">18-core Intel Xeon W</td>

   <td width="312"><strong>2400.0 </strong></td>

  </tr>

 </tbody>

</table>




<strong>Memory </strong>




<table width="624">

 <tbody>

  <tr>

   <td width="312"><strong>Component </strong></td>

   <td width="312"><strong>Additional cost </strong></td>

  </tr>

  <tr>

   <td width="312">32GB DDR4 RAM</td>

   <td width="312"><strong>0.0 </strong></td>

  </tr>

  <tr>

   <td width="312">64GB DDR4 RAM</td>

   <td width="312"><strong>800.0 </strong></td>

  </tr>

  <tr>

   <td width="312">128GB DDR4 RAM</td>

   <td width="312"><strong>2400.0 </strong></td>

  </tr>

 </tbody>

</table>




<strong>Storage </strong>




<table width="624">

 <tbody>

  <tr>

   <td width="312"><strong>Component </strong></td>

   <td width="312"><strong>Additional cost </strong></td>

  </tr>

  <tr>

   <td width="312">1TB SSD</td>

   <td width="312"><strong>0.0 </strong></td>

  </tr>

  <tr>

   <td width="312">2TB SSD</td>

   <td width="312"><strong>800.0 </strong></td>

  </tr>

  <tr>

   <td width="312">4TB SSD</td>

   <td width="312"><strong>2800.0 </strong></td>

  </tr>

 </tbody>

</table>




<strong>Graphics </strong>




<table width="624">

 <tbody>

  <tr>

   <td width="312"><strong>Component </strong></td>

   <td width="312"><strong>Additional cost </strong></td>

  </tr>

  <tr>

   <td width="312">Radeon Pro Vega 56</td>

   <td width="312"><strong>0.0 </strong></td>

  </tr>

  <tr>

   <td width="312">Radeon Pro Vega 64</td>

   <td width="312"><strong>600.0 </strong></td>

  </tr>

 </tbody>

</table>







<strong>Mouse or Trackpad </strong>




<table width="624">

 <tbody>

  <tr>

   <td width="312"><strong>Component </strong></td>

   <td width="312"><strong>Additional cost </strong></td>

  </tr>

  <tr>

   <td width="312">Mouse</td>

   <td width="312"><strong>0.0 </strong></td>

  </tr>

  <tr>

   <td width="312">Trackpad</td>

   <td width="312"><strong>50.0 </strong></td>

  </tr>

  <tr>

   <td width="312">Both</td>

   <td width="312"><strong>149.0 </strong></td>

  </tr>

 </tbody>

</table>




<h2>Example output</h2>




<strong> </strong>










<h2>Requirements</h2>




You are required to create one class, ​<strong>ComputerCustomizer</strong>​, that follows the specifications outlined above. It is to be held in a file called ​<strong>ComputerCustomizer.java</strong>​. For this homework, you can assume that the user will only enter a valid menu choice.


